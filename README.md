# DGL-104-Process-Portfolio
## By Ton Pham

### Activity 0101:  Adapted from The Pragmatic Programmer
I was given an exercise that test an user input year is a leap year or not. So I have
```java
  boolean x = (year % 4) == 0;
  boolean y = (year % 100) != 0;
  boolean z = ((year % 100 == 0) && (year % 400 == 0));
```
But I don't know how to combine them into one true condition to include in if else statement. I tried each way like splitting them into several if else statements, however they need combination, not split. The only way and arguably the best is to combine them into a single line of code that is 
```java 
(x && (y || z)) 
```

### Activity 0102:  
Readability is an issue that almost all teachers talk about, and they give me a lot of advice on that, so with a relatively short exercise like above, I reviewed it and didn't see much. However, in general, naming things is still a relatively difficult issue for me, because English is my second language, sometimes naming an element is a bit difficult, in particular on a above problem, White space and indentation is a minor omission
```java 
Scanner in = new Scanner(System.in);
System.out.print("Please input the year: ");
int year = in.nextInt();
```
I'd better leave a space between line 1 and line 2, because they are two different parts.

### Activity 0301
When using youtube I find it has some differences between the app and its web version, I tested it on Android OS 

![](images/screenshot_1)
![](images/screenshot_2)

