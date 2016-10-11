# GoConqrHireMitch
A project to convince GoConqr to hire me.

Android application for GoConqr
-------------

This repo is for the GoConqrHireMitch application as requested by GoConqr. 
Below is a list of the requested criteria as well as a justification of the work I've done.

-------------
Android Assignment

The test url can be found at:
http://shrouded-woodland......

This exposes an API for manipulating events stored on a database.

In addition to all fields being required the end time must not be before start time.

------
Required

> Write an Android application in Java that can:
[COMPLETE] - GET a list of events.
[COMPLETE] - POST a new event.
[COMPLETE] - DELETE an existing event.

[COMPLETE] The application should display validation errors when appropriate.

------
Desired

> The application should deal gracefully:
- [COMPLETE] If no connection is available.
- [COMPLETE] If the server can’t be reached.
- [COMPLETE] If the server provides a bad response.
• [COMPLETE] The application should be source controlled using git. (Extra brownie points for regular commits clearly tracking your progress)
• [COMPLETE] The application includes a nice clean UI.
• [INCOMPLETE] The application uses both activities and fragments

------
You're a rockstar if...

• [COMPLETE] You have rolled your own network implementation using HttpUrlConnection
• [COMPLETE] The application handles offline mode by caching requests so the user can view cached events if no connection is available
• [INCOMPLETE] The UI is beautiful
• [INCOMPLETE] You have implemented a crash reporting mechanism (perhaps using a 3rd party library)
• [INCOMPLETE] You have used smooth and slick animations for transitions / touch events

-------------
Justification:

Because this project had very little interactive user functionality (i.e. the GET, POST, and DELETE features) I decided I would spend more of my time on the more difficult aspects of the spec, like the HttpUrlConnection network implementation, testing, offline caching, and robust error/crashing prevention. 

This meant that I spent very little time on the UI-- though given more time I could certainly make the UI more user friendly and visually appealing. The project has a maximum API of 24 and a minimum of 19, which is why I thought I should test both of these versions (as well as one in between). 

A Nexus 5 and Nexus 6 was used for these different versions. Unfortunately my personal android device's API was not recent enough (API 18) to run this project, and so it has only been tested on emulators. The code could certainly do with some cleaning up, and no comments exist to explain chunks of code, but overall I believe it was a success.
