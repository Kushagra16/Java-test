OBJECTIVES:

Build and enhance the java code and make all the unit test cases pass.

TASK INVOLVED:

1.Create "getters" and "setters" on Person

2.Ensure that Person.setAge() throws an IllegalArgumentException when passed a value less than zero

3.Ensure that Person.setName() throws an IllegalArgumentException when passed a null String

4.Write a Person.count() that returns the total number of Person instances created

5.Ensure that Person.equals() returns true if two Person instances have the same name and age (salary doesn't factor into equality comparison). Make sure no exceptions are thrown from this method--anything "weird" should just return false.

6.Create an AgeComparator class that compares two Persons and arranges them by age (age 15 is less than age 25). This Comparator MUST BE a nested class inside of Person; Person's fields must remain private.

7.Make Person be Comparable, such that when I compare two Persons, they arrange themselves by salary in reverse order (salary 150000 is less than salary 10000). (Rich people to the front!)

8.Create a static method "getNewardFamily" that returns an ArrayList<Person> consisting of four Person objects: Ted, age 41, salary 250000; Charlotte, age 43, salary 150000; Michael, age 22, salary 10000; and Matthew, age 15, salary 0.

9.Lastly, you will need to implement a final test, marked in comments in the TestPerson class, which will register a "PropertyChangeListener" instance. This PropertyChangeListener will need to call the three "assertEquals" calls (as described in the comments) in order to test that the property did change. You shouldn't change anything above or below the comment lines beyond that.
