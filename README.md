# Batteree
A real battery saving app

# What is Batteree?
There are plenty of battery saving apps out there that will help you monitor you current battery usage, predict how much time you have left or try to blame the most battery hungry app for your shortage in battery life. This is not one of those apps. Instead, Batteree will try to actively shut down or pause services and applications that you may not need while on (low) battery power and enable them again, once you are back charging. Some mobile operating systems are or plan to introduce such functionality, but the same actually applies to the desktop, where you might want expect more convinience of this sort as well.

# How does it work?
The problem is actually simple. You are running too many services on your machine that use power. The simple way is to manually shut them down and then restart them when you want to save power. This works, but why shouldn't your computer do this for you. Entrance: Batteree. It scans your running applications and current power usage as well as your wifi signal strength, display brightness to determine how to best safe battery power.

In the future it could also keep track of your daily routines and know when to expect the next charge, but this is just a thought right now.

The point is to shut down more and more applications the more battery power you have consumed, based on which you need the most. For example: You might have 3 cloud sync services running to keep your files up-to-date. While you are on the move, you might not have a solid WiFi connection, though. So, why would you want these services to keep checking if they can sync the latest changes already? Instead, we will shut them down and restart them later.

Location (as in network location) could also be a trigger to shut down / restart certain applications. Your work office may have it's own cloud service, but you don't really want / need that running, unless you are on the company VPN, do you?

# How can I use it?
We'll get to that ones it's done :D !
