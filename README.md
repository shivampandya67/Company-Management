# Company-Management
# youtube link : https://youtu.be/qQMt4FMMgUI

## how to download and run the code in linux

### Considering you have linux, docker, and docker-compose installed in your system

## Step 1
### create a folder with any name of your choice
### make sure you have the data, src, docker-compose.yml, Dockerfile, my.cnf which you will be as you will be downloading the code from here

## Step 2
### open a terminal and get into the folder which you just created.
### make sure when you do ls command after that you see the docker-compose file
### after that do `sudo docker-compose up -d`

## Step 3
### after the containers are created you can access the mysql container by doing the following
### write `sudo docker exec -it course-mysql /bin/bash`
### write `mysql -u root -p --local-infile`

## Step 4
### now you will be able to access the database and in these case "mydatabase"
### you need to insert the table as well as the data. I am attaching the txt file which has all the data with contraints and code for inserting the data from the dat file

## Step 5
### you are pretty much set. now you only need to run the php file. so open any browser and write localhost:8080/ and you will be able to access the first exercise which is index.php
