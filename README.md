##Description

This is a scheduling system for instructors & students, intended to support scheduling of instructor-studentconsult/counseling sessions.
The requirements for this type of scheduling tend to go beyond those for basic shared calendar scheduling, since policies may restrict the length of a single block,
 limit the number of blocks that may be reserved by a single student, etc.

##Intended users

* This is intended for Instructors who want to minimize the need for them to manage their office hours schedule directly. 
* Instructors who want to ensure that all students have an opportunity to schedule appointments during office hours.
* Students who want to make sure that get the consult time needed (or as much of it as possible) withan instructor.

##Client-side functionality

Android app will display an agenda/day-planner-like view of one of more instructors’ schedules, a single dayat a time.

A student user will be able to click on an unassigned/available time block to schedule an appointment, up to the maximum amount of time permitted, and up to the 
cumulative maximum allowed per day (according topolicies set by instructors).

An instructor will be able to view the scheduled appointments, override appointments, set unavailableblocks of time, and set policies at the global, day,
 or half-day level. Initially supported policies will include maximum appointment length and maximum total time per student per day or half-day.

Instructors will also be able to mark an appointment as “kept”, “late”, or “missed”.

##Server/cloud-side functionality

Server will maintain a registry of instructors, students, past and future scheduled appointments, resolutions(kept/late/missed), and policies.
Authentication information will be passed from the client app to the server,
to enforce privacy controls.

##External services/data

* Google Sign In for OAuth 2.0.
* Google Calendar export.