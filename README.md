## Covid API

## Problem statement

COVID-19 is a disease that spreads between people, mainly when an infected person comes into close contact with another person.
Within South Africa, the government are the ones that currently possess all the information and stats about infected indivduals and the hotspots that are at the highest risk.
So if you are surrounded by many infected people then you are in high risk of getting Covid. Therefore, being surrounded by many infected invididuals, or traveling around hotspot areas puts one at a higher risk to contract this virus.

It would be beneficial if there were an easier way for families and friends to update and notify each other when there has been a newly infected person around your area or in your familty, as well as if  you have been in close contact with an individual who has tested positivd.

Messaging Apps like WhatsApp can be used but they were not designed for this problem and its so limited.Messaging applications such as WhatsApp could provide a solution, however they have limited functionality for this problem in particular as the system isn't specifically designed for this usecase.

## Proposed Solution

Create API that allow person to add a message if he/she tested positive or was in contact with someone who did. The message must have list of numbers/emails of people that were close contact.
The API sent message to all of them and advise each to add their own messages with people had close contact with soon after. The process goes on.

By doing this, we will have a network of friends/families trying to protect each other by ensuring that self isolation is done early.

Any person can also get a stat about the number of infected people on their area/village.

## draft Design

People will be identified by their phone-number or email.

