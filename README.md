# True Test
This is an example project designed to show the power of combining different automated testing techniques to create the most stable possible projects.  The idea behind this project was to give a basic framework for using all of the following techniques:

* Test Driven Development - Test first, implemenation later (Not really shown here, but the ideas hold true)
* Acceptance Criteria/Behavior Driven Development - Given/When/Then Structure
* Properties Based Testing - Random value generation for large acceptable sample space
* Mutation Testing - Test that your tests are actually validating the code

The Application is written in Java and utilizes the [Spock Framework](http://spockframework.org), with [Spock Genesis](https://github.com/Bijnagte/spock-genesis) for properties based testing and [Pitest](http://pitest.org) for Mutation Testing.
