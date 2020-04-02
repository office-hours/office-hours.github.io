## Team Roster

### Jose Ortiz

[![GitHub](github.png)](https://jortiz07.github.io/)  [![LinkedIn](linkedin.png)](https://www.linkedin.com/in/jose-ortiz-/)

---

### Alex Reyes

[![GitHub](github.png)](https://vexurion.github.io/)  [![LinkedIn](linkedin.png)](https://www.linkedin.com/in/alexx-reyes/)

---

### Raymond Jaramillo

[![GitHub](github.png)](https://raymondjaramillo.github.io/)  [![LinkedIn](linkedin.png)](https://www.linkedin.com/in/raymondjaramillo/)

---

## [Office Hours](https://github.com/office-hours) Introduction & description

This is a scheduling system for instructors and students, intended to support scheduling of instructor-student consult/counseling sessions.
The requirements for this type of scheduling tend to go beyond those for basic shared calendar scheduling, since policies may restrict the length of a single block, limit the number of blocks that may be reserved by a single student, etc.

The motivations behind this project was to make an app that would make office hours easier for both students and teachers. These appointments could be scheduled ahead of time so a student can make sure that they get the time that they need. On the other hand this will make the process of office hours more seamless and they only need to make one policy for an entire class, and not be in contact with every student to set up appointments.

## Current state

While very close, Office Hours is not yet ready for deployment or testing. At the current state the app has a login using Google authentication and also has singing out functionality. The landing page is a calendar with a search bar above it. It allows for a use to select a teacher using the search bar, then display and decorate days that the teacher has appointments available.

* Deficiencies at this point include:

    * Not being able to view appointment for a days
    * Reserving an appointment
    * A Teacher is not able to create or delete an appointment
* Aesthetic improvements

    * Adding multiple colors to decorate different availabilities of appointments
    * Adding more color schemes to the project

* Stretch goals

    * Adding the ability to upload appointments to Google calendar.
    * Adding reminder capabilities
    * Giving students the option to request an appointment

## Intended users

* This is intended for Instructors who want to minimize the need for them to manage their office hours schedule directly.
* Instructors who want to ensure that all students have an opportunity to schedule appointments during office hours.
* Students who want to make sure that they get the consult time needed (or as much of it as possible) with an instructor.

### [User stories](user-stories.md)

## Build instructions

* Go to the [GitHub repository](https://github.com/office-hours)

* Click on Clone or download

* Make sure Clone with SSH is selected and click the clipboard icon to copy the SSH key

* Use the IntelliJ Check out from Version Control/Git (from the welcome screen) or File/New/Project from Version Control/Git (from the workspace) command to clone.

* DO NOT click open when prompted to do so (it might even ask twice).

* Import the project you just cloned. In the Import Project window, select Import project from external model and then the Gradle item in the list.

* After the project is imported add a run configuration. This should use the Android App configuration, with a Name of "app", and with app selected from the Module pull-down control.

* Click the run icon and select the device you wish to run it on.

## Basic user instructions

There are two different side the UI in Office Hours. One is from the perspective of the teacher and one from the perspective of a student. A teacher has all of the user capabilities and the ability to create appointments. A teacher using Office Hours can make an policy where they can specify the amount of time that they are available and the length of appointments within that given time. Students are then able to view a specific teacher and see all of their available appointments in a calendar and then, if available, select and appointment and reserve it.

## Design documentation

### [Wireframe diagram](wireframe.md)

### [Entity-relationship diagram](erd.md)

### [Data Definition Language](ddl.md)

## Technical Documentation

### [Technical stacks outline](technical-stacks-outline.md)

## External services/data

* Google Sign In for OAuth 2.0.

    * Site URL: <https://developers.google.com/identity/protocols/OAuth2>
    * Service use: OAuth will be used to authenticate users and pass info like name and email for use in Office Hours.
    * Required: Yes, for authenticating users into Office Hours and for needed student information.

* Google Calendar export.

    * Site URL: <https://developers.google.com/calendar>
    * Service use: This will allow users to take appointment made in Office Hours and export them into Google calendar for convenience.
    * Required: No, users don't have to use google export to use Office Hours.

## [Ground rules documentation](ground-rules.md)

## [Data Model Implementation](data-model.md)

## Licensing 

### [License](notice.md)