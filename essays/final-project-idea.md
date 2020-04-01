---
layout: essay
type: essay
title: "Final Project Idea"
date: 2020-03-31
labels:
  - Software Engineering
  - Meteor
---

###Overview
*The problem:* 
<br/>The notice boards on campus are a great way to advertise events and opportunities both on- and off-campus. Many students use these notice boards to advertise tutoring services, concerts, classes, and more. However, the issue with the notice boards on campus is that they’re typically very cluttered and messy. There’s only a limited amount of space but there are times where multiples of the same flyer have been stapled to the same board, taking up space and burying other flyers. 

*The solution:*
<br/> Manoa Board is a virtual notice board where students can login, publish, and view virtual flyers.

###Approach
Manoa Board has two user roles: regular users and admins. Every user can view and publish flyers to the board. They also can edit and remove the flyers they published. Admins supervise the board. They have the additional ability to remove any flyer that's inappropriate or that violates campus guidelines. Non-users can view the Manoa Board just the same, but they will not have access to any other additional feature. 

Users can publish a flyer (pdf or image format) with a title, a description, tags, date of expiration (if there is one), and/or date of event (if there is one). 

By default, flyers on the Manoa Board are sorted by the date it’s created where newer flyers will take precedence at the top and older flyers are pushed to the bottom. However, there are options to sort the flyers by title, date of expiration, and date of event. Flyers can also be filtered by tags or specific keywords using a search bar. 

###Mockup Pages
Possible mockup pages may include:
<ul>
    <li>Landing page (The Manoa Board)</li>
    <li>User home page</li>
    <li>Admin home page</li>
    <li>Publish flyer page</li>
    <li>Edit flyer page</li>
    <li>Search page</li>
</ul>

###Use Case Ideas
<ul>
    <li>New user goes to the landing page. They immediately can view the board, however they cannot add flyers. New user logs in, gets the user home page where they can now both view and publish flyers. </li>
    <li>Admin goes to the landing page, logs in, gets the admin home page, deletes a flyer.</li>
    <li>Non-user browses the notice board without restriction. 
        User goes to the landing page, logs in, browses the board, goes to the add flyer page, uploads a pdf or image of a flyer, fills out the required fields (title, description, tags, etc…), then publishes their flyer. 
</li>
</ul>


###Beyond the Basics
Ideas for more advanced features:
<ul>
  <li>Favorites page where users can favorite a flyer for later viewing.
    <ul>
      <li>ie) If there’s a flyer for a concert that piqued their interest.</li>
    </ul>
  </li>
  <li>Follow system where users can follow tags
    <ul>
        <li>ie) music, performances, clubs, fundraising, etc… </li>
    </ul>
  </li>
  <li>Notification system that may notify a user when:
  <ul>
    <li>flyers (favorite or all) are expiring</li>
    <li>it’s the day of event for a flyer (favorite or all)</li>
    <li>flyers with followed tags are published, edited, and/or removed</li>
  </ul>
  </li>
  <li>Comment section</li>
</ul>

