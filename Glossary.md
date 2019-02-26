## CI346 Glossary (maintained by UoB students)

### Programming Languages


**Programming Paradigm** - A way to classify programming languages based on their features ([Source](https://en.wikipedia.org/wiki/Programming_paradigm/)). In other words, the style or “way,” of programming.
Note: We don't use the phrase “programming language paradigm.” A paradigm is a way of doing something (like programming), we rather talk about particular paradigms such as: "Object-oriented Paradigm" and "Functional Paradigm" [Source](http://cs.lmu.edu/~ray/notes/paradigms/)


**Object-oriented Paradigm** - [Programming] based on the concept of "objects", which may contain data, in the form of fields, often known as attributes; and code, in the form of procedures, often known as methods.
[Source](https://en.wikipedia.org/wiki/Object-oriented_programming)
__Example:__
```
 class Greeting {
  	void greet(Named target) {
			System.out.println("Hello, " + target.getName() + "!");
  	}
 }

 interface Named {
  	String getName();
 }

 class World implements Named {
  	String getName() {
			return "World";
  	}
 }

 class Main {
  	public static void main( String[] args ) {
			Greeting greeting = new Greeting();
			greeting.greet(new World());
  	}
 }
// [Source](http://wiki.c2.com/?HelloWorldInManyProgrammingLanguages/)
```


**Functional Paradigm** - "Programming with function calls that avoid any global state." [Source](http://cs.lmu.edu/~ray/notes/paradigms/)
__Example:__ - TODO


### Concurrency

**Process** - TODO


**Thread** - A thread is a thread of execution in a program.
The Java Virtual Machine allows an application to have multiple threads of execution running concurrently.

[Source](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/lang/Thread.html)

```
Thread t = new Thread(() -> {
    // some code to run on new thread
});
t.start();
```



### Client-server Computing

**TCP** - TODO

**UDP** - TODO
