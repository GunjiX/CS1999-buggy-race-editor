# Phase 3: Testing

##### This file gives a brief overview of how I tested certain previous parts of the project I have completed or how I would test them if I had got them running

#### PHASE 1:

**1-ADD:**

To test add, I tried out a variety of values in the buggy-form sheet, and when submitting them I checked that they were properly saved and stored in the database. I checked this by opening the buggy tab which should have all the recently inputted and stored values in a table.

**1-VALID:**

To test my validation was working I tried typing in different types of items in the input box, some examples are (banana, 4?, 12, F9F9). In these tests only the value 12 was accepted and stored, showing that the validation was working correctly.

#### PHASE 2:

**2-EDIT:**

When edit was working, tot test it I had to input some valid values onto the database and next time I opened the form 'Make Buggy' the values that had previously been entered showed up in their respective fields.

**2-COST:**

To test cost was working I added a cost section to the table and tried out a few different number of 'hamster boosters' and checked that the total was changing and that if I divided the total cost by the number of buggies, my answer should be 5 (5 was the cost set for a hamster wheel).

**2-RULES:**

I tested rules similarly to the way I tested validation. To test the couple of rules I had added (wheels must be even and must be more than 3), I tried inputting 3,4,5 and 6. When I input these values the number 3 came back with a message saying it must be more than 3, 5 came back with a message saying it should be even, and 4 and 6 were logged in the database with no problem.

#### PHASE 3:

**3-AUTOFILL:**

I did not attemp phase 3 but to test if it was working, the method I would have used would be to try create a new buggy with the auto filled results, and when attempting to enter it into a race, if it is working correctly ,no matter how many times i create a new buggy, it should work and be accepted into the race.

**3-MULTI:**

To test what I achieved in 3-MULTI, I filled in a few new buggy forms and made sure they were all showing up in the show buggies tab with the right values and ids. To test the next section which didn't work involving editing buggies, I would use the edit button and attemp to change and save new values in each section multiple times to make sure everything runs smoothly.

**3-DEL:**

As I did not complete 3-MULTI, I did not start 3-DEL, but as a means of testing it would be best to make some new buggies and attempt to delete them using a delete button, and check if they have been removed form the buggies grid. It would then be worth checking that new buggies can be added unaffected.

**3-FLAG:**

I was unable to fully complete flag, but tot test it would be a matter of trying out a variety of different colour codes and pattern options and then checking that they display correclty on the buggies page.



**NOTES**

Whilst Validation and Rules weren't working I used a print statement to make sure part of my code had been interpretted correctly and was working to some extent.