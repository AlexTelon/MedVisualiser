MedVisualisation:


# Functional specification:
The idea of the project is to be able to visit a site and get your information about meds on one place. The information shown will come from 1177 as well as other official sources. With official I mean that they are from the state and can be used by doctors and other such personel.

One should be able to search for brands or the medical substances used in the different medecines. Once you have selected a medecine you get up some infromation about it and also a little box representing the medecine. You can then search for additional medecines and get information about that new med. But the program will also show any connections between them. 

If one has 3 meds up and they all have different warnings, the warnings will be shown aggregated at all times at some place on the page. So the user always sees that if he or she is to use them all then he/she should use them if the user has heart problems or is allergic to X. Things like that can be helpful for users that use many medecines as well as relatives to people that take many.

Meds that are medically equivalent should also be highlighted in a way so the user realises he or she has two or more meds doing the same thing. This will help in not taking overdoses by accident.

I am not sure if I the user can be able to login or not. On one hand it will make the user able to come back to see all the meds he/she has searched for before. A user can order the meds into different corners of the canvas and if he/she logs in once in a month or so to add/remove a med or two it would be good to have all that old information saved somewhere.

On the other hand the information about what medecines a person uses or is potentially thinking about using is very delicate information which I am not willing to store right now. So I will se what I do.

# Technological specification:

## (1) client framework
Angluar.js for frontend, just becaouse I think would like to learn more about it.

## (2) Server framework
I will most likely use flask as a micro-backend.

## (3) Data Storage 
The data about where stuff where placed and what searches have been done previously should be saved in a good way. I will most likely use MySQL.

## (4) Authentication
If there is a login I will have to add a anonymous login option, people wont want to have facebook or G+ connected to a meds account. But one of the two might be the easiest to do. Would love to test SQRL (Sequire Quick Reliable Login), a new quite unknown new solution for login.
If I use flask then I will look at the options to do this, dont know what is easiest to work with yet.

## (5) multiple clients
I want it to work with mouse and touch on screens bigger than 7-8inches. No phone version. 

## (6) testing framework
I think I want to use jenkins as a CI tool, selenium which is mentioned on the course web-page has a plugin for this. Will take a look at selenium. I dont know to what degree I will be using testing frameworks atm since I will probably have to redo many things and reiterate my ideas a ton. So I dont want to do too many tests at the begining. Once my core sturcture of the project is done I will take a greater look at this. From that point forward I would like to work according to TDD and hence do a lot of tests. But again, at the start I wont know what my requirements will be really so we will see what I end up with.

I want to be able to move elements around in the page, so jQueryUI might be what I will use to be able to do this.

