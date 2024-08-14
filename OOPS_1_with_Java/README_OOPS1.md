OOPS Directory

Intro to OOPS:

Object oriented Programing Language

Entities:
These are the core, they are made up of two things attributes & behaviours(methods/functions/behaviours).
They are anything for which we want to store the information in our system.
It is the table in SQL world

Attributes:
for example for a User we store attr like(name, email,phone number, DOB,address)
These form the columns in a table

Behaviours:OR Methods
What action can the entity perform
for example attend a quiz- a student should be able to perform it not the instructor
instructor can log in students dashboard




class Student{
    int age;
    String name;
    float psp;
    void changeBatch(){...}
	void joinClass(){..}
	void coursePause() {...}
}
age,name, psp are attributes
and changebatch,etc are behaviours




Main Concepts in OOPS:
1 Principle: Abstraction
3 Pillar: 	Polymorphism
            Encapsulation
            Inheritance

pillars support abstraction

Abstraction:
Idea, something i.e. not in existence.
Blueprint
does not take actual memory
It asks us to envision a complex system in terms of ideas/entities

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