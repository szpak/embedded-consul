# embedded-consul changelog

## 2.2.0 - Unreleased

 - mass dependency update
 - automatic Continuous Delivery release process
 - basic compatibility tests with OpenJDK 8, 11 and 15 on CI server 

## 2.0.0 - 2018-12-04

### BREAKING CHANGES:
 
 - jdk1.7 end of support
 - default Consul version 0.8.+

### NEW FEATURES

 -  Added possibility to pass `raft_protocol` via `ConsulBuilder` which allows to test new [Consul Autopilot](https://www.consul.io/docs/guides/autopilot.html) feature

## 1.1.1 - 2018-06-01

 - last version supporting Java 1.7
