http://pythonbooks.revolunet.com/
-----------------------------------

* [Programming Computer Vision with Python](http://programmingcomputervision.com/downloads/ProgrammingComputerVision_CCdraft.pdf) Jan Erik Solem
* [Natural Language Processing with Python](http://nltk.org/book/)


Tips and Practices
==================
* public interface should be super clear
* separate creation (factory, builder, provider, wiring objects) from use (business logic, domain abstraction)
* context, data, algorithm, processor/executor
* declarative is more readable than imperative

> "The only way to go fast is to go well" - *Uncle Bob*

* "When in doubt, leave it out" http://www.infoq.com/articles/API-Design-Joshua-Bloch
* Pragmatic Programmer tips http://pragprog.com/the-pragmatic-programmer/extracts/tips
* Things Every Programmer Should Know http://www.javacodegeeks.com/2010/12/things-every-programmer-should-know.html

Testing
=======
* OO Design for Testability http://www.youtube.com/watch?v=acjvKJiOvXw (Miško Hevery, 2009)
    * new operators inside object,
    * global state, 
    * Law of Demeter violation
* The Deep Synergy Between Testability and Good Design http://vimeo.com/15007792 (Michael Feathers, 2010)
    * Testing is Easy in the Presence of Good Design - testing issues explained as design issues

Architecture
============

Philosophy
* Optimize for **deletability** http://vimeo.com/108441214 by Greg Young
   * You cannot create the first model right and making a change in model that does not work is hard (and error prone). So if you could rewrite the module from scratch quickly, you can have a better model and solve problem more easily.
   * Microservices, Actors, SOA, Objects,... are all the same concept. Read Alan Key who said about "small computers exchanging messages".
   * Small programs are not a new concept, see Linux - you can rewrite ls, grep, cp and others in a week or two.
   * Reading big, interconnected codebases takes weeks, months, or years. Hence it takes a lot of time for a new person to start contributing.
   * SOA in Dutch means what STD means in English.

Design Patterns
* Design patterns Stories http://www.programcreek.com/java-design-patterns-in-stories/
* Design patterns in real life http://www.codeproject.com/Articles/29036/Patterns-in-Real-Life
* Examples of design patterns http://stackoverflow.com/questions/1673841/examples-of-gof-design-patterns
 
* The Architecture of Open Source Applications http://aosabook.org/en/index.html
  * ZeroMQ http://aosabook.org/en/zeromq.html

* Designing and Deploying Internet-Scale Services https://www.usenix.org/legacy/events/lisa07/tech/full_papers/hamilton/hamilton_html/ (James Hamilton)

Algorithms & Data Structures
============================
* Top 10 Algorithms for Coding Interview  http://www.programcreek.com/2012/11/top-10-algorithms-for-coding-interview/
* Data Structures and Algorithms in Linux kernel http://cstheory.stackexchange.com/questions/19759/core-algorithms-deployed/19773#19773
* Ropes: an Alternative to Strings http://www.cs.rit.edu/usr/local/pub/jeh/courses/QUARTERS/FP/Labs/CedarRope/rope-paper.pdf
* Data Structures and Algorithms for Data-Parallel
Computing in a Managed Runtime http://axel22.github.io/resources/docs/my_thesis.pdf
* A Persistent Union-Find Data Structure http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.79.8494&rep=rep1&type=pdf

Learn you more Java
===================
* http://www.programcreek.com/java-tutorials/

Machine Learning
================
* A Few Useful Things to Know about Machine Learning http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf
