                         PROJECT:Travel And Tourism MANAGEMENT SYSTEM

requestment jar file

1) jcalendar-tz-1.3.3-4
2) mysql-connector-j-8.3.0




DATABASE TABLES:

                 #========account table===========#
create table account(username varchar(50),name varchar(50),password varchar(50),security varchar(50),answer varchar(50));

                  #========admin table==========#
create table admin(name varchar(50),username varchar(50),password varchar(50),email varchar(50),phone varchar(50),pancard varchar(50));

                 #========customer table==========#
create table customer(name varchar(50),username varchar(50),password varchar(50),email varchar(50),phone varchar(50),pancard varchar(50));

                #========adminlogin table==========#
create table adminlogin(username varchar(50),password varchar(50));

                #========bookhotel table==========#
create table bookhotel(hotelname varchar(50),name varchar(50),username varchar(50),persons varchar(50),days varchar(50),ac_nonac varchar(50),food varchar(50),totalprice varchar(50));

               #========bookpackage table==========#
create table bookpackage(place varchar(50),name varchar(50),username varchar(50),persons varchar(50),date varchar(50),totalprice varchar(50));

                  #========hotel table==========#
create table hotel(name varchar(50),state varchar(50),ac varchar(50),food varchar(50),hotelcost varchar(50),image longblob);

                 #========package table==========#
create table package(place varchar(50),state varchar(50),price varchar(50),days_nights varchar(50),description longtext,image longblob);
