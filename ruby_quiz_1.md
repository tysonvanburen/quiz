1. What is the difference between a local variable, and an instance variable?
The difference is with their scoping. A local variable is only visible with in the method its defined. An instance variable is visible anywhere else

2. What is the datatype of `"DevPoint Labs"`?
String

3. Assign the number `10` to the local variable `n`.
n = 10

4. Assign your name to the local variable `name`.
name = "Tyson"

5. What is an Array?
Displays a list of things. [tyson, dog, ice]

6. Give an example of when you’d use an Array.
When using .each do ||

7. What is a method?
method is a subprogram that acts on data and often returns a value

8. Name 3 iterator methods for an Array.
new_array = [1, 2, 3, 4]
1 array.first
2 array.each
3 array.last

9. Name 3 methods for a String.
.reverse .upcase .downcase

10. What datatype does `5 / 2` return?
fixnum

11. What is a Hash?
Displays a list of keys and values.

12. Give an example of when you’d use a Hash.
If you wanted to assign values to a subjects attributes. example: dog = {age: 5, name: lucy}

13. What is a class?
A class is a specification of how we want our code to run. Its like blueprints of what we want to run.

14. True or False; A class is a constant.
True

15. `true` and `false` are called what?
Booleans

16. Write 4 conditional operators.
if, unless, else, elsif < > <= !=

17. Create a method called bucket that returns an empty array.
def bucket
  []
end


18. Name 6 ruby special keywords. (a keyword is a word that already has a special meaning)
class, case, do, else, end, false, true, module

19. How would you convert a number into a string?
5.to_s

20. How would you convert a string into a number?.
"5".to_i

21. What is class inheritance?
When a class inherits from another class. class People < John


22. What are modules used for?
Modules define a namespace, a sandbox in which your methods and constants can play without having to worry about being stepped on by other methods and constants.



23. What is a gem?
A package manager for the Ruby programming language that provides a standard format for distributing Ruby programs and libraries.

24. Name 4 gems, and their purposes.
1. aarr: helps track user lifecycle metrics via MongoDB. It also provides cohort and reporting tools.
2. m9t: Classes for handling basic measurement units: distance, direction, speed, temperature and pressure.
3. habits: A habit tracker. Tracks habits in weekly cycles.Each habit has a day or days associated with it.Habits expects activity on the habit on those days. If no activity is registered, habit goes first into yellow zone (e.g. 20 hours before deadline) and then into red zone (e.g. 6 hours). And finally into missed state.Transfer into each state can be used to trigger commands.
4. jabber-bot: Easily creates simple regex powered Jabber bots.
25. What are comments used for in programming?
To help me remember what that specific code was for. And what I was doing with it.
To set up a game plan for how I am going to write my code.

26. In Ruby, only 2 things evaluate to `false`. What are they?
false, nil

27. Write 2 comparison operators.
< <=

28. Write the code for “ if dave’s age is greater than or equal to 21”
daves_age = 22
if daves_age >= 21

29. Instantiate a `Car` class.
old_n_busted = Car.new

new_car = Car.new("Toyota", 2014)

30. What is a method chain?
"tyson".upcase.downcase.capitalize.reverse.reverse

31. How would you capitalize and reverse a string then print it out to the console?
name = "tyson".capitalize!.reverse!
puts name

32. What is a method to add an object to an array?
new_array = [1, 2, 3, 4]
new_array.push 5

33. How would you add an object to a hash?
demo["Graham"] = demo.fetch("Graham",0) + 1

34. What are 2 valid datatypes of keys for a hash?
strings, array

35. What is a writer method?
attr_writer. assignes a value to a attribute

36. What is a reader method?
attr_reader. returns a value to a attribute

37. There are 4 types of variables. What are they?
instance variable, local variable, global variable, class variable

38. What does the question mark at the end of a method in ruby mean?
true or false

39. What’s a common way to debug your code?
using Raise.

40. How would you return the string `"two"` from this array? `arr = ["one", "two", "three"]`
puts arr[1]

41. How would you return the string `"DevPoint"` from this hash? `hsh = {:name => "DevPoint"}`
puts hsh[:name]

42. What is the datatype for `:age`?
symbol

43. What is the datatype for `-36.98`?
float

44. What is the datatype for `[1, 2, 3]`?
array

45. What is the datatype for `"BOOM goes the dynamite"`?
string

46. What is the datatype for `123412`?
fixnum

47. What is the datatype for `{:food => "burger"}`?
hash

48. What is the datatype for `false`?
boolean

49. What is the purpose of `nil`?
nil

50. How would you print out the current date?
puts Time.now

51. How would you print out just the current year without using a Fixnum?
puts Time.now.year

52. What is String interpolation?
#{name}

53. What is String concatenation?
"tyson" + " van buren"

54. What does OOP stand for?
object oriented programming. lol I'm a little brain dead.

55. What does instantiation mean?
to create an instance of a class

56. What is the name of the method that is called every time an object is instantiated?
initialize

57. What are arguments?
def name(string)

58. How do you pass an argument?
by assigning an attribute to the argument then pass it at the end of the code

59. Write a method called `eat` that has an argument `food` with a default value of `"cheese"`.
def eat(food = "cheese")
  puts food
end

60. What is a loop?
A loop allows you to run a block of code until that code is no longer true or false

61. How long has ruby been around?
21

62. How are you doing on this quiz so far?
not so good

63. Is anyone else hungry?
starving

64. What are the pipe characters used for in a block?
new_array = [1, 2, 3, 4]
new_array.each do |i|
  new_array += i
end
it runs through each value individually and assigns something to it then puts it back together?

65. What is the difference between single quote strings and double quote strings?
double quoted strings can be used in string interpolation and single quoted strings cannot.
single quoted strings cannot use other quotes inside of the string and a double quoted sting can.

66. Name some rules for naming a method?
they cannot start with a number

67. How can you tell if a method is an instance or class method?
A method will return true or false. Class methods are used to reference the Class.

68. In an instance method, what is `self`?
Instance of the class

69. How do you add a dependency to a file?
require 'dependency'

70. I have a text file called `names.txt`. Each name is on it's own line. How would you print all the names in the file?
file=File.open("names.txt","r")
file.each_line do |line| puts line end

file.close

71. When a method defines an argument that has a asterisk in front of a variable name, what is that asterisk referred to? e.g. `def thing(*stuff)`
A splat

72. When a method defines an argument that has an ampersand in front of a variable name, what is that ampersand and variable name collectivly called? e.g. `def thing(&stuff)`
blocks? they don't require an argument?  

73. What is it called when you see the `do` and `end` keywords together?
Block

74. What does DRY stand for?
Don't Repeat yourself

75. What does DSL stand for?
Domain Specific Language

76. This question left blank intentionally.


77. What does MRI stand for?
Matz's Ruby Interpreter

78. What is the difference between JRuby and MRI?
JRuby is a high performance, stable, fully threaded Java implementation of the Ruby programming language.

79. What would you use RubyMotion for?
Creating ios apps and androide apps

80. Does your head hurt?
Si'
