Tinder API

In this particular project we will do some fun tasks in Tinder.
We all know about Tinder i.e. worldwide famous as a social, online dating application, which geographically shows the person in it where a person can swipe as like or dislike to anyone’s profile, if any person swipes as like to a particular person’s profile and that same person also swipe as like then it’s a match which means they can share messages between them and may organize a date .

So, now we are ready to head towards our aim which was by using Tinder API we have to get all users nearby, right swipe every fourth user and display all the matches.
To proceed further firstly we have to know about the API which we are going to use i.e.  “pynder” and the second thing which we are going to use i.e. “selenium”  .

•	Step-1  We must have to install our packages by giving this command on CMD:
                pip install pynder
               pip install selenium
So from now our programming part is going to be started.

Now after getting the packages we will create a virtual environment in python inside which we will do our programming part. To create a virtual environment we have to give this command :

           #python -m venv demo_env
           demo_env\Scripts\activate.bat
•	Step-2       
We have to download a webdriver called chromium via this link:
https://chromedriver.chromium.org
After downloading the package we need extract it and set in a suitable path inside C drive. After setting the path just give this command in CMD to activate the driver.
 
            #chromedriver
Now we will start our programming phase.
              #code.py

After writing the above code we have to make another file which contains login credentials.
              #secrets.py

When we execute the above the code we get:


Now we are completely signed in our tinder account and we can see that the swiping is start.


As we can see that we have swiped the users but we don’t have any matches yet so our program will show:
                          *Empty

So that’s all for now. That was some important aspects to use Tinder API  with the process of Automation GUI.
