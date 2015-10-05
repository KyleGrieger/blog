---
layout: post
title: "Victory Lap"
description: "The story of Victory Lap"
category: Development
tags: [EatStreet, AngularJS, New York, GBeta, Facebook]
---
{% include JB/setup %}

#Victory Lap

###Intro
It all started when I was anxiously scrolling through Facebook as many juniors in college do when they are bored. I was about to start working at a new tech startup in Madison after I had been laid off from my previous internship at [EatStreet](https://eatstreet.com/). I got a message from someone who I had just recently met in a computer science class, John Meurer.  The message read:

    Hey Kyle, 
    
    How did your 699 project presentation go? 
    
    If you have the time, I'd like to talk to you about a code related job. I remember that you were a very proficient coder, from the water filter tracking application you developed.
    
    Let me know if you have time to discuss.
    
    John

Instinct would naturally pass this off as some type of spam but I decided to respond.  The conversation quickly shifted towards an idea for a new mobile app.  John was pretty vague at first but I decided to go over to his apartment and meet up with him later that week to learn more.  When I first saw the app I was surprised at how much progress John had made by himself. As he explained to me the concept I immediately though "hey, this could be it." I had been looking for a project outside of school to really sink my teeth into and this seemed to be my shot.  Our first session didn't yield any major development breakthrough but I quickly became familiar with the code base and after working with [AngularJS](https://angularjs.org/) at my internship I soon figured out how the app was really working under the hood, and so the development persisted on.  

###Development
John and I are both idealistic developers.  We were able to come up with ideas for new features and how things should work at a high level and not worry too much about the difficulty of the implementation.  We were both confident we could figure it out.  Or at least John was more than I.  I could tell in the beginning from my slow start that John probably thought I was all talk.  I boasted about my experience at startups and working with a lean but agile development team to get the job done but I had yet to step in and make some significant contributions to the app.  One of my first contributions was to suggest using the version control software [git](https://git-scm.com/).  This seemingly trivial decision was key to our later success but also contributed to some headaches along the way.  Another thing I suggested was adding google analytics to the app so we could track user behavior.  Next was the map.  We had decided that there should be a map that should show where clusters of students are in the United States but we went through many styling iterations before coming to a heat map using google maps javascript API.  The most difficult challenges came with the Facebook integration.  Since the app was a hybrid using both web and native languages we had to develop a solution that would appease Facebook's APIs.  We found a [Cordova](https://cordova.apache.org/) plugin and somehow added Facebook login.
John and I worked through the school year meeting up occasionally and making as much progress as we could even if it meant skipping a week of classes. We had Brett come on to help the development efforts.  He made some significant improvements to the app by adding messaging and fixing countless bugs.  Later that summer Pat was added to the team.  At this point I was organizing weekly engineering meetings with John listening in from New York and the rest of the team in Madison.  We would set dates for deliverables and define requirements even if it meant getting into a little bit of a screaming match on [Google Hangouts](https://hangouts.google.com/).  Development exploded.  We fixed significant bugs added numerous features and redesigned the app in a matter of weeks.  

### New York
We had a date set for the end of the summer to release so students coming back from break would have free time to check out the app.  The week before release I flew to New York to meet up with John to add in some last minute features.  When I arrived John and I both knew it was crunch time.  Since John was working at Goldman Sachs during the day I was tasked with getting facebook approval, fixing bugs and updating styling.  Some of the work was tedious but it had to get done.  When John got back from Goldman, he dove right into work on Victory Lap.  We made a lot of progress the first couple of days so on on the third day we took a break and went out to the bars.  I'll never forget walking home drunk with John at 3 in the morning only to turn on our laptops and start coding.  That weekend when John didn't have to go to his internship we decided to head out into the city and find a coffee shop to get some work done.  Our first stop was central park.  We wondered around for an hour or so trying to find reliable Wi-Fi with little avail.  Finally we wound up at a Starbucks on the upper east side and got to work.  I remember getting so frustrated trying to get the google maps api to work. I finally managed to rig it up and when the final product was done we were amazed at what we were able to do.  We had a fully functional forum with location and metadata filtering all integrated with google maps to give the user an exact look at what posts were around them.  As I sat exhausted in a chair waiting to board my flight home at La Guardia I remember thinking how I had done so much coding in those few days in New York I never wanted to see another line of javascript again.

###Setback
While all this was going on, John and I were regularly on conference calls with the business team for the app.  They made marketing, finance and product design decisions that kept the whole thing rolling, but after some critical feedback from beta testing the team had realized that some significant reorganization had to take place within the app. We decided to push the release back to October.  John and I were frustrated, but understanding.  We would just have to be patient and plan carefully. At this point, Brett who had been working on the app for a while resigned and moved on to other opportunities.  When Pat, John and I were all back from our summer adventures we went to the Monona terrace and grabbed a couple pitchers of beer and brainstormed about the future of the app and what we might want to work on next. John had talked to us about re defining our roles and what the next steps should be for releasing the damn thing.  Pat would be Lead Front End Engineer and I would be Lead Platform Engineer.  After all I was better at optimizing the build processes and addressing navigation and functionality glitches while CSS and SASS often times made me want to throw my laptop across the room. Pat was talented at design and styling and always had good insight on how things should be laid out within the app.   

### Lead-Up
The next school semester started and at this point our engineering team was taking an entrepreneurship class together where we would be able to plan how we would grow the app into something that had a real product market fit. As our engineering team shifted their focus away from development and on to planning for the future and the impending release we were able to schedule an interview with a local startup accelerator in Madison, [GBeta](http://www.gbetawisconsin.com/).  The meeting went well and I knew a few of the people working there through working at other startups in the area. Now with the release a few days away I figured I might as well recount all that has happened since the day I got a random Facebook message from a guy I barely knew.


