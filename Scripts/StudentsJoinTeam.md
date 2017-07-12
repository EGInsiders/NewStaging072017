---
title: # New Coach invites students to the team
layout: post
author: eduguidepfl
permalink: /#-new-coach-invites-students-to-the-team/
source-id: 1DFvJMsCnTFUaa-IkbmY0aWvp_ldVU96KxJoLaTLWbTA
published: true
---
# New Coach invites students to the team

## Send invitation to Recruit Coach as {Team Captain}

Given that I am logged in as a coach

When I click on the command menu

And "coaches"

Then I am taken to the Invite Coaches page

#/##

## Send Coach invitation

Given that I am on the Coaches invite page

When I enter in an email address [{32bpwr3+coach06232017@gmail.com](mailto:{32bpwr3+coach06232017@gmail.com))

And click "Support"

And click "Send Invite"

Then the Send Invitation Modal appears

#/##

## Customize message and confirm send

When I enter a custom message {Please Join my team}

Then the Personalize invitation modal appears

### Send Invitation

When I click "Send Invite"

Then the modal disappears

And  the system responds, "Your coach invitations have been processed and necessary emails sent out."

And I'm taken back to the Manage Team Coaches page

#/##

## Accept Support Coach Invitation

### Respond to invitation in inbox

When I click on "Join <Team Name> Now"

Then I am taken to the site

#/##

## Register for an account

### Decision Tree

When I click "No, Join"

Then I am taken to the registration form

#/##

### Registration Form

When I enter a first name

And a last name

And a job title

And a mobile phone

And a join code

And an email address

And confirm email address

And password

And confirm password

And click "Join"

Then my account is created

And I am promoted to support coach

And I am subscribed to the personal path

And I am added to the team

And I am taken into my path

#/##

### Upload custom avatar

When I click on "Find New Image"

Then a file chooser opens up

And I can select an image

And my selected image is shown as a preview in the space for my avatar

#/##

### Advancing to next screen

When I click on the right hand arrow

Then I am taken to my path

#/##

## Navigate to Metrics Page

![image alt text]({{ site.url }}/public/MmM261cNVxMCY4sefIiwaQ_img_0.png)

When I click on the navigation menu

And click on "Metrics"

Then I'm taken to the Metrics page

#/##

![image alt text]({{ site.url }}/public/MmM261cNVxMCY4sefIiwaQ_img_1.png)

## Adding Students

### Obtaining Join Code for Group

Given that I am on the Group Management Page

When I click on "Invite Members" next to a group's title {Minbari}

Then I am taken to the group's invite page

### Copy join code

Given that I am on the group invite page

When I click on "copy Address"

Then the system responds, "Join url for group copied to clipboard"

## Invite Students to the team

When I go to the invite URL {[https://assets.ford.eduguide.org/join/?invitationCode=3883666](https://assets.ford.eduguide.org/join/?invitationCode=3883666)}

And click "copy"

Then I can copy the URL and share it with my students

#/##

## Joining the team as a student

When I paste the join URL into my address bar

Then I am taken to the decision tree

## Responding to Decision Tree

When I answer, "No, Join"

Then I am taken to the registration form

## Completing registration form for Students

Given that I am on the registration form

When I enter First Name

And Last name

And email address

And confirm email address

And password

And confirm password

And click "Submit"

Then I am prompted to customize my avatar

#/##

