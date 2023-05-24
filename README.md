# User_System

First install all the required modules

RUN pip install -r requirements.txt

connect the databse with "user-system"

CREATE TABLE user (
    id INT AUTO_INCREMENT PRIMARY KEY,
    first_name VARCHAR(50) NOT NULL,
    last_name VARCHAR(50) NOT NULL,
    mobile_number VARCHAR(20) NOT NULL,
    email VARCHAR(100) NOT NULL,
    password VARCHAR(64) NOT NULL,
    profile_photo VARCHAR(100) NOT NULL
);

RUN python main.py