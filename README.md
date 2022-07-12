# Simple Bank REST API

## Problem Description

* User Story:
  * [ ] User can access the bank account 
  * [ ] User can change the currency
  * [ ] All balance will be recorded in database
  * [ ] User can transfer to another account
---

## Prerequisites to run the application

* Development
  * Docker [installation]([stackoverflow.com/questions/37405528/ddg#38909715](https://docs.docker.com/desktop/release-notes/))
  * PPGAdmin
    ```bash
    $ sudo curl https://www.pgadmin.org/static/packages_pgadmin_org.pub | sudo apt-key add
    $ sudo sh -c echo "deb https://ftp.postgresql.org/pub/pgadmin/pgadmin4/apt/$(lsb_release -cs) pgadmin4 main" > /etc/apt/sources.list.d/pgadmin4.list && apt update
    $ sudo apt install pgadmin4
    $ sudo /usr/pgadmin4/bin/setup-web.sh
    ```
  * PostgreSQL 14 Image
    ```bash
    $ docker pull postgres:14-alpine
    ```
  * Golang-migrate :
    ```bash
    $ curl -L https://packagecloud.io/golang-migrate/migrate/gpgkey | apt-key add -
    $ echo "deb https://packagecloud.io/golang-migrate/migrate/ubuntu/ focal main" > /etc/apt/sources.list.d/migrate.list
    $ apt-get update
    $ apt-get install -y migrate
    ```
---
## ERD
> ERD Diagram of bank application
![Merge Sort Example](/images/bank.png "ERD")
## API Documentation
More about API Implementation, explained in postman collection:
[API Documentation](https://documenter.getpostman.com/view/8882188/TzzBourT)

---

## Run Application & Test Suite

* Application


* Test Suite

