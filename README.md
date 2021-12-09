# java-cli-maven-spring-failsafe-findbugs-pmd-jacoco-mockito-car-data

## Description
Analyze source code for potential bugs.
A POC for spring app. Testing done with failsafe
pmd, and jacoco plugins using mockito framework.

## Tech stack
- java
- maven
	- findbugs
  - spring
  - failsafe
  - jacoco
  - pmd
  - mockito
    - junit5

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- pmd report found at bin/target/site
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code concept](https://github.com/eugenp/tutorials/tree/master/testing-modules/junit-5)
