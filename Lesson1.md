## JDK 8 Lambdas and Streams MOOC: Lesson 1 Homework

All the homework for this MOOC will consist of small exercises that you will complete using the things you have learned in during the lesson.

For lesson 1 we will focus on using Lambda expressions, method references and some of the new methods that have been added to existing classes.

There is a template source file that you should use to create the answers to the exercises called Lesson1.java. To simplify things the lists and maps you need for the exercises have already been created. You just need to focus on the code to solve the exercise.

There are five exercises for this week’s homework:

- **Exercise 1**: Create a string that consists of the first letter of each word in the list of Strings provided. HINT: Use a StringBuilder to construct the result.
- **Exercise 2**: Remove the words that have odd length s from the list. HINT: Use one of the new methods from JDK 8.
- **Exercise 3:** Replace every word in the list with its upper case equivalent. HINT: Again, use one of the new methods from JDK 8.
- **Exercise 4:** Convert every key-value pair of the map into a string and append them all into a single string, in iteration order. HINT: Again, use a StringBuilder to construct the result String. Use one of the new JDK 8 methods for Map.
- **Exercise 5:** Create a new Thread that prints the numbers from the list. HINT: This is a straightforward Lambda expression.

The key part of this homework is to use the new features of JDK 8 in the form of Lambda expressions and changes to existing APIs. Although parts of this you could easily do with loops that is not the goal. You should be able to complete all the exercises without resorting to a for or while loop. When you develop your Lambda expressions have a look at them and see if they can be replaced with an equivalent method reference.