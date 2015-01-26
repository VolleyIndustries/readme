#Testing & Performance Goals
![](http://media.giphy.com/media/ZLxIrGuuXSJr2/giphy.gif)

Testing is an important part of any development process and one we take seriously. This is because performance has a massive impact on user experience. People notice when you take care in making an animation run at 60 fps or align everything to a grid, even if they can't describe it.

Here's how we aim to always test all our code for the purposes of giving every user a delightful experience:

##Our Goals

#### 1500ms to Glass
Have the page displayed on screen in 1500ms or less using a simulated 3G connection. Connections speed will be simulated using Apple's Network Link Conditioner

#### 30 Frames Per Second 
Maintain an average frame rate of 30 FPS in a modern desktop browser

#### PageSpeed Insights Score above 80
Using Google PageSpeed Insights achieve a goal of 80 or above

##Ask "What if"...

####Server
- A client passes a mismatched variable type?
- There is no token passed in the header (visitor)?
- The person is not an admin/not a user?
- Someone abuses this endpoint?
- The client needs a descriptive error message?
- Steve Jobs was using this endpoint?
- The client passes a huge file / lots of records?
- The client has many many relationships?
- The client is a phone or on a very slow mobile network?

####Client
- The user is on firefox, chrome or safari?
- The users window is smaller than 768x768?
- The user is on an iPhone 5?
- The user is on mobile safari?
- The user is on mobile chrome?
- This is the first website the user has ever seen?
- The user makes a mistake filling out a form?
- The user clicks every button?
- The user inspects your code?
- The user is on a phone or on a very slow mobile network
- Steve Jobs inspects your code?

####Inspiring Links
* [JankFree](http://jankfree.org/)
* [Google Pagespeed Guidelines](http://www.feedthebot.com/pagespeed/)
* [14 Rules for Faster-Loading Web Sites](http://stevesouders.com/hpws/rules.php)
