# Discord-Tool
A automatic server leaver and unfriender for discord (might need to relocate the pointer x and y coordinates).


# Since you might need to relocate the pointer I'll show you a quick How-To

# **Step One**

First off you need to download [Python](https://www.python.org/downloads/), a detailed tutorial on how to do that can be found [here.](https://www.youtube.com/watch?v=YKSpANU8jPE)
If you've done that or already have pyhton installed on your machine zou can head over to your cmd using WIN + R and then just type in "cmd" and hit **OK**. 

![grafik](https://user-images.githubusercontent.com/81767182/192834873-6b3ba8de-7e14-4c9e-9e56-f1ec44f0dc32.png)

and then type:
```pip install pyautogui```


# **Step Two**

After youve done that, you need to just enter
> python

in the console. After that type 
> import pyautogui

and hit enter.

It should look something like this:
![grafik](https://user-images.githubusercontent.com/81767182/192850299-ad9c6ee8-6b6f-4a41-b725-60a7a04d1a43.png)


# **Step Three | Set up Pointer Locations for servers**

**1st:** Type 
> pyautogui.position()

into the console but dont hit enter yet, head over to discord and hover your mouse over the top server like this:

![grafik](https://user-images.githubusercontent.com/81767182/192850864-60120e8c-7129-4d3d-a1c7-ed451640f248.png)

Now hit enter on your keyboard and the console should give you an output similiar to this (ignore if the numbers dont match up):

![grafik](https://user-images.githubusercontent.com/81767182/192851119-059a6322-4e35-439f-a6e0-0021c9ff4f27.png)

Now next up do the same procedure but hover over the 'Leave Server', this time:

![grafik](https://user-images.githubusercontent.com/81767182/192851331-7650e0b5-a11b-436d-aae7-87666f1823bd.png)

And last but not least do the same but hover over the 'Leave server' at the confirmation screen:

![grafik](https://user-images.githubusercontent.com/81767182/192851461-2ec96df5-447e-4105-bd36-b34d7b86e15f.png)



**2nd:**

After you've followed all the steps your console should look like this:

![grafik](https://user-images.githubusercontent.com/81767182/192852062-4ede467a-d960-4359-bea4-4e4d2d635010.png)

Next up head over to the code and just change the x and y coordinates chronoligically in the "serverleaver.py" file.


# **Step Three | Set up Pointer Location for unfriending**

Type 
> pyautogui.position()

into the console but dont hit enter yet, head over to discord and hover your mouse over the first friends three dots like this (excuse my screenshotting skills):

![grafik](https://user-images.githubusercontent.com/81767182/192853464-4a44c309-7078-4aea-9322-87a0ce9e69d2.png)
 
Now hit enter on your keyboard and the console should give you an output similiar to this (ignore if the numbers dont match up):

![grafik](https://user-images.githubusercontent.com/81767182/192853681-66167988-373d-47e1-9429-6096fd1e3e88.png)

Next up do the same thing as above but hover over "Remove Friend" button:

![grafik](https://user-images.githubusercontent.com/81767182/192853904-a0db7b3f-b2df-493a-a610-3df7bff82e71.png)

And at last do the same but hover over "Remove Friend" on the confirmation screen:

![grafik](https://user-images.githubusercontent.com/81767182/192854108-be00ba3b-f2d3-43a9-84db-a129da9d94a5.png)

After you've followed all the steps your console should look like this:

![grafik](https://user-images.githubusercontent.com/81767182/192852062-4ede467a-d960-4359-bea4-4e4d2d635010.png)

Next up head over to the code and just change the x and y coordinates chronoligically in the "unfriender.py" file.


# **Step Four**

Enjoy! This little program saves you alot of time and you can just afk it.


