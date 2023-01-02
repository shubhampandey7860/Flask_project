create virtual environment :
---> pip install virtualenv
---> virtualenv environmentName(e.g. venv)
---> cd venv/Scripts
--->  cd venv/Scripts/activate

# install these packages
pip install flask
pip install flask-mysqldb

# create database with name login
1. create database login


# create table accounts
create table accounts
(
id int(11) not Null Auto_INCREMENT,
username varchar(50) NOT NULL,
password varchar(50) NOT NULL,
email varchR(100) NOT NULL
PRIMARY KEY(`id`)
);



