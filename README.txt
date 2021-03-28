qbehaviour_deferrednonegatives
=================

This is a question behaviour for Moodle Quiz that forces all questions to 
be graded with only positive fractional grades using deferred feedback mode. 
Negative partial grading will take place within a question (e.g. if several 
answers are allowed), but each question can have only o or positive fractional 
grade. Negative marks are not carried to the whole quiz grade. 
It will work with a variety of question types that normally produce negative 
credit for wrong responses.

Works in a way similar to qbehaviour_deferredallnothing but only negative 
partial grades are discarded. Positive fractional grades are possible and count 
towards final grade. 

Copy this directory to question/behaviour/deferrednonegatives in Moodle
director. Login as admin to complete plugin installation.  Then choose
this behaviour while editng quiz settings. All questions in the quiz
will always receive zero or maximum marks when graded.

This plugin is based on qbehaviour_deferredallnothing by Daniel Thies 2015

All original files are copyright Enrique Castro @ULPGC and
are licensed under the included GPL 3
