# automated Subject Proposed-list System

The project is in it's infant stage.

##Definition of terms

###Prerequisite Subject
a subject a student should pass first before being able to take a subject.

###Corequisite Subject
a subject a student should take with the subject he intended to enroll.

###Proposed-list
a list of subject that a student can take up for next semester. this would be based on a veriety of things.
 - (1) needs to check the current standing of the student and what semester he is currently on. since the proposed list will be limited on the allotted number of units a student can take depending on the year level and the semester the student is in. this data can be found by checking the curriculum the student is under.
 - (2) the subjects that should be listed here should have met all prerequisite subjects.

##Features

###Authentication
- basing on the group the user is in it should redirect to the correct dashboard usuable for the user.

###User Groups
 - student - can view their grades on their previous subjects / semesters, can see their prospectus / curriculum. can view their proposed list of subject for next semester.
 - teacher
 - admin

##Setting up Development Environment
- Set up a local `Virtual Host`
- Create a MySQL database based on the `app/config/database.php`
- Run `php artisan migrate` and `php artisan db:seed` in the project directory.
- go to your browser and login as `bkintanar` with password `retardko`.

