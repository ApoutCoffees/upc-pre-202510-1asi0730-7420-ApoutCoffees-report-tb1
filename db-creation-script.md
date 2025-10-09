
	create table companies(
		id varchar(100) primary key,
	    name varchar(100) not null    
	);

	create table informative_cards(
		id varchar(100) primary key,
	    description varchar(100)
	);

	create table coffees(
		id varchar(100) primary key,
		name varchar(100) not null,
	    image varchar(100),    
	    company_id varchar(100),
	    informative_card_id  varchar(100),
		foreign key (company_id) references companies(id),
	    foreign key (informative_card_id) references informative_cards(id)
	);

	create table mystery_boxes(
		id varchar(100) primary key,
	    name varchar(100) not null,
	    image varchar(100),
	    origin varchar(100),
	    profile varchar(100),
	    total_amount varchar(100),    
	    coffee_id varchar(100),
	    foreign key (coffee_id) references coffees(id)
	); 



	create table mystery_boxes_preview(
		id varchar(100) primary key,
	    name varchar(100) not null,
	    image varchar(100),
	    origin varchar(100),
	    profile varchar(100),    
	    coffee_id varchar(100),
	    foreign key (coffee_id) references coffees(id)
	);

	create table subscriptions(
		id varchar(100) primary key,
	    subscription_type varchar(100) not null,
	    discount int not null check(discount>=0)
	);

	create table accounts(
		id varchar(100) primary key,
	    email varchar(100) not null,
	    password varchar(100) not null,    
	    subscription_id varchar(100),
	    foreign key (subscription_id) references subscriptions(id)
	);

	create table users(
	    id varchar(100) primary key,
	    name varchar(100) not null,
	    age int not null,
	    sex varchar(10) not null,    
	    account_id varchar(10),
	    foreign key (account_id) references accounts(id)	    
	);

	create table consumer_profiles(
		id varchar(100) primary key,    
	    user_id varchar(100),
	    foreign key (user_id) references users(id)    
	);

	create table company_profiles(
		id varchar(100) primary key,
	    consume_metrics varchar(100),    
	    user_id varchar(100),
	    company_id varchar(100),
	    foreign key (user_id) references users(id),
	    foreign key (company_id) references companies(id)    
	);

	create table company_coffees(
		id varchar(100) primary key,
		name varchar(100) not null,
	    image varchar(100),
	    total_amount decimal not null check(total_amount>=0),
		cost_per_unit decimal check(cost_per_unit>=0),
		measurement_unit varchar(100) not null,
	    replenishment_frecuency varchar(100),
	    rating int check(rating>=0),    
	    company_profile_id varchar(100),
	    foreign key (company_profile_id) references company_profiles(id)
	);

	create table profile_mystery_boxes(
		id varchar(100) primary key,
	    name varchar(100) not null,
	    image varchar(100),
	    status varchar(100) not null,    
	    consumer_profile_id varchar(100),
	    foreign key(consumer_profile_id) references consumer_profiles(id)
	);

	create table profile_coffees(
		id varchar(100) primary key,
		name varchar(100) not null,
	    image varchar(100),    
	    consumer_profile_id  varchar(100),
		foreign key (consumer_profile_id) references consumer_profiles(id)
	);

	create table payments(
		id varchar(100) primary key,
	    total_price decimal not null check(total_price>= 0),      
	    account_id varchar(100),
		foreign key (account_id) references accounts(id)
	)



