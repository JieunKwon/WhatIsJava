#  What is Java

  -  Describe and define about Java
  
 

> JVM .Java Vitual Machine.
  - it is an abstract machine which provides the runtime environment in which Java bytecode can be executed. It is a specification which specifies the working of Java Virtual Machine. Its implementation has been provided by Oracle and other companies. Its implementation is known as JRE. 
JVMs are available for many hardware and software platforms (so JVM is platform dependent). It is a runtime instance which is created when we run the Java class. There are three notions of the JVM: specification, implementation, and instance.

> JRE
  - JRE stands for Java Runtime Environment. It is the implementation of JVM. The Java Runtime Environment is a set of software tools which are used for developing Java applications. It is used to provide the runtime environment. It is the implementation of JVM. It physically exists. It contains a set of libraries + other files that JVM uses at runtime.

> JDK
  - JDK is an acronym for Java Development Kit. It is a software development environment which is used to develop Java applications and applets. It physically exists. It contains JRE + development tools. JDK is an implementation of any one of the below given Java Platforms released by Oracle Corporation



> 1. What is Java?
  - Java is a high-level programming language originally developed by Sun Microsystems and released in 1995. Java runs on a variety of         platforms, such as Windows, Mac OS, and the various versions of UNIX.
  
> 2. Java features 
  - Object Oriented, Platform Independent, Robust, Interpreted, and Multi-threaded
 
> 3. Object
  - Object is a runtime entity and it’s state is stored in fields and behavior is shown via methods. Methods operate on an object's          internal state and serve as the primary mechanism for object-to-object communication.

> 4. Class 
  - is a blue print from which individual objects are created. 
   A class can contain fields and methods to describe the behavior of an object.

> 5. Steps for creating an Object for a class?
  - An Object is first declared
  - instantiated
  - initialized

> 6. Inheritance
  - It is the process where one object acquires the properties of another. With the use of inheritance the information is made        manageable in a hierarchical order. 

> 7. Polymorphism 
  - the ability of an object to take on many forms. 
   The most common use of polymorphism in OOP occurs when a parent class reference is used to refer to a child class object.

> 8. Abstraction
  - It refers to the ability to make a class abstract in OOP. 
  It helps to reduce the complexity and also improves the maintainability of the system.

> 9. Encapsulation
  - It is the technique of making the fields in a class private and providing access to the fields via public methods. 
  If a field is declared private, it cannot be accessed by anyone outside the class, thereby hiding the fields within the class.           Therefore encapsulation is also referred to as data hiding.
  
  - The primary benefit of Encapsulation is the ability to modify our implemented code without breaking the code of others who use our      code. With this Encapsulation gives maintainability, flexibility and extensibility to our code.

> 10. Abstract class & Method
  - cannot be instantiated and are either partially implemented or not at all implemented. 
  This class contains one or more abstract methods which are simply method declarations without a body.
 
  - If a class contains a particular method but the actual implementation of that method is determined by child classes. it declares        the method in the parent class as abstract.

> 11. Interface
  - a collection of abstract methods. A class implements an interface, thereby inheriting the abstract methods of the interface.

> 12. Super keyword 
   - If the method overrides one of its superclass's methods, overridden method can be invoked through the use of the keyword super. It can be also used to refer to a hidden field.
    
> 13. Packages
  - A Package can be defined as a grouping of related types(classes, interfaces, enumerations and annotations ) providing access         protection and name space management.
  
  - Packages are used to prevent naming conflicts, to control access, to make searching/locating and usage of classes, interfaces, enumerations and annotations, etc., easier.
  
> 14. public static void main (String args[ ])

   The following shows the explanation individually −
   public − it is the access specifier.
   static − it allows main() to be called without instantiating a particular instance of a class.
   void − it affirns the compiler that no value is returned by main().
   main() − this method is called at the beginning of a Java program.
   String args[ ] − args parameter is an instance array of class String

> 15. Method overloading

    Method overloading increases the readability of the program. 
    If a class has multiple functions by same name but different parameters, the method is overloaded

> 16. overriding

    If a subclass provides a specific implementation of a method that is already provided by its parent class, 
    it is known as Method Overriding. parameter must be same in case of overriding

