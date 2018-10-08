# SimpleTraining1Web

## Required
1) Need install MySql database. schema name="test", username="root", password="root"
2) This program need 8080,8081,8082 ports
3) JDK8

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
http://localhost:8080/category/initData


### Access
http://localhost:8080/login