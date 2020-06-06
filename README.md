# 30DaysOfKotlin
On this repository I will be updating all the stuff that I do every day related to Kotlin for the 30DaysofKotlin Challenge proposed by Google Dev India

# Day 1:
Today was my first day. I learnt how to work with the Kotlin REPL (Read-Eval-Print Loop) interactive shell, and I practiced using the basic syntax of Kotlin code.<br>
Also learnt about the data types and *VAR* and *VAL* and their limitations and use. Very excited for the next 29 days and going to learn and use time efficiently during this Pandemic.

# Day 2:
I started today with conditional statements and Booleans. If else was the first one. Then I went to _"when"_ statement which was like the _"Switch"_ statement in other languages. Next I learnt about nullable versus non-nullable variables. Also first time I used Double-bang operator (!!).<br>
Lastly it was all about arrays, lists and loops. New points here for me were 1) Loopong through the elements and the indexes at the same time 2) Stepping backward using downTo in a loop 3) Repeat Loops.

# Day 3:
Today was a long day of playing with functions. Starting from main() and moving to much complicated one's like passing an arguement or parameter in a function or passing a function in a function. Learnt how to make functions compact and how to create a filter of both eager and lazy types. Used _Sequence()_ and _asSequence_() for the same. <br>
Used the map() function which helps to perform a simple transformation on each element in the sequence. Lastly it was all about lambdas and higher order functions (a function that takes two arguments).

# Day 4:
Today I started with the classes. Studying all the parameters of classes deeply, moved onto class constructers, INIT, secondary constructors, property getter and setter. Next it was the visibility modifiers i.e Public, Protected, Private and Internal. Ended the day with subclasses and and inheritance. Lastly it was the use of override property in many examples.

# Day 5:
Function part-2 was completed today. Starting from abstract classes and its subclasses and Interfaces, moved on to interface delegation to add functionality to a class. Made it more complicated with two classes and two interfaces with delegation. Next I created a data class which is similar to struct in other languages.<br> Used destructuring and lastly it was Singleton class, creating an enum and ended with an example of Sealed class. This finally made me finish Functions today.

# Day 6:
Today I learned about collections, constants, and got a taste of the power of extension functions and properties. Started with Pairs and triples and many useful functions for List, such as reversed(), contains(), and subList(). Used Hashmap() to map the keys to values and got to know compile-time constants using the _const_ keyword. Also got to know about companion keyword and lastly ending with Extension functions and properties.

# Day 7: 
Today I focused on Generics in Kotlin. Learned to create generic classes to make code more flexible, adding generic constraints to limit the types used with generics. Used *in* and *out* to restrict types being passed into or returned from classes. Went through Generic functions and methods ending with generic extension functions and Reified types to run the generics into run time instead of compile time.

# Day 8:
Today I learnt to use annotations to specify things to the compiler and labeled breaks to let the code exit from inside nested loops. Laerned more about lambdas and higher order functions again. Also used _inline_ function very much. Got a little bit familiar with this new method SAM, Single Abstract Method, a common pattern, which was made simpler with lambdas. It was an end of all the basic stuff of Kotlin. 

# Day 9: 
Switched to Android Studio today. Learnt about all the files in an empty app and what all it means. Downloaded a virtual device too and set it up. Didn't do too much today and also ran Hello World successfully.

# Day 10: 
Made a rolling dice app in which whenever clicked on "Roll", it changed the the dice number randomly. Spent almost 3 hours on some very lame errors which defintiely helped me to understand how each file and each code is running altogether. I changed stuff mostly in AndroidManifest.xml, activity_main.xml, MainActivity.kt and strings.xml. Enjoyed today alot and realized that I have a long way to go in Kotlin :)

# Day 11:
Improved the rolling dice app today. Used the images instead of printing only the numbers. Also Learnt about API levels, its compatibility and _lateinit()_ keyword too. Next I also learnt how to change the launcher icon in Android Studio. 

# Day 12:
Worked with Linear Layout and learnt how to add a button. Linear layout is a layout that arranges other views either horizontally in a single column or vertically in a single row. Now I'll go a little slow for a while because of my semester exams starting from today.

# Day 13:
Today I studied about constraint layout for building flexible and efficient layouts and data binding library that allows us to bind UI components in our layouts to data sources in our app using a declarative format rather than programmatically.

# Day 14:
Went through fragment tag which is used to edit the app's UI and also Safe Args plugin, NavDirection classes, intent action for sharing, back and up button and lastly the navigation drawer. All I got to know is that more I'll practice these methods, more easy it'll be for me to understand.

# Day 15:
Activity lifecycle was the main topic for me today. It is a set of states through which an activity migrates. Other thing I learnt today was use of Timber logging and got to know how it is better than the normal log.

# Day 16:
Learnt more about the lifecycle library in depth and created a lifecycle-aware class. Got the overview about the Android Debug Bridge (adb), a command-line tool that lets us send instructions to emulators and devices attached to your computer. 

# Day 17-18:
Implemented the factory method design pattern, which is a creational pattern. Used ViewModelFactory Interface, also ViewModelProvider.Factory is an interface we can use to create a ViewModel object. Also resolved "Guess The Word" app's lifecycle issue using onSaveInstanceState() callback.

# Day 19-20: 
Worked on LiveData, an observable data holder class that is lifecycle-aware, one of the Android Architecture Components. Learnt to add it by changing the type of the data variables in ViewModel to LiveData or MutableLiveData, encapsulated it by using private MutableLiveData inside the ViewModel and return a LiveData backing property outside the ViewModel, and also got to know about Observable LiveData using the observe() method.

# Day 21-22:
Today I went through ViewModel data binding, adding LiveData to it, and String format for Data binding. This will be the last day of my learning from codelabs as from tomorrow I'll move on to making some project. 

First Google Codelab was pretty good but gotta need to work on the 2nd Codelab.

# Day 23-30: 
Made a Calculator app using Kotlin and Android Studio.
https://github.com/IIshaan/MyCalC 

Some of the concepts I used in it are -

Fragment OnCreate()
String Templates
Named Parameters
Inheritance

End of my journey of Kotlin!!

fun funfun() {
  fun haveFun() {
      fun haveMoreFun() {
          haveFun()
      }
      haveMoreFun()
  }
 }
fun funfun()
