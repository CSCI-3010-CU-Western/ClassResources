CSCI 3010: Programming Project Workshop: Object-Oriented Programming
=====================
See the [Canvas website](https://canvas.colorado.edu/courses/99583) for the syllabus, assignments, and in-class activities materials.  

c++ Tutorials and references
--------------------
For your review or as a reference on new course topics, these are recommended references:

[learn cpp tutorial](https://www.learncpp.com/)

[ThinkC++ by Allen B. Downey](https://www.greenteapress.com/thinkcpp/thinkCScpp.pdf)

Compiling and Makefiles
--------------------

[__c++ compilation process__](http://faculty.cs.niu.edu/~mcmahon/CS241/Notes/build.html) -- What are the steps to converting c++ file(s) to an executable file? This is a quick run down of all the steps involved.

[  youtube overview of c++ compilation process  ](https://www.youtube.com/watch?v=ksJ9bdSX5Yo&ab_channel=MikeShah)

[__example Makefile__](examples/Makefile)

[__verbose guide to writing Makefiles__](https://www.cs.swarthmore.edu/~newhall/unixhelp/howto_makefiles.html)

Pointers vs. References
----------------

[__wikipedia on pointers (general)__](https://en.wikipedia.org/wiki/Pointer_(computer_programming))

[__wikipedia on c++ references__](https://en.wikipedia.org/wiki/Reference_(C%2B%2B))

[__passing arguments by reference vs. pointer__](https://www.geeksforgeeks.org/when-do-we-pass-arguments-by-reference-or-pointer/)

Structs and Objects
-----------------

[__structs and objects syntax__](examples/structs_objs_declarations.md)

Terminal & bash
---------------------
[__what is terminal?__](https://askubuntu.com/questions/38162/what-is-a-terminal-and-how-do-i-open-and-use-it)

[__bash commands reference__](https://courses.cs.washington.edu/courses/cse390a/14au/bash.html)

[__bash guide focusing more on scripting__](https://guide.bash.academy/)

[__installing Windows Subsystem for Linux__](examples/WSL/instructions.md)

Enums
-----

[__enums__](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md#S-enum)

[__enum class vs. enum (stack overflow)__](https://stackoverflow.com/questions/18335861/why-is-enum-class-preferred-over-plain-enum)

C++ Errors
-------

[__compiler, linker, run-time errors__](https://www.cs.bu.edu/teaching/cpp/debugging/errors/)


Version control & git
----------------
[__CVS vs. DVCS__](https://www.atlassian.com/blog/software-teams/version-control-centralized-dvcs)

[__pros and cons of CVS and DCVS__](https://content.intland.com/blog/sdlc/the-needs-that-version-control-systems-serve)

[__git cheat sheet__](https://www.atlassian.com/dam/jcr:8132028b-024f-4b6b-953e-e68fcce0c5fa/atlassian-git-cheatsheet.pdf)

[__hello world for github__](https://guides.github.com/activities/hello-world/)

[__about pull requests__](https://help.github.com/articles/about-pull-requests/)

[__resolving merge conflicts__](https://help.github.com/articles/resolving-a-merge-conflict-using-the-command-line/)


Design Patterns (game programming blog)
------------
[__Singleton__](http://gameprogrammingpatterns.com/singleton.html)

[__Flyweight__](http://gameprogrammingpatterns.com/flyweight.html)

__Factory (without inheritance)__ -- look at notes in `design_patterns.md` after we go over them in class.

[__Factory (example with inheritance)__](https://sourcemaking.com/design_patterns/factory_method/cpp/1)  

[__Prototype__](http://gameprogrammingpatterns.com/prototype.html)

[__Iterator (using)__](https://www.cprogramming.com/tutorial/stl/iterators.html)  

[__Iterator (how to implement)__](https://stackoverflow.com/questions/8054273/how-to-implement-an-stl-style-iterator-and-avoid-common-pitfalls)


Design Patterns & `static`
-----------
[__`static` wikipedia__](https://en.wikipedia.org/wiki/Static_(keyword))  

[  static member variables: overview & best practices  ](https://www.learncpp.com/cpp-tutorial/static-member-variables/)

__Singleton Example__ -- Can be found in lecture 11 (Earth examples)


Continuous Integration
-----------
[Github Actions - workflow file](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions#understanding-the-workflow-file)

[__Travis/CI core concepts__](https://docs.travis-ci.com/user/for-beginners/)

For an example `.travis.yml` file, see the [demo repo in the course organization](https://github.com/CSCI-3010-CUBoulder/CSCI3010-demo-Lec6/blob/master/.travis.yml). 

[__Travis embedding status icons__](https://docs.travis-ci.com/user/status-images/)


Unit Testing
-----------
[__Catch2 tutorial__](https://github.com/catchorg/Catch2/blob/master/docs/tutorial.md#top)

[__Catch2 Assertion Macros__](https://github.com/catchorg/Catch2/blob/master/docs/assertions.md#top)


Overloading Operators
-----------
[  friend functions for overloading operators  ](https://www.learncpp.com/cpp-tutorial/overloading-operators-using-member-functions/)

[  See code examples here  ](https://github.com/CSCI-3010-CU-Western/ClassResources/blob/main/overloading_overriding_const_constructors_enums.md)


Inheritance
----------
[__inheritance in c++ (lectures from Univ. of Washington)__](https://courses.cs.washington.edu/courses/cse333/18su/lectures/18-c++-inheritance.pdf)  

[__part 2 inheritance from UW__](https://courses.cs.washington.edu/courses/cse333/18su/lectures/19-c++-casts.pdf) 

Templating
--------

[__Templating wikipedia__](https://en.wikipedia.org/wiki/Template_(C%2B%2B))  

[__stack overflow about why templated functions/classes' implementations go in header files__](https://stackoverflow.com/questions/1724036/splitting-templated-c-classes-into-hpp-cpp-files-is-it-possible)



To make changes:
---------------
1. Clone this repository (`git clone https://github.com/CSCI-3010-CUBoulder/ClassResources.git`)
2. Do a `git pull` when your repository has gone stale (there are changes/resources here that you do not have locally).
3. We recommend not editing the files in this repository, but if you do, you may want to make a copy of the file to avoid any merge conflicts later if we add to/update the document!

Acknowledgements: 
--------------
Thanks to Sreesha Nath for compiling and sharing these resources
