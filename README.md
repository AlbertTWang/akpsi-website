Walkthrough Link: 
1) Magic methods are: __str__  in models.py & __repr__ in blog_getter.py
2) First party packages used are: import os in settings.py & blog_getter.py & import random in views.py
3) Third party packages used are: Django & Selenium & Requests

Project details:

My final project is creating a website for Alpha Kappa Psi, a business fraternity that I recently crossed. I’m the Webmaster for the fraternity and while we currently have a website being upennakpsi.com, the website is outdated, has numerous small mistakes, and uses SquareSpace. The reason this was my idea was because I loved using Django for HW5 and I never got the chance to do HW4 so I wanted to essentially combine HW4 with the AKPsi website. Additionally, I know this is something that I’ll keep working on even after I submit. There’s actually numerous things I didn’t implement for the sake of time so I can study for my other finals. The biggest one being implementing User Profiles that show each Brother. When I have the time I’ll definitely implement that.

Installation Instructions:

The actual Django is similar to HW5 in terms of installation. I’ve attached a requirements.txt.

NOTE: I have a blog_getter.py file which extracts Instagram images from the AKPsi UPenn Instagram. I do this so I can get pictures easily and make blog posts out of this. The code won’t run unless ran itself through Terminal. I used Selenium which requires a ChromeDriver installation. I used Chrome Version 90. It’s likely you use a different version so you’ll have to install the ChromeDriver corresponding to that version. The code, blog_getter.py, which is in /media/images also has an absolute path for the ChromeDriver which only works on my computer. To make the code work, you’ll have to find the path to your ChromeDriver and change the path of that code. Again, this code only runs if you run it yourself through Terminal, and only I would do that as the admin of the page to extract the images from the AKPsi Instagram.

Note: I imported RichTextField but didn’t implement it yet.

Code Structure:

The code is formatted similarly to HW5 with views.py, models.py, and urls.py having the bulk of the python code. An addition is that blog_getter.py also has a lot of code. The HTML templates are in the templates folder. An important template is the base.html where every other template extends this template and it has the navigation bar and much more. I also have a media folder that stores all my images.

One thing to note is that I could have potentially made a class in Models.py modeling each Pledge Class instead of hard-coding each one, and I might do that in the future.
