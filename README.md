# Top-10-Java-Libraries


Top 10

There are hundreds of thousands of libraries out there. I want to save you a lot of time in research and choosing the best ones, the most well documented ones, the most supported and up-to-date ones as well the ones that should save as much time as possible.

I want to point out that these recommendations are all my personal opinions. They are all open source and free for use.

1. Java standard libraries   

        Yep, that’s right, you heard me right. A lot of people underestimate or do not fully know the Java Standard libraries and do not know how to unleash its full power when programming or they don’t use it at all. Here is a brief description of some of the libraries:
        
        java.lang is always implicitly being imported as it contains everything you basically cannot program without String, Double, Enum, Math, etc.
          In java.util you can find all the collections and data structures available in Java
          Next, we have java.io for reading files, working with pipes, streams and similar.
          Also we have java.nio, which actually is the alternative to java.io and stands for non-blocking I/O. It allows intensive use of the input/output operations as you might guess.
          java.math provides functionality for working with arbitrary-precision decimal (BigDecimal) and integer (BigInteger) values
          java.net is being used for working with sockets, creating connections or in short – creating networking applications
          In Java we also have libraries for working with GUI : javax.swing (extension of the older java.awt)
          We even can play music and create midi files with java.sound
    
      
2. JHipster  

     JHipster is a development platform to generate, develop and deploy Spring Boot + Angular Web applications and Spring microservices.
    
      Man, this one have saved me months of development . I could definitely say that this one is my personal favourite and that I keep a special place for it in my heart. It basically generates your whole application from your front-end to the back-end. The only thing you need to add is the business logic behind the architecture. The main and most important libraries, which are included in the generated project are:
    
      Spring Boot – helps you accelerate and facilitate application development
      Angular / AngularJS – JavaScript framework


3. Maven     

      Maven is a software project management and comprehension tool. Honestly, Maven is great. If you’ve never used Maven before, you’re missing out. Sometimes, I wonder how it was even possible to create enterprise applications prior to its creation.
    
     Maven can manage all your project dependencies, configurations and build configurations and even documentation only by specifying them in a single pom.xml file.


4. Apache Commons

      Apache Commons is actually a whole project focused on creating Java libraries.  
    
        Here is a short list of some of the best and most commonly used libraries:    
    
        Commons Math: The Apache Commons Mathematics Library – the name says it all: this library contains components allowing advanced mathematics and statistics operations and computations
        Commons CLI – provides API for parsing command line arguments. Why will you even bother creating an application without the ability to pass parameters and control its behavior?!
        Commons CSV – whatever you are developing, at some point you are going to face the necessity of using csv files. This include opening, reading, editing, saving and creating them. I suggest using the RFC 4180 format from the CSVFormat class and UTF-8 encoding when saving/creating files.
        Commons IO – it is being used for easier execution of input/output operations. Checking at least the ReversedLinesFileReader is definitely worth it.


5. Guava   

      Guava is the Google Core Libraries for Java.      
      It is a library for extending the basic Java collections functionalities    
      
      This is an utility I absolutely have to mention.      
      Did you ever needed ordering for your collections? Did you ever need to compare the contents there?   
      What about advanced sort and compare on multiple columns with multiple conditions?    
      
      I present you one of my most favorite components in this library:   
      ComparisonChain is used for implementing advanced and complicated comparison sort for collections.


6. google-gson      

      google-gson is helpful for converting Java Objects to JSON and vice versa.  
      
      This library is especially helpful when developing mobile applications and creating/using REST APIs as well as in any case you would need to convert a Java Object to its JSON representation and vice versa.


7. Hibernate-ORM     

        Hibernate-ORM is an object relational mapper.     
        It’s used for persisting of data in relational databases.       
        It provides an easier and more abstract way of doing that for the developers.     
        It uses JDBC in its implementation.     
        Hibernate is also an implementation of the JPA specification.   
      
  
8. Mockito  

      However, Mockito enables you to create mocks and write tests easier with simpler and cleaner code.      
      Writing great tests has never been easier!    
      

9. JUnit      

      JUnit is a free Java framework for writing unit tests.      
      It provides functionality for conducting repeatable tests on your code. You just need to be careful not to get obsessed with the numbers (% code coverage). Bigger code coverage does not always mean better and bug-less code.


10. Log4j and Slf4j       

        The two of these are both logging frameworks. Slf4j represents an abstraction for other logging frameworks (such as Log4j ). 
         On the other hand, Log4j is just a simple logging framework.     

