# Project Proposal
CampusCrowd

### What and why?

CampusCrowd is a mobile web app that shows (picture a heatmap) NYU students how busy campus study spaces and dining halls are right now, before they walk there. Every student knows the midterms-week routine: you go to Bobst, ride the elevator 3 times, find every floor fully occupied, try Stern, find the same, and lose thirty-five minutes before opening a textbook. The information isn't hard to know — dozens of students are standing in those rooms and can see exactly how full they are — it just isn't shared. CampusCrowd captures what students already know and gives it to the next person deciding where to go.

### For whom?

The initial users are NYU undergraduates who study on campus and eat in dining halls on campus. It could later be extended to other schools

### How?

There are 2 ways this could be implemented.
1. Students report what they see when they're physically at a location, one tap on a four-point scale, designed to be done in under five seconds while walking through a door.  
2. NYU ID card taps or WiFi device counts, but both are institutional data held by Public Safety and NYU IT, which may or may not be obtainable. 

Both methods allow students to see what is busy (say a list of nearby locations ordered by walking distance, each showing a crowd and noise level (quiet, moderate, busy, packed)). It also allows them to plan ahead because with the use of data and pattern recognition the app will show typical patterms (e.g. Bobst floor 5 fills by 7pm but is emptier at 11pm)

### Scope

The proposal is neither too easy nor too ambitions for a group of approximately 4 - 6 programmers to undertake in one semester. The core build is a mobile-first web app with three screens, a database of locations and timestamped reports, and aggregation logic turning individual reports into a current reading and a historical pattern.
