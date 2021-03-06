# watchdog-safety-app

Watchdog is an app that attempts to detect when the user is in distress or under attack, then report the incident and/or scare away the attacker.

This project is a HackISU Fall 2019 project put together by Walter Svenddal, Jesrik Gomez, Karla Montoya, and Arnoldo Montoya.
This app  is committed to improving the safety and peace of mind of communities all over the world.

This app is designed to provide real-time information; including the exact GPS location and time of the disturbance
to ensure the fastest response time to emergencies. The microphone will listen for a series of screams, and if alerted,
will send the coordinates of each device that registered the sound.Will send a SMS alert and display the location
of any disturbances via Google Maps.


Inspiration
After the attacks on two different women in Iowa this summer, we were inspired to develop an application that could have potentially helped these individuals in distress.

What it does
Watchdog is an Android app that attempts to detect when the user is in distress or under attack. There is an emergency notification system which sends an SMS link of the user's current location to his/her emergency contacts, and also sounds an alarm to scare away the attacker. In addition to monitoring for signs of distress, the emergency notification system can also be triggered by saying "help".

How we built it
We built our application by interfacing with the phone's hardware, specifically voice commands, GPS, and gyroscope. We combined data available from the phone with built in functionalities. We also used libraries that allowed us to analyze speech.

Challenges we ran into
We all had different hardware (different phones and virtual devices), so we needed to streamline the application across all systems.

Accomplishments that we're proud of
We finished our first Hack ISU project. We were able to modularize work such that we could all work independently and then integrate everything.

What we learned
We learned how to independently design and implement different components of an application and integrate them. We also got more experience interfacing with Android hardware.

What's next for Watchdog
Port to iOS. Add more distress scenarios/
