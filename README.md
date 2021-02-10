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
I have read about Device Compatibility, a pretty cool topic that every designer must solve is Compatibility.

Android apps have to run on many different types of devices, so to optimize we have to work hard to find solutions by specifying your app's feature requirements and control which types of devices can install your app from Google Play Store. There are two types of compatibility: device compatibility and app compatibility. To achieve the largest user-base possible for your app, you can restrict your app's availability to devices through Google Play Store based on the following device characteristics: Device features, Platform version, Screen configuration. These three factors are used to control your app's availability to devices. Also, you can control your app's availability for business reasons.

This article explains Compatibility in great detail. First of all, the article explains in detail the word "compatibility". Then it lists ways to do this for various purposes and plans. On the left hand side there is a menu row where we can read other articles, and on the right hand side there is a list of each items in the article we are reading. This is a common layout for websites like this, I find this is often used by wiki, or any e-newspaper websites. 

### Activity 0303:
I will use assignment 1 for this activity, and after looking back, I think my code is quite DRY. I think in order to be able to write DRY code, you have to understand what the problem you want to solve, and you have to know the logic behind it, and it must also be readability. 

### Activity 0401:
<img src="images/Airbnb Pattern.png" width=400>

I chose the Airbnb pattern, and I think One-Handed Usage and Intelligence are two important factors that programmers must constantly use on this app. This is an app for travelers and businessman. It can be seen that the customers of this application are those who will definitely have to carry many things such as: luggages, documents, tools, etc, and it seems like always using two hands when using apps is very difficult for them. And as shown above in the map search of surrounding places, Airbnb did a relatively good job showing location information right below the screen, where the thumb can navigate easily. Secondly, It's a relatively versatile app that not only shows places to stay, but also shows nearby places to entertain or dining, I tried it out, when you choose a place to stay, and when I click in the map section, the application will self-understand to show places near it, it does not need you to enter the address. This is called Intelligence, the app collects information by itself and uses it to make the application more convenient.

### Activity 0402:
I think Split2 is more orthogonal - it only splits a line into fields. It allows the source of the lines to be changed without needing to alter the field splitting class and allows it to be used in other contexts. In MVC orthogonal segments are used to create segments that are perpendicular to each other.













