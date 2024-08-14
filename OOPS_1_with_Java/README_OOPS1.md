In Scaler there are entities like: Student, Batch,Contest,Instructors, Class,Assignments,Mentors,etc
no need to go indepth only high level/birds eye, not go in depth how it should be just the idea/abstarct manner

1. Represent complex s/w sytems in terms of ideas/entities
2. Hiding details of complex implementation



Encapsulation:
Like a capsule that protects medicine and holds medicine
1. Holds attributes & behavious together=> via class
2. Protects attr & behav from outside world=>access modifier



Terms in OOPs:
1. Class: Blueprint of an entity
   class occupies no memory like blueprint of house on paper that does not hold actual rooms

2. Objects: to store actual information we need to create objects
   depending upon class, we can create instances of that class
   objects occupy space like a row in a table represents a particular student

Table structure: Class  ; A row in a table:Object

Instance:
What is an instance? In object-oriented programming (OOP), an instance is a specific realization of any object.
An object may be different in several ways, and each realized variation of that object is an instance.

IDEAS take mental space OBJECTS take physical space


Access Modifier:
defines how accessible is a member(methods,attributes) of a class.

class Student{
access_modifier data_type attr_name;	--> attribute --> public int age, private String name
access_modifier return_data_type	--> Method --> protected void changeBatch()
	method_name(...){
	}
}

Link to Code in IntelliJ [OOPS 1](https://github.com/Ak-github-dev/Java_OOPS/tree/main/OOPS_1_with_Java/src/main/java/org/example/OOPS01/)