### Map Reduce

[_MapReduce_](https://hacks.mozilla.org/2015/01/from-mapreduce-to-javascript-functional-programming/) is one of the common idioms in modern programming languages, usually associated with functional programming techniques.  In [_Functional Programming_](https://en.wikipedia.org/wiki/Functional_programming), functions may be assigned to variables, and functions (anonymous or not) may be passed as arguments to other functions.

The _MapReduce_ idiom usually includes the _Map_, _Filter_, and _Reduce_ functions. While it is possible to write such data transforms using imperative code, functional or declarative code may be easier to read and reason 
about, and usually uses immutable arrays and is optimized for execution speed.

A few simple examples of _MapReduce_ are given in the directories.

javascript
+ imperative.js shows imperative programming examples of map, filter, and reduce functions.
+ functional.js shows functional programming using map, filter, and reduce functions.  It has
 fewer variable declarations, and is easier to read and understand.

python
+ imperative.py shows imperative programming examples of map, filter, and reduce methods.
+ functional.py show functional programming examples of map, filter, and reduce methods.  Lambdas are helpful when writing functional python code.

ruby
+ imperative.rb shows imperative programming examples of map, filter, and reduce methods.
+ functional.rb show functional programming examples of map, filter, and reduce methods.  Lambdas and blocks are helpful when writing functional ruby code.

#### Programming Style
None of these scripting languages are purely functional, but they have functional elements.  One can take advantage of functional elements in them to write better, more organized code.  
+ JavaScript has objects and prototypes (objects inherit from other objects).  It can also be written in either a functional or imperative style.
+ Python is an OO language with classes and objects.  It can be written in either a functional or imperative style.  List comprehensions and generators may help.
+ Ruby is an OO language with classes and objects.  It can be written in either a functional or imperative style.


#### Elements of MapReduce
The basic elements of _MapReduce_ methods are:
+ map : array input, transformed array output
+ filter : array input, array output, boolean test
+ reduce : array input, single object output

#### Questions
+ Which _MapReduce_ elements are used in builtin _Array_ or _Hash_ / _Dict_ methods?
