---
title: # Grouip Creation and Deletion
layout: post
author: eduguidepfl
permalink: /#-grouip-creation-and-deletion/
source-id: 16mEEDOR33RJZT6f9tTt2Jmg5u3jdEkaJi0Kuwuz6MEg
published: true
---
# Group Creation and Deletion

## Group Creation

### Initiate Group Creation

When I click on "Create Group"

Then the Group Name field appears

#/##

### Entering Group Name

When I enter a group name into the group name field

And click "Save"

Then the group is created

And is displayed in the Pending Groups section of the page

#/##

### Remove a Group

#### Navigate to Group invitations page

Given that I am on the Group Management page

When I click on "Invite Members"

Then I am taken to the group invitation page

#/##

#### Navigate to Edit Group Page

Given that I am on the Group Invitation page

When I click on "View List"

Then I am taken to the Group Edit page

#/##

#### Delete Pending Group

Given that I am on the group edit page

And I am an Admin Coach or higher

When I click "delete"

Then the system responds, "Are you sure? / You're about to do something you might not be able to undo. / Are you sure you want to do this?"

#### Confirm deletion

When I click on "OK"

Then I am taken back to the group management page

And the system responds, "Delete Me removed"

And the group has been removed from the list

