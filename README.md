# quiz-4-corrections

Multiple Choice Corrections

3. There is no difference in the ways the methods are translated to output because the first usage provides the string to be printed within the double quotes of the method call. The second usage creates a new message string to pass into the method, which still properly prints it. And the third usage creates a new 'something' string which is then passed into the method.

4. The public access modifier is visible within all classes and packages. The private modifier is only visible within the class it is defined in. The default modifier is visible within it's defined class and classes within the same package. The protected modifier is only visible within it's defined class and it's subclasses and by classes inside of the same package.

5. int i = 0; | int length = str.length(); | while (i < length) { | System.out.println(str.charAt(i)); } is also able to be used to print out each character within a string because it uses a while loop condition which is true up until the end of the string. While there is no set iteration, the while loop accomplishes that using the index of each character and the length of the string.

6. The Math.ceil() function would accepts a single parameter that will return the same if a whole number or be rounded up to the next whole number if it is a decimal. While Math.round() would round up, it would only do so if the decimal place was .5 or greater.

7. When writing a method, you must always include a visibility indicator, an access modifier, and the method name (in that order). Together, this is known as the method's signature. This would look something like public void getCars.

13. These lines of code would return "cdefg" and "ef" after running the code because the first modification would remove all the letters before 'c' to only have c and the letters following it since it has no "stop" indicator in the substring method. The second modification would cut the string before g and after, but also including, 'e'. 

15. The error with the code at hand is that the limits that are checked don't account for any number of seends less than or equal to 500. The code checks if seeds is greater than 1000, or if it's greater than 500-- nothing less than those limits.
