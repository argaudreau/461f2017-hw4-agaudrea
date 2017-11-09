# Adam Gaudreau's GUI1 HW4
This repository contains my homework 4 submission.

## Purpose
The goal of this assignment is to build a dynamic table based off user input. In this case, the user will enter
the MSRP and MPG for a number of vehicles of their choosing. They will also enter the current gas price, so the
price of the car plus the price of gas for 100,000 miles can be calculated. For some, this number can be useful
to someone making a choice.

## "Impress Me"
For the impress me section, I did a few things:
1. Logically separate each step so the user's page is less cluttered.
2. Animated the transition from one step to another (with a progress bar).
3. Added simple validation so the user can only continue to the next step if the inputs are valid (NOT JQuery Validation).
4. It's responsive. (Looks good on mobile too, except for the table maybe)
This is still a single page web application, but it is logically separated into 3 steps. This makes it so for commonly
used, non-mobile pages, do not have to scroll. The less the user needs to manipulate the page, the quicker their visit
will be. If the user inputs something invalid, they will not be allowed to conitnue, thus making it impossible for the
table to display corrupted data. With the help of Bootstrap, it is also fully responsive, so viewing from a mobile device
looks good too. The only place it doesn't is at the table, but tables like that do not have a reasonable purpose on mobile
devices.
