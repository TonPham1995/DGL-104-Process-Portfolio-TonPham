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

### Activity 0301:
When using youtube I find it has some differences between the app and its web version, I tested it on Android OS 

<img src="images/screenshot_1.jpg" width=400> <img src="images/screenshot_2.jpg" width=400>

As you can see, on the top bar, in the web version there is no button to connect to the TV and a notification button. Right below, we see a clear difference, while on the web version we see some search suggestion, and on the app side we see two buttons, the Original, which is used to access some videos recomended by youtube, and Music app is used to switch to another music player app of youtube. There is not much difference when both sides show random videos with topics according to what we often watch and Top news. In the lower part of both sides have a navigation bar, but their items are different. The application has an additional button used to upload videos. The next difference is that the web version has a trending button while the app side is explore, but strangely when I click on them they have the same function, after researching they are used to watch the videos that are on the top trending, which are videos that have had a high number of views for a short period of time. Next, when I scroll down in the web version, then stop, this navigation bar tends to disappear, and reappears when I continue to scroll down. This behavior does not appear in their application. There is not much difference when watching a video on both platforms, except for the comment section, while the comment on the web version appears at the end, in the application version it is in the middle. 

<img src="images/screenshot_3.jpg" width=400> <img src="images/screenshot_4.jpg" width=400>

### Activity 0302:

### Activity 0303:

I will use assignment 1 for this activity, and after looking back, I think my code is quite DRY. I think in order to be able to write DRY code, you have to understand what the problem you want to solve, and you have to know the logic behind it, and it must also be readability. 













