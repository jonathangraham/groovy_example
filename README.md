example of running a unit test in Groovy.

studentTest.groovy runs the JUnit test that will test the code in student.groovy

The class being tested needs compiling first: groovyc student.groovy
This will create a file called Student.class

then you can run the test: groovy studentTest.groovy