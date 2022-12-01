---
layout: essay
type: essay
title: The beginning of the end, sort of
# All dates must be YYYY-MM-DD format!
date: 2022-11-30
labels:
- Software Engineering
- Learning
- MeteorJs
- ReactJs
- Project Management
---

## Overview 
This semester I had an opportunity to work with the DOE for my Software Engineering II course in order to create a bill tracker application 
that would allow DOE employees to easily manage thousands of bills that they get. The code that we were building for this project would 
help bills that they wouldn't be able to get to not be lost in the long and tedious process of creating testimonies for 
bills. Needless to say the code that we would write for this project would directly benefit not just the DOE employees,
but the Hawaii population as a whole. I learned a lot about the process of creating testimonies for a bill as well as how bills 
are handled in the DOE. 

## Client vs Programmer

I initially had no clue how the legislature handled the process of a bill or what they even wanted from our application. The first 2 or 3
weeks of the semester was figuring out what the DOE really wanted us to do and trying to understand the entire process of a bill. A lot of 
communication with the DOE employees and our professor was being exchanged in order to get the core idea of the application. After a 
few weeks of discussing with the DOE employees and our professor our team concluded that what the DOE wanted was not necessarily a bill tracker 
that would track how far a bill is along the tiring process of a bill going into law, they wanted a way to track the process of a testimony that was being written internally by the DOE staff. 
Maybe a more apt name would have been testimony manager?

This was definitely a valuable skill to have as a software engineer. Although it made the initial process of creating our application take much
longer than it needed to I like to take a more positive learning experience from this. Sometimes you and your client and not on the same page,
and it is important for both you as an engineer and them as a client to work together to clear up any misunderstandings before production begins. 
The last thing I wanted was to build a full-fledged application that did not match the customers needs. 

## As small as managing can get

I think that one of the most difficult things for me this semester was learning how to manage a team. Learning to adapt to the current state of the project every
milestone was something that I had never thought I would be doing. I tried to guide our team by delegating tasks that they would succeed in given their 
skills and interest, and I also managed them by having meetings every tuesday and thursday where we discussed how everyone was doing on their tasks. In
addition, I would create tasks for our team and meet every 4 weeks with our customer to discuss any changes to our current project. 

## Everything is going to be fine.

A part of this project taught me the value of component design in ReactJs. I was able to make one component like my search bar and use it throughout the rest of my application
with little trouble. This saved a lot of time on my end as I needed to write fewer lines of code in order to implement a similar feature throughout our application.

One of the hardest tasks was trying to filter out a large amount of data efficiently. I was able to do this with ReactJs by creating a useState() that tracked the state of a users selected filters and matching those selected filter
data with the ones on the bill, easy-peasy sort of. The real challenge came with using Reacts useEffect(). I had only used it slightly in the past and never had
troubled with it, however, in this project when I was trying to get user data to load preferred with the useEffect() I was unable to do so as it was loading the page
in a non filtered state. Putting my googlefu to the test I was able to find the solution by adding a dependency to the useEffect() which allowed me to render the filtered
data whenever the state of the users selected data would change. This allowed for my app to quickly filter for bills based on a users filter. This filter component was
used throughout our application and was easily one of the best time commitments for our project.

Another task I was proud of was creating the workflow from beginning of it reaching the secretary to finally sending it back to the secretary
for review by the final approver. This was a difficult task as it really put my business as well as my technical logic to the test. I needed to fully understand how the workflow
and approval process is conducted. Furthermore, I needed to understand how to design the page and design the database to go along with the application. I wanted a table which
approvers, writers, and secretary's could easily manage the tasks assigned to them. I also needed approvers to be able to comment on a writers draft as well as to keep track of
the approving and rejecting of a bill by an approver. In the end the database kept track of the entire approval process while the UI allowed approvers to approve and reject testimonies
with a simple click of a button and to comment on testimonies easily and efficiently.


## Not yet a programmer Not yet a software engineer
I don't think being a software engineer is all about code and writing efficient and fast algorithms, as much as I constantly try and implement
these elegant solutions to my own code. I think that being a team member and knowing how to communicate and receive and give constructive criticism
is an important part of being a software engineer. As much as people like to think that large companies like Google and Facebook were created 
by one individual person often times it is an entire team working on a product together to push a completed project. I was able to learn a lot about 
what it's like working with a large team of 9 people and how merge conflicts, bugs, and reading other peoples code is a frustrating yet beautiful process.
I am far from being a 10x developer who can consistently write elegant and efficient code, but I think that this project has definitely put me on the right path
and creating this bill tracker program has given me an opportunity to work with a real client and communicating and managing a fairly large team. 

## To track or not to track
In the end we were able to push a mostly completed project. There are still some things that we were not able to fully accomplish, such as having a feature
to track the different versions of a bill, a more elegant looking UI, and a method for writers to see the comments left by approvers. Unfortunately, these tasks
were either not completed due to time constraints with the project, however, I believe that the ideas that we put forth for this project were extremely valuable. In
addition, I believe that I was able to become a better programmer and leader. Going forward I plan to take this experience with me and use the mistakes and success
here in this course at my new position as a software engineer intern at Hawaiian Airlines as well as my internship as a software engineer at Eworld enterprises.

Source: <a href="https://github.com/a-doe-bo/hi-doe-bill-tracker">Github Link</a>




