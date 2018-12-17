#### start
FLASK_APP=hello.py flask run        

#### installation
pip install Flask     
pip install flask-mysqldb   

#### mysql
mysql -u root -p    
//password    
My4820806    

//create database    
CREATE DATABASE flaskapp;    
//use databse     
USE flaskapp    
//create table     
CREATE TABLE users(name varchar(20), email varchar(40));    


#### mac path for mysql
cd ~   
.open profile     
export PATH=${PATH}/usr/local/mysql/bin/     
export DYLD_LIBRARY_PATH=/usr/local/mysql/lib/     

//issue “Library not loaded: @rpath/libmysqlclient.21.dylib”     
sudo ln -s /usr/local/mysql/lib/libmysqlclient.21.dylib /usr/local/lib/libmysqlclient.21.dylib     

