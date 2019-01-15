# eventually-rx4j
Event sourcing library built on Java 9 Reactive types.

## Getting Started

Clone the project to get started.

### Prerequisites

You will need the following software at a minimum to build the project:

* Java 9+
* Gradle

### Installing

Getting your development environment running requires the installation of Java 9+.

Install Java 9+

```
# Debian
$ sudo apt-get install openjdk-9-jdk-headless
```

## Running the tests

```
$ ./gradlew test
```

## Usage

Usage of this script should be done during the deployment of your application. In order to use this script you will need to
1. Define your service and routes using the declarative format and save the format in your repository.
2. Update your .circle.yml file to run a job that will register your service with Kong
3. Create a job definition that will be run with k8s.

## Built With

* [Gradle](https://gradle.org/) - Build Tool
* [Maven](https://maven.apache.org/) - Dependency Management

## Versioning

We use [SemVer](http://semver.org/) for versioning. 

## Authors

* **Nathaniel Weems** - *Initial work*
