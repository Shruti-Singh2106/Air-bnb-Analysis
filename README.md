# Air-bnb-Analysis
This is a EDA ( Exploratory data analysis) and Cumulative Analysis of Air bnb.  
Here is the overview of the data 

CREATE TABLE airbnb_listings (
    id BIGINT,
    NAME VARCHAR(255),
    host_id BIGINT,
    host_identity_verified VARCHAR(32),
    host_name VARCHAR(100),
    neighbourhood_group VARCHAR(100),
    neighbourhood VARCHAR(100),
    lat FLOAT,
    long FLOAT,
    country VARCHAR(100),
    country_code VARCHAR(10),
    instant_bookable VARCHAR(16),
    cancellation_policy VARCHAR(32),
    room_type VARCHAR(50),
    Construction_year FLOAT,
    price VARCHAR(32),
    service_fee VARCHAR(32),
    minimum_nights FLOAT,
    number_of_reviews FLOAT,
    last_review VARCHAR(32),
    reviews_per_month FLOAT,
    review_rate_number FLOAT,
    calculated_host_listings_count FLOAT,
    availability_365 FLOAT,
    house_rules TEXT,
    license VARCHAR(50)
);
