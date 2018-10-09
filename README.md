# SimpleTraining1Web

## Required
1) Need install MySql database. schema name="test", username="root", password="123abcABC"
2) This program need 8080,8081,8082 ports
3) JDK8

## DB installtion
### Windows
        In windows, we suggest use free installation version Mysql. 
        1) download the both files in \\172.17.3.100\Training\Microservice\Phase1-JavaBase\Examing and unzip in your local
        2) edit POC.txt in MySQLData. change "basedir" & "datadir" base on your path
        3) add "mysql-5.7.20-winx64\bin" into your system env path.
        
        The "test" schema default password is "123abcABC" 
        
### Linux
        In Linux, we have to install mysql or use mysql docker. and set the "test" schema password to "123abcABC".
        

## How to running
### Run price service module
```
git clone https://github.com/scorityzhu-aaxis/SimpleTraining1PriceService.git
cd SimpleTraining1PriceService
git checkout master
mvn spring-boot:run
```

### Run inventory service module
```
git clone https://github.com/scorityzhu-aaxis/SimpleTraining1InventoryService.git
cd SimpleTraining1InventoryService
git checkout master
mvn spring-boot:run
```

### Run this web module
```
git clone https://github.com/scorityzhu-aaxis/SimpleTraining1Web.git
cd SimpleTraining1Web
git checkout master
mvn spring-boot:run
```

### Inital temporary data

        If we use above free installation version Mysql. we do not need initial data.
        if we use ourself's mysql, we need initail data with blow url.  
        http://localhost:8080/category/initData


### Access
        http://localhost:8080/login

 


Training report
=====================================================
        Input all what you changed content blow.

## Mandatory items

###JDK8 Lambda Expression
        Input any comments here;
        
###Spring Validation
        Input any comments here;
        
###Springboot Unit Testing
        Input any comments here;

###Logging
        Input any comments here;
        
###Spring Security
        Input any comments here;
        
###Spring Data JPA - MySQL
        Input any comments here;
        
###Spring Data Redis
        Input any comments here;
        
###Springboot Application Performance Tuning
        Input any comments here;
        
## Optional items
        Add any your implemented items here. 