# 314 (or so) Awesome Raspberry Pi Resources

I had this ambitious idea on Pi Day to see if I could come up with 314 awesome <people, companies, projects, books, etc> for learning about and building with the Raspberry Pi. I mean, any search on Google turns up 314 *million* results, so surely I could come up with the best of the best right? :smirk:

I combed through my bookmarks, scoured links from old posts, and finally just started looking... everywhere. I discovered a lot of new people to follow, new material to read, and new projects to try out. I'll have no shortage of things to do and try out on the Pi now, and neither will you!

This was originally a blog post, but I figured it'd be more collaborative on here. If you have anything to add or correct, [let me know](contributions.md)! Also, if you'd like to work through a few easy projects, check out [my other repo](https://github.com/grantwinney/314-or-so-awesome-raspberry-pi-resources).

<img src="https://grantwinney.com/content/images/2018/03/raspberry-cake-276800.jpg" width=500>

## Table of Contents

*   [Getting Started](#getting-started)
*   [Operating Systems](#operating-systems)
*   [Scratch](#scratch)
*   [Python](#python)
    *   [Coding with the IDLE](#coding-with-the-idle)
    *   [Coding Online](#coding-online)
    *   [Coding with IDEs](#coding-with-ides)
        *   [Mocking GPIO Pins](#mocking-gpio-pins)
    *   [Python Tutorials](#python-tutorials)
    *   [Python MOOCs (free online classes)](#python-moocs-free-online-classes)
*   [Tutorials](#tutorials)
    *   [Beginner](#beginner)
    *   [Even More](#even-more)
    *   [YouTube](#youtube)
    *   [Other Languages](#other-languages)
        *   [C](#c)
        *   [C#, C++, Visual Basic (UWP Apps)](#c-c-visual-basic-uwp-apps)
        *   [C++](#c-1)
        *   [Go / GoLang](#go--golang)
        *   [Java](#java)
        *   [PHP](#php)
*   [Stores](#stores)
*   [Blogs / Magazines / Ezines](#blogs--magazines--ezines)
*   [Contests / Events](#contests--events)
*   [Software](#software)
*   [Hardware](#hardware)
    *   [Robotics](#robotics)
*   [Social Media](#social-media)
    *   [Twitter](#twitter)
    *   [Facebook](#facebook)
    *   [Pinterest](#pinterest)
*   [Educational Resources](#educational-resources)
*   [Electronics Fundamentals](#electronics-fundamentals)
*   [Reference Guides / Help](#reference-guides--help)
*   [Books](#books)
*   [Interfacing with Arduino](#interfacing-with-arduino)
*   [A List of Lists](#a-list-of-lists)
*   [Pi Day](#pi-day)
*   [What are your resources?](#what-are-your-resources)

## Getting Started

If you're brand new to the world of the Raspberry Pi, you might wonder what the heck it is and what you can do with it. Let's start at the start.

* [The Official Raspberry Pi Beginner's Book](https://www.raspberrypi.org/magpi/issues/beginners-1/) *- the Raspberry Pi Foundation*
* [What is a Raspberry Pi?](https://www.raspberrypi.org/help/what-%20is-a-raspberry-pi/) *- the Raspberry Pi Foundation*
* [What is a Raspberry Pi?](https://thepi.io/what-is-a-raspberry-pi/) *- The Pi*
* [What is a Raspberry Pi?](https://opensource.com/resources/raspberry-pi) *- OpenSource.com*
* [What is the Raspberry Pi 3? Everything you need to know...](http://www.zdnet.com/article/what-is-the-raspberry-pi-3-everything-you-need-to-know-about-the-tiny-low-cost-computer/) *- ZDNet*
* [Which Pi is Right for Your Project?](https://www.pubnub.com/blog/raspberry-pi-board-comparison-3-zero-1-2/) *- Jeremy Cook and Zach Wendt, PubNub*
* [9 Things You Wanted to Know About Raspberry Pi](https://www.makeuseof.com/tag/9-things-wanted-know-raspberry-pi/) *- Mihir Patkar, MakeUseOf*
* [5 easy steps to getting started using Raspberry Pi](https://www.imore.com/how-get-started-using-raspberry-pi) *- Lory Gil, iMore*
* [How to choose a Raspberry Pi starter kit](https://howchoo.com/g/zdg4zmy4yze/how-to-choose-a-raspberry-pi-starter-kit) *- Zach, howchoo*
* [Eben Upton - The Story of Raspberry Pi](https://www.youtube.com/watch?v=UCt6d0SCxO4) *- a talk about how the Pi came to be and its evolution*

There are quite a few models at this point, but the latest and greatest are:

* [Raspberry Pi Zero W](https://www.raspberrypi.org/products/raspberry-pi-zero-w/)
* [Raspberry Pi 3 Model B+](https://www.raspberrypi.org/products/raspberry-pi-3-model-b-plus/), *which was [just announced today](https://www.raspberrypi.org/blog/raspberry-pi-3-model-bplus-sale-now-35/)*

If you want to compare the various models, here are a couple charts:

* [Raspberry Pi Comparison Table @ ModMyPi](https://www.modmypi.com/blog/raspberry-pi-comparison-table)
* [RaspberryPI models comparison @ SocialCompare](http://socialcompare.com/en/comparison/raspberrypi-models-comparison)

Once you decide to make the investment, you'll need to figure out what to buy - and there is a _lot_ you can do with and buy for the Pi. I'd stick with the basics at first - get used to navigating around the Pi, and get familiar with GPIO pins, connecting LEDs, and using resistors.

You might consider buying a kit if your budget allows it. I've personally bought kits from Vilros and CanaKit and had no problems with either, but there are others too - check out the [stores](https://grantwinney.com/314-awesome-raspberry-pi-resources#stores) below. Kits generally provide everything you need to get up and running - the bare-bones Pi doesn't even come with an adapter! Or you could use the list in one of the product's descriptions and source each part separately.

* [Vilros Raspberry Pi Ultimate Project Kit](http://amzn.to/2tuzaYQ)
* [CanaKit Raspberry Pi 3 Ultimate Starter Kit - 32 GB Edition](http://amzn.to/2FBFouR)

## Operating Systems

You'll need to install an operating system before you can do anything else. If you purchase a kit, check the description - they might preinstall NOOBS on the SD card for you. NOOBS is a program that helps you install and switch between multiple OS's, and generally makes life easier when you're starting out.

* [Getting Started with NOOBS](https://www.raspberrypi.org/help/noobs-setup/2/) *- Raspberry Pi Foundation*
* [Beginner's Guide to NOOBS](https://www.raspberrypi.org/magpi/beginners-guide-noobs/) *- The MagPi*
* [How to install NOOBS on the Raspberry Pi](https://thepi.io/how-to-install-noobs-on-the-raspberry-pi/) *- The Pi*
* [How to Install Raspbian: A Simple Guide for Beginners](https://pimylifeup.com/how-to-install-raspbian/)
* [Installing Operating System Images](https://www.raspberrypi.org/documentation/installation/installing-images/), if you'd like to move beyond NOOBS and install an OS directly
* [Raspberry Pi Operating Systems](https://pimylifeup.com/category/projects/operating-systems/) *- installation guides at Pi My Life Up*

There are plenty of other operating systems available too, some of which have a specific purpose like streaming media, but starting out you'll probably want to stick with Raspbian.

* [Third party operating system images for Raspberry Pi](https://www.raspberrypi.org/downloads) *- Raspberry Pi Foundation*
* [Brief overview of available operating systems](https://www.lifehacker.com.au/2016/05/the-best-operating-systems-for-your-raspberry-pi-projects/) *- Thorin Klosowski, Lifehacker*
* [Create a Lightweight Raspberry Pi System with Raspbian Lite](http://thisdavej.com/create-a-lightweight-raspberry-pi-system-with-raspbian-lite/) *- Dave Johnson*
There's a Raspbian Lite OS that's similar to Raspbian, but without a GUI and about ¼ the size.

## Scratch

Raspbian comes with Scratch, a program developed at MIT that lets you drag-and-drop blocks representing different coding constructs, and then "run" them to see the effect on cartoon characters that move around the screen. It's a decent intro to programming concepts, without getting all bogged down in a particular language's syntax.

* [Scratch](https://scratch.mit.edu/about/)
* [Getting Started with Scratch](https://cdn.scratch.mit.edu/scratchr2/static/__20d52c9edc3c922510ac40dba7d51a08__//pdfs/help/Getting-Started-Guide-Scratch2.pdf) (pdf)
* [Learn to Code with Scratch](https://www.raspberrypi.org/magpi/issues/essentials-scratch-v1/) *- special issue of The MagPi*
* [Tutorials for Getting Started](https://scratch.mit.edu/tips)
* [Using Scratch 2.0 on the Raspberry Pi](https://projects.raspberrypi.org/en/projects/using-scratch2)

After you get comfortable with Scratch, here's some other stuff to check out:

* [CodeClubProjects](https://codeclubprojects.org/en-GB/scratch/) *- Dozens of projects for learning to use Scratch, from the Raspberry Pi Foundation*
* [Hardware That Can Connect to Scratch](https://en.scratch-wiki.info/wiki/Hardware_That_Can_Connect_to_Scratch)
* [Project Sharing](https://en.scratch-wiki.info/wiki/Project_Sharing) *- When you create a Scratch project, share it with the world!*
* [Scratch online](https://scratch.mit.edu/) *- You can also play with Scratch away from the Pi.*
* [Scratch Projects](https://scratch.mit.edu/explore/projects/all) *- official Scratch site*
* [Scratch Studio \- Webcam Games](https://scratch.mit.edu/studios/237442/)

You can even use it to control the GPIO pins, when you're using it on the Pi.

* [GPIO control using Scratch on the Raspberry Pi](https://sparkfuneducation.com/how-to/scratch-gpio-control-guide.html#tab4)
* [Physical Computing - Scratch 2.0 for Raspberry Pi](https://www.hackster.io/mjrobot/physical-computing-scratch-2-0-for-raspberry-pi-2d8c0a)
* [Scratch GPIO @ Raspberry Pi Foundation](https://www.raspberrypi.org/documentation/usage/scratch/gpio/README.md)
 
It's also worth noting that there's an offshoot of Scratch called Snap! that was developed by Berkeley. Their version expands upon Scratch, and is geared more towards adults.

* [A web-based alternative to Scratch](http://www.raspberry-pi-geek.com/Archive/2014/06/A-web-based-alternative-to-Scratch)

## Python
Raspbian (like any Linux OS) supports pretty much any language, but Python has become the defacto language for the Raspberry Pi, and most of the tutorials you come across will use it.

* [Download Python](https://www.python.org/downloads/)

A quick side note. You'll see some examples in Python 2 and others in Python 3. Usually, when a language is updated, the new version is backwards compatible. **Python 3 is not.**

* [What should I learn as a beginner: Python 2 or 3?](https://learntocodewith.me/programming/python/python-2-vs-python-3/)
* [Should I use Python 2 or Python 3 for my development activity?](https://wiki.python.org/moin/Python2orPython3)

Here's my two cents. If you need to support a Python 2 project, or have an idea that depends on legacy Python 2 libraries, then consider the older version. But if you're just learning, like for the Pi, then go with Python 3.

### Coding with the IDLE

Python is installed by default on the Pi, but you'll need an environment to type code in. The first option is the Python IDLE (integrated development learning environment), a built-in editor that you get with Python (check under the Programming menu inside Raspbian).

* [Program a Raspberry Pi: Terminal and Python IDLE](https://www.raspberrypi.org/magpi/program-python/) *- Raspberry Pi Foundation*
* [Python 2 IDLE](https://docs.python.org/2/library/idle.html) *- official docs*
* [Python 3 IDLE](https://docs.python.org/3/library/idle.html) *- official docs*

### Coding Online

You might consider these online editors for experimenting, although you'd need to copy the code onto your Pi to run it when you're ready to try it out.

* [JDoodle](https://www.jdoodle.com/python3-programming-online)
* [Pyfiddle](https://pyfiddle.io/)
* [Python Fiddle](http://pythonfiddle.com/)
* [Python Online Shell](https://www.python.org/shell/)
* [Trinket](https://trinket.io/)

### Coding with IDEs

Here are some full-blown IDEs. An IDE is typically a full environment for programming in a language, keeping your project's files together, providing a compiler and debugger, hopefully some intellisense for helping with syntax, etc. They're typically more resource-intensive though, so running directly on the Pi is probably not an option.

* [PyCharm](https://www.jetbrains.com/pycharm/download) *- will probably run directly on a Pi, but it'll be slow*
* [NINJA-IDE](http://www.ninja-ide.org/about/) *- haven't tried it, but looks promising*
* [spyder](https://pypi.python.org/pypi/spyder) *- it's an option... doesn't look as user friendly to setup, but I've never tried it*
* [Thonny IDE](https://www.raspberrypi.org/magpi/thonny/) *- apparently made for Raspbian, so will probably perform better on the Pi*

#### Mocking GPIO Pins

If your project requires access to the GPIO pins, but you're coding away from the Pi, you won't be able to run your code unless you can mock out the pins. I wrote a Python module for that purpose, which you might find helpful.

* [Mock GPIO Module](https://github.com/grantwinney/52-Weeks-of-Pi#mocking-rpigpio)

### Python Tutorials

**[Beginning Python Programming (Raspberry Pi Week 7 – Day 2)](http://www.suntimebox.com/raspberry-pi-tutorial-course/week-7/day-2-beginning-python-programming/)**
Part of a larger couse from Suntimebox, this post covers the basics of Python. If you end up liking it, week 8 of their course covers Python in more depth.

**[Getting Started with GUIs](https://projects.raspberrypi.org/en/projects/getting-started-with-guis)**
All of my Python modules up to this point have been command-line driven, but eventually you may want to create a nice GUI for someone to interact with your code.

**[Learn Python \- Free Interactive Python Tutorial](https://www.learnpython.org/)**
An extensive tutorial, with code samples written in Python 3. They even have a [Facebook group](https://www.facebook.com/groups/learnpython.org/about/) for community support.

**[Python for Everybody](https://www.py4e.com/)**
A website dedicated to learning Python, from [installing it](https://www.py4e.com/install), to learning it [step-by-step](https://www.py4e.com/lessons). Created by [Charles Severance](https://twitter.com/drchuck).

**[Python For Beginners](https://www.python.org/about/gettingstarted/)**
From the official Python site, links to what you need to install, and where you can learn more.

**[Python Usage Documentation](https://www.raspberrypi.org/documentation/usage/python/)**
From the Raspberry Pi Foundation, a brief intro to Python and the IDLE.

### Python MOOCs (free online classes)

There's a whole lot of MOOCs for learning Python too *([What's a MOOC](https://grantwinney.com/a-march-of-moocs-how-to-find-a-good-course-working-as-a-team-is-free-really-free/)?),* some with start dates (mostly if an actual instructor will be available) but most you can join whenever and take at your own pace. A few of these might not sound beginner level, but the syllabi and reviews indicated they were.

* [An Intro to Interactive Programming in Python (Part 1)](https://www.coursera.org/learn/interactive-python-1) *- Rice University (Coursera)*
* [An Intro to Interactive Programming in Python (Part 2)](https://www.coursera.org/learn/interactive-python-2) *- Rice University (Coursera)*
* [Intro to Computer Science and Programming Using Python](https://www.edx.org/course/introduction-computer-science-mitx-6-00-1x-11) *- MIT (edX)*
* [Intro to Computing using Python](https://www.edx.org/course/introduction-computing-using-python-gtx-cs1301x) *- Georgia Tech (edX)*
* [Intro to Python for Data Science](https://www.datacamp.com/courses/intro-to-python-for-data-science) *- DataCamp*
* [Intro to Python: Absolute Beginner](https://www.edx.org/course/introduction-python-absolute-beginner-microsoft-dev236x-1) *- Microsoft (edX)*
* [Intro to Python: Fundamentals](https://www.edx.org/course/introduction-python-fundamentals-microsoft-dev274x-1) *- Microsoft (edX)*
* [Intro to Python for Data Science](https://www.class-central.com/course/edx-introduction-to-python-for-data-science-5683) *- Microsoft (edX)*
* [Learn to Program: The Fundamentals](https://www.coursera.org/learn/learn-to-program) *- University of Toronto (Coursera)*
* [Learn to Program Using Python](https://www.edx.org/course/learn-program-using-python-utarlingtonx-cse1309x) *- University of Texas Arlington (edX)*
* [Programming for Everybody (Getting Started with Python)](https://www.coursera.org/learn/python) *- University of Michigan (Coursera)*
* [Programming Foundations with Python](https://www.udacity.com/course/programming-foundations-with-python--ud036) *- Kunal Chawla (Udacity)*
* [Python Programming: A Concise Introduction](https://www.coursera.org/learn/python-programming-introduction) *- Wesleyan University (Coursera)*
* [Python Programming Essentials](https://www.coursera.org/learn/python-programming) *- Scott Rixner, Rice Unversity (edX)*
* [Python Programming for Everybody](https://www.canvas.net/browse/canvasnet/courses/python-for-everybody) *- Charles Severence*

If you get hooked on Python, consider following these enthusiasts (aka Pythonistas) on Twitter:

* [Dan Bader](https://twitter.com/dbader_org)
* [Harlin Seritt](https://twitter.com/HarlinAtWork)

## Tutorials

So you've got a little Python under your belt, or you're gonna skip it for now and learn as you go - what next? There are *so many* Pi tutorials available out there - here are just a few. I tried to split them up a bit, listing ones I thought were more "beginner" first, but it doesn't mean much since what's "beginner" for one person may be "advanced" for another.

### Beginner

**[Circuit Basics - Raspberry Pi](http://www.circuitbasics.com/raspberry-pi/)**
Some nice guides for connecting various sensors and configuring accessories.

* [Running your first Python program](http://www.circuitbasics.com/how-to-write-and-run-a-python-program-on-the-raspberry-pi/)
* [Setting up wifi on the Raspberry Pi 3](http://www.circuitbasics.com/how-to-set-up-wifi-on-the-raspberry-pi-3/)
* [Configuring remote access to your Pi](http://www.circuitbasics.com/access-raspberry-pi-desktop-remote-connection/)

**[Conquer the Command Line](https://www.raspberrypi.org/magpi/issues/essentials-bash-vol1/)**
A special edition of The MagPi written by [Richard Smedley](https://twitter.com/RichardSmedley), covering how to read and write text files, install software, and more.

**[How to take screenshots on the Raspberry Pi](https://howchoo.com/g/mgmym2fimzd/how-to-take-screenshots-on-the-raspberry-pi)**
You might want to share an image of something you've done, or an error you're getting. It's handy to know how to capture the screen when you need to.

**[Introduction to the Raspberry Pi](https://pythonprogramming.net/introduction-raspberry-pi-tutorials/)**
A nice page and couple of videos on getting started with the Pi, created by [Harrison Kinsley](https://twitter.com/sentdex). And there's no question he knows his way around Python, the defacto programming language for the Pi.

**[Raspberry Pi - The Unofficial Tutorial](https://www.makeuseof.com/tag/great-things-small-package-your-unofficial-raspberry-pi-manual/)**
Wow. Christian Cawley of MakeUseOf wrote a phenomenal article covering the Pi from top to bottom. A great place to get up to speed on the Pi.

**[RaspberryPi.org Projects](https://projects.raspberrypi.org/en/projects)**
A couple hundred projects from the Raspberry Pi Foundation, broken down nicely into clearly-defined steps.

**[Raspberry Pi Workshop for Beginners](https://www.youtube.com/watch?v=xiR14tSfc-U&list=PLPK2l9Knytg67nkvpnnl81ossAHfOgmqU)**
A collection of 30 videos introducing various topics, from NOOBS to Python to connecting peripherals.

**[The Raspberry Pi Platform and Python Programming for the Raspberry Pi](https://www.coursera.org/learn/raspberry-pi-platform)**
Taught by Ian Harris of the University of California, Irvine, this free course introduces the Pi, getting it setup, and getting started with Python.

### Even More

**[Adafruit](https://learn.adafruit.com/category/raspberry-pi)**
You'll see Adafruit on this list a few times, for different reasons. They're a super active company, selling electronics and kits, and providing free tutorials.

**[Building a Raspberry Pi Baby Monitor](http://stuffbabiesneed.com/blog/building-raspberry-pi-baby-monitor-part-one/)**
Hey, why not? There are lots of parents out there, and baby monitors can be expensive, especially with a video feed. Learn how to create one with a Pi that's accessible anywhere on your intranet.

**[Hackster.io](https://www.hackster.io/raspberry-pi/projects?sort=published)**
If you're looking for inspiration, it's probably here. They have hundreds (thousands?) of DIY projects, and you can filter by difficulty, product, etc.

* [Connecting your Pi to the web via cellular](https://www.hackster.io/hologram/add-cellular-to-a-raspberry-pi-with-hologram-nova-ea5926)
* [GooglePi \- Google Assistant on Raspberry Pi](https://www.hackster.io/Salmanfarisvp/googlepi-google-assistant-on-raspberry-pi-9f3677)
* [Raspberry Pi Door Bell](https://www.hackster.io/77857/raspberrydoorbell-8ebb74)
* [Security Camera](https://www.hackster.io/windows-iot/security-camera-579b7f)

**[Instructables](https://www.instructables.com/technology/raspberry-pi/)**
Lots of random projects from lots of random people. If you're looking for inspiration, you should be able find *something* here!

**[Interfacing with the Raspberry Pi](https://www.coursera.org/learn/raspberry-pi-interface)**
Another course by Ian Harris of the University of California, Irvine, this one is more advanced than the previously mentioned intro. It covers interfacing the Pi with various sensors and other electronics.

**[Pi My Life Up](https://pimylifeup.com/category/guides/)**
Guides for common tasks you might find yourself tackling, like these: 

* [Updating Raspbian](https://pimylifeup.com/update-raspbian/)
* [Converting analog signals to digital](https://pimylifeup.com/raspberry-pi-adc/) *(useful when you try to use an analog control such as a joystick)*

**[Raspberry Pi Spy](https://www.raspberrypi-spy.co.uk/category/tutorials-help/)**
Dozens of helpful tutorials, many showing how to interface with various hardware:

* [RC522 RFID Tag Reading with the Raspberry Pi](https://www.raspberrypi-spy.co.uk/2018/02/rc522-rfid-tag-read-raspberry-pi/)
* [Using a servo with the Raspberry Pi](https://www.raspberrypi-spy.co.uk/2018/02/basic-servo-use-with-the-raspberry-pi)
* [7\-segment Display Modules and the Raspberry Pi \- Raspberry Pi Spy](https://www.raspberrypi-spy.co.uk/2016/03/7-segment-display-modules-and-the-raspberry-pi/)

**[Reboot or shut down your Raspberry Pi using an Amazon Dash Button](https://howchoo.com/g/ymy4nza0nzb/reboot-your-raspberry-pi-using-an-amazon-dash-button)**
Zach shows how to hack an Amazon Dash button in order to power down your Pi.

**[Solar Powered, Remote Controlled, Smart Garden](https://www.hackster.io/jamesthomas915/solar-powered-remote-controlled-smart-garden-f9beee)**
James Thomas wrote about using solar power to run a Pi that monitored a garden. I find it easier to figure out _how_ to do something if I have a good _why_... and this seems like a fun project to tackle.

**[Teaching Physical Computing with Raspberry Pi and Python](https://www.futurelearn.com/courses/physical-computing-raspberry-pi-python)**
James Robinson, of the Raspberry Pi Foundation and Picademy, created a course for interacting with the physical environment through sensors and electronics.

**[The MagPi Tutorials](https://www.raspberrypi.org/magpi/tutorials/)**
The MagPi is an online magazine, covered in the next section below. They also provide a series of tutorials for different projects. They're not exactly starter tutorials (IMO), but they seem to be broken down nicely into steps, often including breadboard designs and the code to run.

**[The PiHut](https://thepihut.com/blogs/raspberry-pi-tutorials)**
Roughly 40 tutorials on configuring the Pi and assembling various accessories.

**[SparkFun](https://learn.sparkfun.com/tutorials/)**
You'll have to do a little digging since their tutorials cover a wide range of topics, but there are a fair amount specific to the Pi.

**[Tinkernut](https://www.tinkernut.com/portfolio_cat/episodes/)**
Some cool Pi project ideas, laid out nicely and with the required parts all listed upfront, many with prices so you can get an idea of how expensive a project might be.

* [Controlling your Pi over the web](https://www.tinkernut.com/portfolio/make-raspberry-pi-web-controls/)
* [How To Make A Cheap 360 Video Camera With A Raspberry Pi](https://www.tinkernut.com/portfolio/make-cheap-360-video-camera-raspberry-pi/)
* [Portable Spotify player](https://www.tinkernut.com/portfolio/hipster-spotify-radio-using-raspberry-pi/)

**[52 Weeks of Pi](https://github.com/grantwinney/52-Weeks-of-Pi)**
Full disclosure, this one's mine. And it's pretty embarrassing I didn't even make it to double digits. But there are a few things in there for you to try out, and I was diligent about including diagrams, photos, and all the code you'd need to get the projects to work.

### YouTube

Lots of cool stuff on YouTube too, if you're looking for even more ideas. Here are some nice channels.

**[ExplainingComputers (Raspberry Pi 3)](https://www.youtube.com/watch?v=T_WlF9I5EGw&list=PL2m2YvnrOYxKWlCkoSZXfkLtgDAMev9oN)**
A series of videos taking the Pi 3 out for a spin, from comparing it to the Pi 2, to talking about how to overclock it and multiboot with BerryBoot.

**[ExplainingComputers (Raspberry Pi)](https://www.youtube.com/watch?v=T_WlF9I5EGw&list=PL2m2YvnrOYxLgdiZDxIfhyU4ETr-v36sH)**
A series of videos regarding the Pi. Some of the same videos as the previous playlist but not all, plus more about multiple versions of the Pi.

**[Gaven MacDonald](https://www.youtube.com/user/updowndown/videos)**
Gaven hasn't posted any new videos in awhile, but the videos that are there could be really helpful. As I said, figuring out how to use some of the sensors and various electronics with the Pi is tricky, and most of Gaven's videos deal with just that.

**[Newman Solutions](https://www.youtube.com/channel/UCISJLcrpjARN4wkHcRDxHSA/playlists)**
At least 80 videos covering a wide array of things you can try with the Pi. They seem nicely done, but personally I'd prefer a voiceover explaining what I'm watching over the music playing in each video.

**[Pi My Life Up](https://www.youtube.com/channel/UC7NMrNa-RgcVeD__l_uPJTg)**
Dozens of videos about different projects you can try out with the Pi, including motion and temperature sensors, minecraft and plex servers, creating a photo frame, and more.

**[RaspberryPi](https://www.youtube.com/channel/UCFIjVWFZ__KhtTXHDJ7vgng)**
Official channel of the Raspberry Pi, you'll find general tutorials for the Pi and related technologies like Scratch and the Astro Pi mission involving the ISS.

**[Raspberry Pi IV Beginners](https://www.youtube.com/channel/UCRAvo5cQWyfog8nRzlf_jWg)** 
The videos on using various sensors should prove helpful. The Pi can work with a lot of sensors and accessories with a little bit of extra setup *(like I did with an [analog joystick](https://grantwinney.com/connecting-an-analog-joystick-to-the-raspberry-pi-and-using-it-with-an-rgb-led-to-simulate-a-color-wheel/)),* but you'll often find that sensors come with little or no instructions on how to use them.

**[RasPi.TV](https://www.youtube.com/user/RasPiTV)**
Alex Eames has posted well over a hundred videos, some giving basic overviews of the Pi and related technologies, while others are more advanced like using a [RasPiO Duino](http://rasp.io/duino/) board to [monitor his central heating system](https://www.youtube.com/watch?v=ykrmm2xrTM0) with the Pi.

**[Tech Erudio](https://www.youtube.com/watch?v=Jj4pjfU_-jo&list=PLsa31gkyINsly6N_usaeHrtDPYnwxO-1Y)**
A nice set of videos to get you up and running with the Pi, from setup to lighting an LED.

**[The MagPi](https://www.youtube.com/channel/UCgZlbxTljh1aXKijTRye5bA)**
Tutorials and reviews of Pi-related technologies.

**[TheRaspberryPiGuy](https://www.youtube.com/channel/UCfY8sl5Q6VKndz0nLaGygPw)**
Matt posts a lot of general tutorials and informational videos.

### Other Languages

I mentioned earlier that Python is the most common language used on the Pi, but that it also supports many other languages. Here are some tutorials for other languages supported on the Pi.

#### C

**[Beginning C Programming (Raspberry Pi Week 7 – Day 3)](http://www.suntimebox.com/raspberry-pi-tutorial-course/week-7/day-3-beginning-c-programming/)**
Part of a comprehensive course from Suntimebox, covering C programming on the Pi.

**[Learn C Essentials \- The MagPi Magazine](https://www.raspberrypi.org/magpi/issues/essentials-c-v1/)**
A special edition of The MagPi, dedicated to programming in C on the Raspberry Pi.

#### C#, C++, Visual Basic (UWP Apps)

**[Getting started (with UWP): Choosing a programming language](https://docs.microsoft.com/en-us/windows/uwp/porting/getting-started-choosing-a-programming-language)**
The previous page uses C# for its examples, but when you're using Visual Studio you should be able to choose from at least C++, Visual Basic, and JavaScript too. Contains code samples and links to further reading, if you're interested in another language.

**[How To Create Custom GUI Apps For Raspberry Pi Using Visual Studio](https://www.youtube.com/watch?v=ZBsLR6QotoQ)**
And for those who prefer videos, here's a nice short video demonstrating creating a basic GUI in Visual Studio, then copying it to and running it on the Raspberry Pi (with the help of [Mono](http://www.mono-project.com/)).

**[Internet of Things - Working with Raspberry Pi and Windows 10](https://msdn.microsoft.com/en-us/magazine/mt808503.aspx)** *- Bruno Sonnino, MSDN*
A thorough guide to getting [Windows 10 IoT Core](https://developer.microsoft.com/en-us/windows/iot/getstarted) installed, and developing UWP *(Universal Windows Platform)* apps remotely for your Pi. Visual Studio is probably too intensive to run on the Pi itself.

**[The IoT Journey : Getting Started with the Raspberry Pi 3](https://blogs.msdn.microsoft.com/tedmalone/2016/04/19/the-iot-journey-getting-started-with-the-raspberry-pi-3/)** *- Ted Malone, MSDN*
If you'd like to develop apps for Raspbian instead of Windows 10 IoT Core, here's a detailed walkthrough on using the [Mono framework](http://www.mono-project.com/) to develop cross-platform apps in C#. Again, it assumes Visual Studio on a separate machine. [Mono supports a ton of languages](http://www.mono-project.com/docs/about-mono/languages/), but if you use VS you'll be restricted to what VS supports.

#### C++

**[Beginning C++ Programming (Raspberry Pi Week 7 – Day 4)](http://www.suntimebox.com/raspberry-pi-tutorial-course/week-7/day-4-beginning-c-plus-programming/)**
A nice introduction to programming C++ on the Raspberry Pi. This is actually part of a larger, very comprehensive and completely free course.

**[How to code in C++ on my Raspberry Pi?](https://raspberrypi.stackexchange.com/q/58797/44926)**
Just a thread from the SE network, asking how to code in C++ on the Pi, with a few tips on what to use.

**[Learn to Program Using C++ on the Raspberry Pi: An Easy Introduction to Programming for Beginners Using Linux and GNU C++](http://amzn.to/2Hpxu5d)**
A nice-looking book for learning C++ on the Pi. The reviews are all positive.

**[Use C++ on a Raspberry Pi 3](https://raspberrypi.stackexchange.com/a/75403/44926)**
Another thread from the SE network, with a few suggestions on what to use to develop C++ on the Pi.

#### Go / GoLang

That's actually just one language, but the two names seem to be used interchangeably.

**[Cross Compiling Golang Applications For Use On A Raspberry Pi](https://www.thepolyglotdeveloper.com/2017/04/cross-compiling-golang-applications-raspberry-pi/)**
A very brief tutorial on how to compile your GoLang app in such a way that you can upload it to the Pi and run it.

**[Gobot - Golang framework for robotics, drones, and the IoT](https://gobot.io/)**
If you're into Go, then maybe you'll want to check out Gobot, a framework for using Go to control robotics and other devices. They have [instructions for the Pi](https://gobot.io/documentation/platforms/raspi/).

**[Golang and Docker 1.13 on your Raspberry Pi](https://blog.alexellis.io/golang-docker-rpi/)**
Covers a few different ways to get access to GoLang on the Pi.

#### Java

**[BlueJ IDE](https://www.bluej.org/raspberrypi/)**
A Java IDE that runs on the Pi. It uses the [Pi4J](http://pi4j.com/) library to give you access to the GPIO pins as well.

**[Efficient Java Development for the Raspberry Pi](http://www.instructables.com/id/Efficient-Development-of-Java-for-the-Raspberry-Pi/)**
Learn how to use Java on the Pi, via NetBeans running on another machine - probably because it's too intensive to run directly, even on a Pi 3. Looks very thorough, but be aware that [NetBeans is moving from Oracle to Apache](https://jaxenter.com/netbeans/using-apache-netbeans-incubating-jdk-9), and development on it is frozen, so it might be awhile before it supports the latest/greatest Java 9. Not an issue unless you _need_ to use something from Java 9.

**[Greenfoot](https://www.greenfoot.org/overview)**
A development environment that mixes characters you can move around (similar to Scratch) with the ability to use actual Java code to do it. Seems like it might be a good way to introduce programming to kids. There's a Debian (and hence Raspbian) installer on the downloads page. Not sure if it can access the GPIO pins directly like BlueJ *(see above)* can.

**[IoT Applications With Java and Raspberry Pi](https://dzone.com/refcardz/iot-applications-with-java-and-raspberry-pi)**
The interesting stuff is on page 3, but you probably want to at least glance at the first two as well.

**[Java Programming on Raspberry Pi](https://www.youtube.com/watch?v=P2-wobZrqNg&list=PL6LQDONHZvFLelxXc78XR5ck9Lyf7UBO9)**
A 2-hour series of videos by Daniel Ross, demonstrating the use of Java on the Pi.

**[LEDs on Raspberry Pi GPIO with Java Pi4J - Start to Finish](https://www.youtube.com/watch?v=29va8L2LMfI)**
Using Java on the Pi to light an LED.

**[Raspberry Pi with Java: Programming the Internet of Things (IoT)](http://amzn.to/2Ge7iuE)**
Looking at the reviews, it seems this is not a beginner's book in Java, but it is a good book for learning to accomplish things on the Pi with Java.

#### PHP

**[Installing PHP (Raspberry Pi Course Week 6 – Day 4)](http://www.suntimebox.com/raspberry-pi-tutorial-course/week-6/day-4-installing-php/)**
Part of the a comprehensive course on the Pi at Suntimebox.com. This one's a brief intro to using PHP.

**[Programming PHP (Raspberry Pi Course Week 6 – Day 5)](http://www.suntimebox.com/raspberry-pi-tutorial-course/week-6/day-4-programming-php/)**
Same as above. ;)

## Stores

Many of your projects, including some of the ones above, are going to require accessories and peripherals. You might even want to tackle a robotics kit. Fortunately, there are a *lot* of places to shop, and odds are good you'll find what you're looking for.

* [Adafruit](https://www.adafruit.com/category/105)
* [CanaKit](https://www.canakit.com/raspberry-pi)
* [ModMyPi](https://www.modmypi.com/)
* [Monk Makes](https://www.monkmakes.com/product/) 
* [Newark element14](http://www.newark.com/c/embedded-computers-education-maker-boards/raspberry-pi)
* [Pimoroni](https://shop.pimoroni.com/collections/raspberry-pi)
* [Pi Supply](https://www.pi-supply.com/)
* [Raspberry Pi Foundation](https://www.raspberrypi.org/products/)
* [RasPiO](https://shop.rasp.io/)
* [SparkFun](https://www.sparkfun.com/categories/233)
* [The PiHut](https://thepihut.com/collections/raspberry-pi-store)

## Blogs / Magazines / Ezines

Once you really get going, you'll want to stay updated on new stuff going with Pi, or goings on in the Pi community, or just new projects to try. Here are some great blogs and magazines to check out.

**[Adafruit](https://blog.adafruit.com/category/raspberry-pi/)**
In addition to selling kits, Adafruit provides a lot of helpful blog posts, and even shares blog posts and resources from around the web.

**[Christian Cawley, MakeUseOf.com](https://www.makeuseof.com/tag/author/ccawley/)**
He writes a lot of tech-related articles (like, *1000+* a lot), a fair amount of which concern the Raspberry Pi. Dig around for some gems, like this one on creating [DIY lego cases](https://www.makeuseof.com/tag/lego-raspberry-pi-cases/).

**[Electronics Weekly](https://www.electronicsweekly.com/news/products/raspberry-pi-development/)**
Specializing in news about electronics *(surprising, I know),* Electronics Weekly provides news regarding the Pi and its related hardware, as well as the Raspberry Pi Foundation and other companies involved in Pi development.

**[Hackaday](https://hackaday.com/tag/raspberry-pi/)**
Interesting articles about projects from around the web, including quite a few involving the Raspberry Pi.

**[Les @ Bigl.es](http://bigl.es/tag/raspberry-pi/)**
Les writes extensively about the Pi, on his site and elsewhere. He showcases some pretty creative projects, like this [Harry Potter frame](http://bigl.es/friday-fun-diy-harry-potter-animated-frame/).

**[Pi Supply](https://www.pi-supply.com/blog/)**
Posts are few and far between, but Pi Supply occasionally announces the release of new hardware.

**[Raspberry Pi Pod](http://www.recantha.co.uk/blog/)**
Various walkthroughs and tutorials for the Pi, from [Mike Horne](https://twitter.com/recantha).

**[Raspberry Pi Starter Kits](https://www.raspberrypistarterkits.com/blog/)**
They frequently post tutorials and other interesting news regarding the Pi.

**[SparkFun](https://www.sparkfun.com/news/tags/raspberry-pi)**
SparkFun has an active blog, including some posts specific to new developments in Pi-related hardware.

**[The MagPi Magazine](https://www.raspberrypi.org/magpi/issues/)**
The MagPi is an amazing resource for projects and other information. They publish on a monthly basis, and although you can pay to support them, the magazines are available for free. There are one-off special issues too, like the two that each have 200 pages of projects, and others that focus on specific tech like using cameras with the Pi.

**[The PiHut](https://thepihut.com/blogs/raspberry-pi-roundup)**
Lots of "roundup" style blog posts, showcasing some cool Pi-related projects that people are working on from all over the community.

**[The Polyglot Programmer](https://www.thepolyglotdeveloper.com/categories/raspberry-pi/)**
Various articles covering an assortment of Pi-related topics. 

## Contests / Events

Ready to show off a bit? Or learn from what others are doing? Here are some events.

**[Adafruit Blog - Contests](https://blog.adafruit.com/tag/contest/)**
Adafruit has a very active blog, and sometimes they post upcoming contests. Granted, looking at the older posts it's been a couple years since they posted contests regarding the Raspberry Pi, but it wouldn't hurt to keep an eye on them from time to time.

**[element14](https://www.element14.com/community/community/design-challenges)**
They have challenges from time to time that focus a certain topic like "safe wearables", "upcycling", and [using the Pi to improve the kitchen experience](https://www.element14.com/community/community/design-challenges/pichef). I found these contests after stumbling on a project involving [monitoring oven temperature](https://www.element14.com/community/community/design-challenges/pichef/blog/2018/03/04/bake-mate-pi-chef-blog-6-measuring-oven-temperature).

**[PA Consulting's Raspberry Pi Competition](https://www.paconsulting.com/events/raspberry-pi-competition/)**
Only open to the UK. They pick a theme each year, then select a few winners to receive generous monetary prizes. You'll have to wait until next year though, since as of this writing registration closed about a week ago.

**[Pi Wars](https://piwars.org/)**
A two-day Raspberry Pi robotics competition held in Cambridge, UK. They accept up to 76 teams from anywhere in the world. I love that they emphasize "non-destructive challenges" ... don't expect any *Real Steel* action when they hold the next competition in April.

**[PyCon](https://us.pycon.org/)**
A week long conference on everything Python (default language of the Pi and all). I know conferences are tough to get to depending on location, but this one is in my backyard so I had to toss it out. If you decide to check it out, it's a *relatively* safe bet that by May we'll have warm weather... or at least, a minimal chance of frost.

**[Raspberry Jam](https://www.raspberrypi.org/jam/)**
Community events held around the world, which focus on the Raspberry Pi. The Pi Foundation even put together a comprehensive [guidebook for starting your own jam](https://www.raspberrypi.org/jam/guidebook/), packed with nearly 70 pages of advice.

## Software

Here are some software projects, either to run on the Pi or to support your Pi development.

**[BerryBoot](http://www.berryterminal.com/doku.php/berryboot)**
If you're going to use multiple OS's for different projects at the same time, I'd just invest in several SD cards - they're cheap enough. However, if you're short on SD cards, or have a few with tons of space, or you've tried NOOBS and are unhappy with it, check out BerryBoot. Whereas NOOBS allows you to easily install multiple OS's and choose between them, changing your decision later on means wiping them all out and reinstalling your new selections - BerryBoot (as I understand it) allows you to have multiple OS's, switch between them, and change which OS's are loaded. However, I'm not sure it's as beginner-friendly as NOOBS.

**[DietPi](http://dietpi.com/)**
An OS optimized for minimal space, CPU and RAM requirements.

**[Edublocks](https://edublocks.org/)**
A tool for transitioning from drag-n-drop interfaces like Scratch to actually programming in Python. You can drag elements of Python3 onto a board, similar to Scratch, but then view the actual Python code and even download it.

**[Fritzing](http://fritzing.org/home/)**
A free program for creating circuit diagrams. I find this tool extremely helpful in documenting and sharing layouts, like when I wired up an [analog joystick](https://grantwinney.com/connecting-an-analog-joystick-to-the-raspberry-pi-and-using-it-with-an-rgb-led-to-simulate-a-color-wheel/#spanidfritzing_diagramfritzingdiagramspan) and created my [simon clone](https://grantwinney.com/creating-a-simon-game-clone-on-the-raspberry-pi/#spaniddiagramdiagramspan).

**[Hass.io](https://home-assistant.io/hassio/)**
If you're into home automation, here's an app written for the Pi that can help you out.

**[Jasper](https://jasperproject.github.io)**
An [open source](https://github.com/jasperproject/jasper-client) platform for designing voice-controlled apps, Jasper was made to run on a Raspberry Pi. The possibilities for this are pretty awesome.

**[Mopidy](https://www.mopidy.com/)**
This just sounds awesome. Mopidy lets you stream music from a Raspberry Pi, from disk but also other sources like Spotify and Google Play Music.

* *Related: [Installing Raspbian and Mopidy on the Raspberry Pi](https://smartishhome.com/installing-raspbian-mopidy-raspberry-pi/)*

**[OctoPi](https://github.com/guysoft/OctoPi)**
OctoPi brings [OctoPrint](https://github.com/foosel/OctoPrint) to the Raspberry Pi, OctoPrint being a program that provides a web interface for controlling a 3D printer. Created by [Gina Häußge](https://twitter.com/foosel).

**[openHAB](https://docs.openhab.org/installation/openhabian.html)**
Another home automation tool. Check out their openHABian image, which lets your Raspberry Pi centralize all your home automation tasks.

**[PiBakery](http://www.pibakery.org/about.html)**
I haven't tried it, but this is such a cool idea. It can take awhile to get the Pi setup the way you need, depending on the project you're tackling. PiBakery gives you a Scratch-like interface for creating a script that'll automate the process, and then you can export and share it - maybe with a class or code club, or to upload and make it part of a tutorial. Very cool! Created by [David Ferguson](https://twitter.com/fergusondavid6).

**[Pi Cart: a Raspberry Pi Retro Gaming Rig in an NES Cartridge](https://howchoo.com/g/mti0oge5nzk/pi-cart-a-raspberry-pi-retro-gaming-rig-in-an-nes-cartridge)**
This is so cool looking, I want to stop writing and go try it *right now*. Zach makes a single NES cartridge that houses 2400 games, and runs them on an emulator.

**[Pi-hole](https://pi-hole.net/)**
Sick of ads? How many of us have ad blockers on Chrome, Firefox, tablets and phones, etc? Install Pi-hole on a Raspberry Pi and set it up so your router funnels all your network traffic through it, and it'll filter the ads out before they get to your devices.

* *Related: [Setting up a Pi Hole for whole-home ad/tracker blocking](https://www.jeffgeerling.com/blog/2017/setting-pi-hole-whole-home-adtracker-blocking) by Jeff Geerling*

**[PiNet](http://pinet.org.uk/)**
Allows a group of people running Pis (say, a classroom or coding club) to setup one machine to act as the centralized location for user accounts and file storage. It's a neat idea, since that one machine could easily be backed up, instead of needing to keep track of dozens of fragile (and easily losable) SD cards. Created by [Andrew Mulholland](https://blog.gbaman.info/?page_id=90).

**[PiVPN](http://www.pivpn.io/)**
Configure your Pi with a VPN client, to give you secure and private connectivity to the Internet.

* *Related: [How to turn your Raspberry Pi into a Home VPN Server using PiVPN](http://kamilslab.com/2017/01/22/how-to-turn-your-raspberry-pi-into-a-home-vpn-server-using-pivpn/)*

**[RetroPie](https://retropie.org.uk/)**
Turns your Pi into a retro gaming machine, capable of playing old arcade and console games.

* *Related: [Build your own Raspberry Pi retro gaming rig using RetroPie](https://howchoo.com/g/n2qyzdk5zdm/build-your-own-raspberry-pi-retro-gaming-rig)*
* *Also: [RetroPie Setup for Raspberry Pi 3 – The Quick and Easy Guide](https://gameroomsolutions.com/raspberry-pi-3-retropie-setup-easy-guide/)*

**[Screenly](https://www.screenly.io/)**
Turns your Pi into a media server, serving up video and images to other devices in your household.

**[Sonic Pi](http://sonic-pi.net/)**
Sonic Pi is the creation of [Sam Aaron](https://twitter.com/samaaron), and it allows you to actual program sounds and create music! It's a really cool app. I used it a couple times back in 2016, first to [mimic a grandfather clock](https://grantwinney.com/creating-music-with-sonic-pi-on-the-raspberry-pi/), and then to [create a simon clone](https://grantwinney.com/creating-a-simon-game-clone-on-the-raspberry-pi/). Sam even wrote a special issue of The MagPi called [Code Music with Sonic Pi](https://www.raspberrypi.org/magpi/issues/essentials-sonic-pi-v1/). If you happen to see [Scott Fradkin](https://twitter.com/sfradkin) appear as a speaker anywhere, I learned of Sonic Pi during his livecoding session at [Stirtrek](https://stirtrek.com/) a couple years ago, and it was an excellent session.

**[Things Gateway](https://iot.mozilla.org/gateway/)**
Mozilla has designed an app that allows you to control all your IOT devices from a single interface running on a Pi, instead of using each device's individual web interface. Here's a [full walkthrough](https://hacks.mozilla.org/2018/02/how-to-build-your-own-private-smart-home-with-a-raspberry-pi-and-mozillas-things-gateway/).

**[Volumio](https://volumio.org/)**
Turn your Raspberry Pi into an audio player that can stream all your music. Similar options include [OSMC](https://osmc.tv/), [OpenELEC](https://openelec.tv/), and [Pi MusicBox](http://www.pimusicbox.com/).

**[Webfoot Games](http://www.webfootgames.com/pi/)**
A slew of retro arcade-style and card games they made available to the Pi, available for free!

**[Xbian](http://www.xbian.org/)**
In their own words, "XBian is a small, fast and lightweight media center distribution for the Raspberry Pi."

**[YoYo Games](https://www.yoyogames.com/pi)**
A few free games for the Pi, including "They need to be fed", "Super crate box", and "Maldita Castilla".

## Hardware

There's some really amazing hardware out there that enhances and extends the functionality of the Pi, usually by interfacing through its GPIO pins.

**[JustBoom](https://www.justboom.co/)**
An amplifier for your Pi.. if you're playing music with it and need an extra kick, I guess!

**[Flick](https://www.pi-supply.com/brand/pi-supply/flick/)**
Tracks movement and gestures. This could have some pretty neat uses. Wonder if this is the same kinda tech they use in those magic wands in the Harry Potter World in Orlando?

**[Kano Computer Kit](https://kano.me/)**
Cute kits. Everything you need to build your own laptop out of a Pi.

**[Pibrella](http://pibrella.com/)**
A HAT that sits on your Pi, providing 3 lights, a button, and a speaker - no wiring necessary.

**[Pi-Car](https://pi-cars.com/2012/12/18/what-is-a-pi-car-and-why-does-it-exist/)**
This looks like a nice kit, and not too expensive either. It comes with everything to let you put together a remote-controlled car controlled by your Pi.

**[PiJuice](https://www.kickstarter.com/projects/pijuice/pijuice-a-portable-project-platform-for-every-rasp)**
There's a lot you can do with the Pi, as long as the cord reaches! The PiJuice is an accessory that sits on top of the Pi like any other [HAT](https://www.raspberrypi.org/blog/introducing-raspberry-pi-hats/), providing portable power for hours. Plus it is apparently capable of recharging using wind and thermoelectric plates to extend the runtime indefinitely.

* *Related: [PiJuice Quick Start Guide and FAQ](https://www.pi-supply.com/make/pijuice-quick-start-guide-faq/)*

**[Raspberry Shake](https://www.raspberryshake.org/)**
Turn your Pi into a seismograph! They're active on [Facebook](https://www.facebook.com/raspishake) if you're into that.

**[Strato Pi](https://www.sferalabs.cc/strato-pi/)**
These little units extend the Pi to for commercial applications, such as power surge protection, UPS features (in case of main power loss), a hardware watchdog to monitor the Pi's health to alert the user of issues, etc.

**[Using Hot Wires / Snap Circuits with Raspberry Pi](http://bigl.es/using-hot-wires-snap-circuits-with-raspberry-pi/)**
I'm a huge fan of [Snap Circuits](http://amzn.to/2DjCHZR), so I had to slip this in _somewhere._ It shows how Snap Circuits can be connected to a Pi. If you try this, you'll want to grab some [Snap-to-Pin Connectors](http://amzn.to/2DmijqO) to connect your Snap Circuits set to a breadboard.

### Robotics

I for one welcome our eventual Raspberry Pi overlords. Here are some hardware kits and related articles that are specific to robotics.

**[CamJam EduKit #3 - Robotics](https://thepihut.com/collections/camjam-edukit/products/camjam-edukit-3-robotics)**
Pretty much everything you need to create your first Pi robot.

**[GoPiGo](https://www.dexterindustries.com/gopigo3/)**
Some impressive robotics kits. You can [read more about them](https://www.raspberrypi.org/magpi/gopigo3-review/) at The MagPi.

**[Raspberry Pi Robotics](https://www.youtube.com/watch?v=41IO4Qe5Jzw&list=PL2m2YvnrOYxLOZG0TGQgm9LAEYuvaglzY)**
A series of videos showing how to use the GPIO pins, first to control some LEDs, then moving to robots.

**[Top 5 RaspberryPi Robot Projects](https://www.youtube.com/watch?v=j_1JFnwOFwI)**
A 10 minute video with some interesting robots, if you're looking for inspiration.

## Social Media

I'm more present on Twitter than Facebook, but I'll try to represent both. I tried to focus on organizations and individuals who post mostly about technology, especially (of course!) the Pi.

### Twitter

* [Andrew Mulholland](https://twitter.com/gbaman1), creator of the previously mentioned PiNet.
* [Ben Nuttall](https://twitter.com/ben_nuttall), community manager for Raspberry Pi Foundation.
* [Clare Sutcliffe](https://twitter.com/ClareSutcliffe), *executive director at Raspberry Pi Foundation*
* [Frank Hockey](https://twitter.com/fth_nix)
* [Joshua Lowe](https://twitter.com/all_about_code)
* [Kano Computing](https://twitter.com/TeamKano)
* [Laura Sach](https://twitter.com/CodeBoom), author for Raspberry Pi Foundation, Hello World, and MagPi.
* [ModMyPi](https://twitter.com/ModMyPi)
* [Pete Lomas](https://twitter.com/PeteLomasPi), co-creator of the Raspberry Pi.
* [PiBorg](https://twitter.com/Pi_Borg)
* [Raspberry Pi Foundation](https://twitter.com/Raspberry_Pi)
* [Raspberry Pi Spy](https://twitter.com/RPiSpy)
* [RaspberryPi Geek](https://twitter.com/raspber_pi)
* [RaspberryPint](https://twitter.com/RaspberryPint)
* [SparkFun](https://twitter.com/sparkfun)
* [The Raspberry Pi Guy](https://twitter.com/RaspberryPiGuy1)

### Facebook

* [Circuit Basics](https://www.facebook.com/circuitbasic/)
* [MagPi Magazine](https://www.facebook.com/MagPiMagazine)
* [PiBorg](https://www.facebook.com/piborg.org/)
* [Raspberry Pi Foundation](https://www.facebook.com/raspberrypi/)
* [Raspberry Pi HQ - Project Blog](https://www.facebook.com/raspberrypihq/)
* [Raspberry Pi News and Ideas](https://www.facebook.com/Raspberry-Pi-News-and-Ideas-816586718421370)
* [Raspberry Pi Projects and Resources](https://www.facebook.com/RaspberryPi.Projects99/)
* [Raspberry Pi Tutorials for Complete Beginners](https://www.facebook.com/raspberrypitutorials/)
* [The Pi Zone](https://www.facebook.com/thepizone)

### Pinterest

* [Cool Components](https://www.pinterest.com/coolcomponents/raspberry-pi/)
* [Instructables](https://www.pinterest.com/instructables/raspberry-pi/)
* [Make Magazine - Raspberry Pi](https://www.pinterest.com/makemagazine/raspberry-pi/)
* [Make Magazine - Robotics](https://www.pinterest.com/makemagazine/robotics/) *- some of them involve a Pi*
* [Pi My Life Up](https://www.pinterest.com/pimylifeup/) *- lots of boards, from getting started, to projects and guides, to gear and more*
* [Raspberry Pi](https://www.pinterest.com/garygs/raspberry-pi/) *(garygs)*
* [RaspberryPi Spy](https://www.pinterest.com/rpispy/)

## Educational Resources

What's the fun in learning something if you can't turn around and teach it to someone else? Here are some educational resources to help along the way.

**[Adafruit + Educators](https://www.adafruit.com/educators)**
Adafruit is a popular supplier, and offers discounts and other promotions to educators, so if you're planning something for a large group maybe you can save a few bucks.

**[Adventures in Raspberry Pi](http://amzn.to/2Hn76Zq)**
A well-rated book, by author Carrie Anne Philbin, focused on the development side of the Pi.

**[CamJam EduKit](https://thepihut.com/collections/raspberry-pi-store/products/camjam-edukit)**
At only £5 (or $7), this minimal set looks perfect for teaching classes or hosting clubs. For a few bucks more, they sell a [sensor kit](https://thepihut.com/collections/camjam-edukit/products/camjam-edukit-2-sensors) that comes with a couple of sensors instead of a button.

**[Hello World](https://helloworld.raspberrypi.org/)**
A free magazine published by the Raspberry Pi Foundation several times a year, Hello World focuses on the educational opportunities provided by the Pi. Looks like a good resource for anyone who finds themselves in a teaching role. *([read more](https://www.raspberrypi.org/magpi/hello-world-magazine/))*

**[Picademy](https://www.raspberrypi.org/training/picademy/)**
The "Raspberry Pi Foundation's free face-to-face professional development programme", Picademy is for anyone in an education-related field. At the end of the program, you could become a [Raspberry Pi Certified Educator](https://www.raspberrypi.org/training/picademy/rce/) as well.

**[Pi Supply kits](https://www.pi-supply.com/product-category/kits-and-bundles/educational/)**
Some of the products they sell are geared towards educational purposes, and marked accordingly, like the [junior science and experimentation kit](https://www.pi-supply.com/product/expeyes-junior-science-learning-experimentation-kit/) and [BBC micro:bit](https://www.pi-supply.com/product/microbit-go/) (a HAT with buttons and LEDs built-in).

**[Raspberry Pi Foundation](https://www.raspberrypi.org/education/)**
The Raspberry Pi Foundation also provides a lot of material to assist in ongoing education, including:

* [Free Online Courses](https://www.raspberrypi.org/training/online/)
* [Project Ideas for Teaching, Learning, and Making](https://www.raspberrypi.org/resources/)
* [Education Newsletter](https://www.raspberrypi.org/education/newsletter/)
* *and more...*

**The MagPi Educator's Edition**
There are some special editions of The MagPi, including a couple "educator edition" issues:
* [Issue 1: Raspberry Pi for Education](https://www.raspberrypi.org/magpi-issues/MagPi-EduEdition01.pdf)
* [Issue 2: Teach and Make with Raspberry Pi](https://www.raspberrypi.org/magpi-issues/MagPi-EduEdition02.pdf)

## Electronics Fundamentals

Some of the electronics you'll use to extend the Pi are surprisingly fragile, so it's good to have a basic understanding of them. Here are some tutorials covering the more common electronics you'll encounter - diodes, resistors, capacitors, buttons, etc.

**[A simple guide to electronic components](https://www.youtube.com/watch?v=6Maq5IyHSuc)** *- bigclivedotcom, YouTube*
An illustration of how various electronic components like capacitors and resistors work.

**[Basic Electricity - Resistance and Ohm's law](https://www.youtube.com/watch?v=NfcgA1axPLo)** *- Afrotechmods, YouTube*

**[Basic Electronics Tutorials](https://www.electronicshub.org/tutorials)**
Links to well over a hundred tutorials covering various electrical components, like capacitors and resistors.

**[Capacitors](https://learn.sparkfun.com/tutorials/capacitors)** *- SparkFun*
A nice illustration of capacitors from SparkFun.

**[Capacitors](http://www.explainthatstuff.com/capacitors.html)** *- Chris Woodford, ExplainThatStuff!*
An overview of how capacitors function, their various uses, and how they even occur in nature.

**[Choosing the Resistor to Use With LEDs: 3 Steps](http://www.instructables.com/id/Choosing-The-Resistor-To-Use-With-LEDs/)**
Covers a few ways to calculate the correct resistor to protect your LEDs. It's a 10 year old article but the still applies. It even links to a couple of calculators you can use to make your life easier, and amazingly they're both still active.

**[Connecting a Push Switch](http://razzpisampler.oreilly.com/ch07.html)**
A walkthrough you can follow to practice using a button. There's a diagram of a button in there that's actually quite helpful in visualizing how it works.

**[Current Limiting Resistor](https://www.build-electronic-circuits.com/current-limiting-resistor/)**
A brief overview of resistors, including how to calculate which one you need - a very handy calculation to have once you start designing your own circuits.

**[Diodes](https://learn.sparkfun.com/tutorials/diodes)** *- SparkFun*
They have a series of tutorials on different components. Here's one that covers diodes.

**[Diodes and LEDs](http://www.explainthatstuff.com/diodes.html)** *- Chris Woodford, ExplainThatStuff!*
An overview of how diodes and LEDs function and their various uses. An interesting fact about LEDs is that current only flows in one direction, which can be taken advantage of in a technique called [charlieplexing](https://grantwinney.com/what-is-charlieplexing-a-short-demo-using-the-raspberry-pi/).

**[Introduction to Electronics](https://www.coursera.org/learn/electronics)** *- Drs. Ferri and Robinson, Jr of Georgia Tech*
An introduction to the basic components of electronics, including diodes, transistors, and op amps. Haven't taken it, but the reviews look generally positive.

**[Picking Resistors for LEDs](https://www.evilmadscientist.com/2012/resistors-for-leds/)**
A comprehensive overview of resistors, and how to pick the right one for your project.

**[Push Button with Raspberry Pi](https://www.hackster.io/hardikrathod/push-button-with-raspberry-pi-6b6928)** *- Hardik Rathod, Hackster.io*
A nice demo of how to use a simple button, with several diagrams, a video, and the accompanying Python code - everything you need to try it yourself.

**[Resistors](https://learn.sparkfun.com/tutorials/resistors)** *- SparkFun*
An illustration of resistors from SparkFun.

**[Resistors](http://www.explainthatstuff.com/resistors.html)** *- Chris Woodford, ExplainThatStuff!*
An overview of how resistors function, their various uses, and how to pick the right one based on the colors of the stripes on their sides.

**[Simple Button Input with the Raspberry Pi](https://www.youtube.com/watch?v=Bqk6M_XdIC0)** *- Gaven MacDonald, YouTube*
A good illustration of what pullup and pulldown resistors are, and why you may need them in your circuit. Covers using an external resistor as well as the Pi's internal resistors.

**[Transistors](https://learn.sparkfun.com/tutorials/transistors)** *- SparkFun*
A tutorial on transistors, with links to further resources. Parts like these often come in electronics kits if you buy one; unfortunately, they frequently contain little documentation.

**[Using PullUp and PullDown Resistors on the Raspberry Pi](https://grantwinney.com/using-pullup-and-pulldown-resistors-on-the-raspberry-pi)**
This one's mine. One of the first times I messed around with resistors I saw some unexpected behavior, and a little research led me to the concepts of pullup and pulldown resistors, so I wrote about it.

**[What is a Circuit?](https://learn.sparkfun.com/tutorials/what-is-a-circuit)** *- SparkFun*
Yet another SparkFun tutorial, this one covers the basics of what a circuit is. Understanding circuits is a prerequisite to doing pretty much anything else with the Pi's GPIO pins.

## Reference Guides / Help

Just some random reference pages, places to get more help, and cheat sheets that might be handy to print and keep nearby.

**[Linux Commands Cheatsheet](https://www.improgrammer.net/linux-commands-cheat-sheet/)**
As you do more with the Pi and find yourself using the command line, a good cheat sheet will help you remember all those pesky Linux commands. ;)

**[Linux Commands Cheat Sheet: A Great Beginners Guide](https://pimylifeup.com/linux-commands-cheat-sheet/)**
Another cheat sheet / brief overview of the more common Linux commands, from Pi My Life Up.

**[Pibrella Commands](http://www.tecoed.co.uk/uploads/1/4/2/4/14249012/pibrella_commands.pdf)** *(pdf)*
A handy cheat sheet for the Pibrella HAT. *(from TeCoEd)*

**[Raspberry Pi Cheat Sheet](http://www.tecoed.co.uk/uploads/1/4/2/4/14249012/ras.pi_noob_hacksheet.pdf)** *(pdf)*
A handy cheat sheet for the Pi. *(from TeCoEd)*

**[Raspberry Pi Pinout](https://pinout.xyz/)**
An interactive guide for the Raspberry Pi, it tells you what each GPIO pin does and a little bit about them. Includes guides for [dozens of other accessories](https://pinout.xyz/boards) too, such as the [Sense HAT](https://pinout.xyz/pinout/sense_hat) used in the [Astro Pi mission](https://astro-pi.org/).

**[Raspberry Pi Commands Cheat Sheet](https://www.raspberrypistarterkits.com/guide/raspberry-pi-commands-cheat-sheet/)** *(Raspberry Pi Starter Kits)*
A couple pages of Pi commands, which you'd run from the command line.

**[Raspberry Pi @ StackExchange](https://raspberrypi.stackexchange.com/)**
Amongst the 170+ sites making up the [StackExchange network](https://stackexchange.com/sites), there's one dedicated solely to the Raspberry Pi. You can ask questions and get answers *(and eventually, provide answers!)* from other enthusiasts and experts.

**[Sonic Pi Cheat Sheet](http://www.tecoed.co.uk/uploads/1/4/2/4/14249012/sonicpi_cheatsheet.pdf)** *(pdf)*
A handy cheat sheet for Sonic Pi. *(from TeCoEd)*

**[TeCoEd - Rapspberry Pi](http://www.tecoed.co.uk/raspberry-pi.html)**
Lots of resources, cheat sheets, and tutorials for using the Pi and related technologies (like Python and Sonic Pi).

**[The MagPi Troubleshooting Special](https://www.raspberrypi.org/magpi/issues/60/)**
Issue 60 of the MagPi was dedicated to solving problems on the Raspberry Pi.

**[42 of the Most Useful Raspberry Pi Commands](http://www.circuitbasics.com/useful-raspberry-pi-commands/)**
A list of commands you'll find handy while navigating around the Debian OS on your Pi.

## Books

For those of us who prefer reading, some books. I specifically looked for those with good ratings, and whose reviews weren't robo-reviews *(i.e. 15 five-star reviews in a 1-week period)...* although I'd encourage you to read the reviews as well. If nothing else, they remind us that what one person finds easy, another person finds hard.

Be aware that as these books age (even 2-3 years), you're likely to run into snags like having a newer version of the Pi than the author, or software that's been updated and changed. Same thing could happen with any decent online tutorial though.

* [Code Your Own Games!: 20 Games to Create with Scratch](http://amzn.to/2GmWc6K) by Max Wainewright
If you're teaching someone Scratch, or learning it yourself, this looks like a nice place to start.

* [Coding Games in Scratch](http://amzn.to/2FKO41Z) by Jon Woodcock
Looks to have lots of solid examples for someone being introduced to Scratch.

* [Coding Projects in Scratch](http://amzn.to/2FzUei7) by Jon Woodcock
Same as above...

* [Encyclopedia of Electronic Components Volume 2: LEDs, LCDs, Audio, Thyristors, Digital Logic, and Amplification](http://amzn.to/2FzRq4z) by Charles Platt
This is one of a 3-part series explaining how to use various electronics. [Volume 1](http://amzn.to/2p7XivF) covers resistors, capacitors, etc, while [Volume 3](http://amzn.to/2tERG0G) covers a variety of sensors. All 3 are well-rated.

* [Python for Kids: A Playful Introduction To Programming](http://amzn.to/2p8m8fb) by Jason R. Briggs
Reviews are favorable, generally indicate it'd be better for older kids. But then that's not a surprise, since it's for text-based coding and not Scratch.

* [Python Programming for Raspberry Pi, Sams Teach Yourself in 24 Hours (2nd Edition)](http://amzn.to/2FGi4sH) by Richard Blum and Christine Bresnahan
Seems to be (true to its name) mostly focused on learning and writing Python code, which will make it possible for you to do other things with the Pi. Not sure how much of a Pi book it is, since they only very briefly touch on the GPIO pins.

* [Raspberry Pi Cookbook: Software and Hardware Problems and Solutions](http://amzn.to/2DnRvGV) by Simon Monk
I read this last year and found it to be a good reference book - [here are my thoughts](https://grantwinney.com/cooking-with-simon-monk-raspberry-pi-cookbook/).

* [Raspberry Pi For Dummies](http://amzn.to/2GlTzSB) by Sean McManus and Mike Cook
Looks like a thorough introduction to the Pi, suitable for someone who's just trying it out for the first time.

* [Raspberry Pi Projects for Kids - Second Edition](http://amzn.to/2FKOUfg) by Daniel Bates
The consensus seems to be that it's better for adults looking to teach kids, than for kids themselves. Topics include Scratch, Python, and Sonic Pi.

* [Scratch Programming Playground: Learn to Program by Making Cool Games](http://amzn.to/2Dnxznp) by Al Sweigart
A very well-rated book about learning Scratch by creating games.

## Interfacing with Arduino

This is outside my wheelhouse, since I don't have an [Arduino](https://www.arduino.cc/); but it's a popular microcontroller and you might be interested in connecting it to a Raspberry Pi for certain projects.

* [Connect Your Raspberry Pi and Arduino Uno\!: 6 Steps \(with Pictures\)](http://www.instructables.com/id/Connect-Your-Raspberry-Pi-and-Arduino-Uno/)
* [Controlling Arduino by Raspberry Pi](http://www.meccanismocomplesso.org/en/controlling-arduino-raspberry-pi/) *- Fabio Nelli*
* [Interfacing Arduino with Raspberry Pi](https://create.arduino.cc/projecthub/sankarCheppali/interfacing-arduino-with-raspberry-pi-6d9870) *- Sankar Cheppali*
* [Program an Arduino UNO with your Raspberry Pi](https://www.raspberrypi.org/magpi/program-arduino-uno-raspberry-pi/)
* [Raspberry Pi Tutorial 38 \- Use an Arduino as a Slave with Python \(Nanpy\)](https://www.youtube.com/watch?v=QumIhvYtRKQ)
* [RasPiO Duino](http://rasp.io/duino/) *- A board that acts like an Arduino, but plugs directly into the Pi for programming. Has excellent reviews at [The PiHut](https://thepihut.com/products/raspio-duino).*

## A List of Lists

If this list isn't enough list for you... have more lists!

**[Raspberry Pi Awesome List](https://github.com/thibmaek/awesome-raspberry-pi)**
When you're done with this list, there's another whole list to check out too! It's not mine, and I deliberately didn't look at it so it wouldn't influence what I included here. No doubt there's some overlap, but (I hope) a whole lot of additional value too.

**[Raspberry Pi: Top 31 projects to try yourself](http://www.itpro.co.uk/mobile/21862/raspberry-pi-top-31-projects-to-try-yourself-1)**
A list of 31 more projects involving the Pi to check out. In case you need more. :)

**[RPi Tutorials @ elinux.org](https://elinux.org/RPi_Tutorials)**
There's so much going on here I don't even know what to make of it. Tons of links to tutorials, guides, projects, etc. It's hard to tell how much of it might be outdated, but there could be some real gems in there.

**[101+ Raspberry Pi Projects For Electronics Students](https://www.electronicshub.org/raspberry-pi-projects)**
Links to tons of (well, 101 I suppose) other projects, with a brief summary of each.

## Pi Day

And last but not least, some fun Pi facts and Pi Day activities!

**[A Brief History of Pi](https://www.exploratorium.edu/pi/history-of-pi)**
I had no idea the concept of Pi goes back *millenia*. Exploratorium shares this and other interesting facts in its brief history of Pi.

**[Find Your Pi Day](http://www.mypiday.com/)**
Enter your birth date (or any date.. or any number for that matter) and it'll find it in Pi and display it back to you. Check it out.. it's neater than I'm making it sound. Read more about [how they did it](http://mypiday.com/about-this-site/).

**[Huge list of FREE Pi Day Activities for All Ages](https://mathgeekmama.com/math-resources/pi-day-goodness/)**
Bethany, aka Math Geek Mama, shares some literature and a long list of links to other Pi-related activities she's collected from around the web.

**[Lesson Plans and Other Activities for Pi Day](http://www.educationworld.com/a_lesson/lesson/lesson335.shtml)**
In Education World, Gary Hopkins shares his own long list of links to activities from around the web, as well as lesson plans.

**[Numbers of Pi](https://www.exploratorium.edu/pi/numbers-of-pi)**
Exploratorium shares the first million digits... just be patient as the page renders. 😬

**[TeachPi\.org Activities](http://www.teachpi.org/activities/)**
More activities! In case all of the above didn't float your boat.

## What are your resources?

Do you have any favorite Raspberry Pi resources? Would you mind [sharing them](contributions.md)? I'm always looking for something else that makes creating with the Raspberry Pi easier or more interesting, and I'm sure lots of other people feel the same way.

Thanks, and enjoy!
