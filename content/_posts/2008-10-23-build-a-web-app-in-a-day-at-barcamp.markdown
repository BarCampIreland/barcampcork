---
author: conor
date: 2008-10-23 08:52:12+00:00
draft: false
title: '"Build A Web-App in a Day" at BarCamp'
type: post
url: /2008/10/23/build-a-web-app-in-a-day-at-barcamp/
categories:
- Announcements
tags:
- app-in-a-day
- barcamp
- barcampcork
---

A few of us have been bouncing around the idea of building a web application in one day for the past few months. BarCamp seems like the ideal opportunity to try this. From the sign-up comments, it looks like plenty of people are interested in taking part. Unlike the impromptu style of the rest of the day, this one does require quite a bit of up-front preparation if it is to succeed.

The current idea is to build a "Carbon Footprint Calculator for Meetings". We are also talking to a few people about integrating energy meters into this app but only if we have the time and expertise on hand.

As an experiment, we are looking at building the App in the style of a movie. The idea here is that small scale web-app development might be ideally suited to the model of creating dynamic teams of freelancers who come together for a project and disperse afterwards. The "Producer" is the commercial person, the "Director" is the Project Manager, the "Script" is the Spec etc etc. It could also be a bit of fun :-)

Phoebe Bright has put together the following thoughts on the app. Please give lots and lots of feedback in the comments so we can ensure success on the day.

**Scene 1**
A group meets for a one off.  The secretary to the meeting prepares the footprint ahead of time, After entering some details of the venue and all attendees can in a batch.  He prints of a single page report to be handed out at the meeting to show how much each attendee can pay to have their footprint offset.

**Scene 2**
An environmental group meet once a month and want to 'walk the talk' in terms of reducing their carbon footprint.  Each member of the group registers with the system and enters where they came from and how they travelled.  After adding the meeting location the system calculates the carbon footprint of the meeting including travel, materials (paper, refreshments) and room use (electricity, heating etc.).  The amount can be tracked for each meeting so the group know if they are reducing their footprint or not.  Option also available for those attending remotely with small addition for electricity.  The Group prints out a graph and/or chart

**Scene 3**
A registered user uses the system to record all their offsite meetings but in this mode, the system does not include an element for the venue, just their travel.

**Scene 4**
A conference sets up the venue data and then at registration, asks people to add their journey details.  Their journey foot print and cost to offset is displayed immediately and they are offered the option to offset their journey (electornic or cash tin).  If they supply their email, a report will be emailed to them with how the journey was calculated and cost of alternative transport methods.

**Scene 5**
When planning a meeting, the system is used to calculate the relative costs of different forms of transport.  Is is more efficient to car share with four people or all drive to the train station and go by train and tax the other end?

**Scene 6**
A company must include carbon use as part of the annual reporting requirements.  At the end of the year, all offsite meeting data is summarised for the company by month and department.

**Requirements:**

_MUST_
- come up with a good name
- record details of the location of the meeting
- calculate travel element for each person
- calculate venue element for whole meeting and (optionally) apportion to each attendee
- prepares report for a single meeting or a series of meetings
- use http://trac.amee.cc for carbon calculation
- be developed as an api

_SHOULD_
- save multiple possible locations for each user - may have come from home or work
- interface with offsetting system(s) to allow offset

_COULD_
- link in with Upcoming etc. and provide car pooling information
- link in with calendaring systems to prompt to use system when going to offsite meetings

**Pre-Production**

Get a domain name and register - or use someones existing one.

Agree language and framework. Currently looking at Django

Get space on a server - Do we need VPS to deploy?

Version control

Local dev server?

OpenSource presumably.

Licence? GPL?

**Cast**
- programmer(s) in chosen language
- designer
- tester(s)
????
