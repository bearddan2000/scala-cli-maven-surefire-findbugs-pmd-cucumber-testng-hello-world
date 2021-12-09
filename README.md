# scala-cli-maven-surefire-findbugs-pmd-cucumber-testng-hello-world

## Description
Analyze source code for potential bugs.
A POC for maven app using testNg
and cucumber framework with surefire
and PMD plugins.

## Tech stack
- scala
- maven
	- findbugs
  - testNg
  - surefire
  - cucumber
  - PMD

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
- [Code concept](https://stackoverflow.com/questions/67847818/maven-junit-5-cucumber-not-running-tests)
- [PMD example](https://github.com/eugenp/tutorials/blob/master/static-analysis/src/main/resources/logback.xml)
