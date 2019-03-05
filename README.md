# JEE Dev Stack: Oracle Java, Payara and MySQL/RabbitMQ

## Overview
VirtualBox
* Ubuntu 14.04
* Oracle JDK 8
* Payara 5
* MySQL 5.6

## Access from Host Environment
* Payara: https://localhost:14848 (admin / admin)
* MySQL:  jdbc:mysql://localhost:13306 (root / root) 

## Installation
1. Clone this repo
2. ```cd``` to oracle-jdk8-payara-mysql
3. Run ```vagrant plugin install vagrant-vbguest``` to install vagrant plugin for updating Virtual Box Guest Additions
4. Run ```vagrant up``` to bootstrap an ubuntu/trusty64 box with Java 8, Payara and MySQL


Based on: https://github.com/zezutom/vagrant-boxes