gradle-playground
=================

A bunch of small projects exploring the capabilities of [Gradle](www.gradle.org) in comparison to [Maven](maven.apache.org).

hello-world
-----------

The most simple Gradle project. Just execute `gradle helloWorld` to run it. Have a look at the `build.gradle`. Run `gradle world` to execute the most simple multi-task build.

java-library
------------

An example of a simple Java library bootstrapped with `gradle init --type java-library`.

Run `gradle build` (or `./gradlew build` if you want to use the wrapper) to build the project.

Run `gradle test` to execute the tests. Run `gradle -Dtest.single=Library test` to execute a single test. (I added some logging to make the test execution visible on the command line.)

gradle-lifecycle
----------------

This one demonstrates the simple lifecycle of a Gradle build and explains the difference of task configuration vs. task execution. Have a look at `build.gradle` and run `gradle lifecycle` to learn more.

