# Add attendees to your EventBrite event

EventBrite is a great package for managing your Ignite. It allows you to sell tickets (either paid or free) and check people in using their free iPhone/Android app.

One major pain is that there's no easy Import function to add attendees. If you have a long list of attendees to add, it's time-consuming and error-prone.

This script automates the process, so you can easily import multiple attendees to your guest list.

#### Before you get started

1) Log into your EventBrite account and open up the event that you wish to add people to. Note its `eid` value, which will be shown in the URL, eg https://www.eventbrite.fr/myevent?eid=123456

2) Hit the Add Attendees option (on the lower-left of the Manage page) then use your browser's Developer Tools to note the ID of the ticket type that you wish to create.

![Finding the ID of the quantify field](http://i.imgur.com/RIYANW1.png)

3) Install the Selenium python plugin from https://selenium-python.readthedocs.org/

4) Get last chromeDriver from Selenium

#### Update the script

1) Enter your EventBrite login and password in the relevant sections.

2) Connect to your googleSheet with this Column structure. Update the SSid and SSname in the relevant sections:

<img width="733" alt="Capture d’écran 2022-07-31 à 20 53 10" src="https://user-images.githubusercontent.com/44141766/182042844-094b1aae-a6cb-4f81-8686-d1ac55baab98.png">


#### Run the notebook
