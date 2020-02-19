## Description

This is a scheduling system for instructors and students, intended to support scheduling of instructor-student consult/counseling sessions.
The requirements for this type of scheduling tend to go beyond those for basic shared calendar scheduling, since policies may restrict the length of a single block,
 limit the number of blocks that may be reserved by a single student, etc.

## Intended users

* This is intended for Instructors who want to minimize the need for them to manage their office hours schedule directly.
* Instructors who want to ensure that all students have an opportunity to schedule appointments during office hours.
* Students who want to make sure that get the consult time needed (or as much of it as possible) with an instructor.

### [User stories](user-stories.md)

## Design documentation

### [Entity-relationship diagram](erd.md)

## External services/data

* Google Sign In for OAuth 2.0.

    * Site URL:<https://developers.google.com/identity/protocols/OAuth2>
    * Service use: OAuth will be used to authenticate users and pass info like name and email for use in Office Hours.
    * Required: Yes, for authenticating users into Office Hours and for needed student information.

* Google Calendar export.

    * Site URL:<https://developers.google.com/calendar>
    * Service use: This will allow users to take appointment made in Office Hours and export them into Google calendar for convenience.
    * Required: No, users don't have to use google export to use Office Hours.

# Ground rules documentation

### [Ground rules](ground-rules.md)

# Entity classes

### [Appointment.java](https://github.com/office-hours/server/blob/master/src/main/java/edu/cnm/deepdive/officehours/model/entity/Appointment.java)

### [Student.java](https://github.com/office-hours/server/blob/master/src/main/java/edu/cnm/deepdive/officehours/model/entity/Student.java)

### [Teacher.java](https://github.com/office-hours/server/blob/master/src/main/java/edu/cnm/deepdive/officehours/model/entity/Teacher.java)

### [User.java](https://github.com/office-hours/server/blob/master/src/main/java/edu/cnm/deepdive/officehours/model/entity/User.java)
