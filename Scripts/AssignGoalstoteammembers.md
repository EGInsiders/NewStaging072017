---
title: Assign Goal to team member
layout: post
author: eduguidepfl
permalink: /assign-goal-to-team-member/
source-id: 1xcZWNC1CfYwGQRCGzTSQmQEkhXt3ALKNdf7DnEaUeP4
published: true
---
# Start a new Goal

Given that I am on the team goal page

When I click on "New Goal"

Then i am taken to the new goal form

###

# Create a Goal

Given that I am on the goal information page

When I enter Goal title

And Goal Notes

And a Start Date

And a Due Date

And add an Attachment

And click "next"

Then I am taken to the "Steps" page

###

# Create a new Step

Given that I am on the "Goal Steps" Page

And that I am creating a new team goal

###

# Starting a new step

When I click "Add Step"

Then a create new step form appears

###

#Configuring the new step

Given that I have clicked "Add Step"

Then I enter in a step name

And step notes

And a Start Date

And a Due Date

And set the Reminder as "1 Day Before"

And attach a resource

And click "done"

Then the step is saved

and the step is displayed on the new step page

###

# Set Goal Settings

Given that I am viewing the Goal Settings Page

When I select "Members can edit due dates"

And "Members can remove steps?"

And "Members can add steps?"

And set status of "Active"

And click "Finish"

Then I am taken to the goal detail page

# Assign a Goal to a team member

# Initiate Assign Goal

When I click on the command menu

And click on "Assign Goal to Members"

Then I am taken to the "Assign Goal" page

###

# Select Members to assign the goal to

When I click on "Add Members"

Then the Select Members modal appears

###

# Select Members from Modal

When I click on "Assign to Goal" next to a target member

Then the member becomes selected

And "Assign to Goal" disappears

###

# Closing Select Members Modal

When I click on the "X"

Then the modal disappears

###

# Submit assigned goal to members

Given that I've selected member(s) from the team

and entered a custom message

And click "Assign Goal"

Then I am taken back to the goal detail page

And the assigned member(s) are shown in the list of adoptees

###

# Set Goal Settings

Given that I am viewing the Goal Settings Page

When I change the status of "active" to "draft"

Then I am taken to the "Update Team Member Goals"

And Not yet adopted the goal is checked

And not yet completed the goal is checked

And completed the goal (if you've added steps, your changes will make their goal incomplete)

And override user edits is unchecked

and click "confirm changes"

Then I am taken to the Goal Detail Page

