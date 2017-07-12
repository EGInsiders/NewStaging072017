# Test set up of Scholarship America as a Demo Team

## Create Partner Team for Scholarship America

### Launch Partner Team

When I click on admin
And “Create Partner Team”
Then I am taken to the wizard for launching a Partner Team

## Configure Partner Team

### Team Title

When I enter in the team's title
And click “Next”
Then I am taken to “Path”

#/##

### Path Settings

When I set the minimum word requirement at {Medium}
And set path subscription as {enabled}
And set the Path as {Core Learning}
And set Max new activities per day as {1}
And Max Activities for Subscription Period {20}
And Subscription Start Date as {July 1, 2016}
And Subscription End Date as {June 30, 2016}
And Literacy Tools as {off}
And Audio Reader as {off}
And I click {Save}
Then I am taken to the Invite page
And the system responds, “Path settings have been saved.”

### #/##

### Invite

When I enter an email address {32bpwr3+[SACoach@gmail.com](mailto:SACoach@gmail.com)}
And enter a custom message of {Blank}
And click “Send Invite”
Then I am taken to the team {Scholarship America}
And the system responds, “An invitation email was sent to 32bpwr3+SACoach@gmail.com. Once they accept their invitation they will be able to begin the team setup process.”

#/##

## Lead Admin Coach Joins the Team

### Accept invitation

When I click on {Launch Team}
Then I am taken to the coach Decision Tree

#/##

### Decision Tree

When I click “No, Join”
Then I am taken to the registration form

#/##

### Registration

When I enter First Name {Aubrey}
And Last Name {Pradeep}
And {Scholarship America}
And Mobile Phone
And Street
And City
And State
And Zip Code
And Country
And Email {32bpwr3+[SACoach@gmail.com](mailto:SACoach@gmail.com)}
And Confirm Email {32bpwr3+[SACoach@gmail.com](mailto:SACoach@gmail.com)}
And Password {PW}
And Confirm Password {PW}
And the type of organization {school}
And the number of students served {1000}
And click “Join”

## Create a Demo Group with individualized path settings

### Create a “Demo Group”

When I click “Create Group”
Then the group title field appears

#/##

When I enter the group name {Demo Group}
And click “Save”
Then the Group is created
and the system responds “Successfully created new group”
And the group is displayed under “My Groups”

## Adjust Group path settings

### Open up Group Path settings

Given that I am on the team settings page
When I click on the button “Manage Path Settings Per Team Group”
Then I am taken to the Team Group Chooser page

#/##

### Adjust the path settings for the Demo Group

When I set the minimum word requirement at {Medium}
And set path subscription as {enabled}
And set the Path as {Demo Path}
And set Max new activities per day as {1}
And Max Activities for Subscription Period {5}
And Subscription Start Date as {July 1, 2016}
And Subscription End Date as {June 30, 2016}
And Literacy Tools as {off}
And Audio Reader as {off}
And I click {Save}
Then I am taken to the Invite page
And the system responds, “PPath settings have been saved for the group. Settings were applied to all current group members.”
And I am taken back to the Demo Group Path Settings page

# Invite Demo Users to Group

## Obtain Invite Code

When I click on “Invite Members” next to {Demo Group}
Then I am taken to the invitation page for {Demo Group}

#/##

### Copy JOin URL

When I click on Copy Address under the “Online” box
Then the system responds, “Join url for group copied to clipboard” {https://staging.eduguide.org/join/?invitationCode=1906666}

#/##

# Demo User Joins the team/Group

## Decision Tree

When I click on “No, Join”
Then i am taken to the registration form

### Registering for a new Account

When I enter First Name {Simon}
And Last Name {Gaios}
And Email {32bpwr3+[SACoach@gmail.com](mailto:SACoach@gmail.com)}
And Confirm Email {32bpwr3+[SACoach@gmail.com](mailto:SACoach@gmail.com)}
And Password {PW}
And Confirm Password {PW}
And click “Join”
Then the system responds “Congratulations! You have Joined the team”
and I am prompted for my personal avatar

#/##

Given that the demo group has been set up with different path settings

## Send invitation to Coach Recruit

Given that I am on the coach invite page

When I enter in an email address {32bpwr3+[admincoach06082017@gmail.com](mailto:admincoach06082017@gmail.com)}
And select a coach role {Admin}
And click “Send Invite”
Then the Invitation Modal appears

#/##

When I click “Send Invite”
Then the modal clears
and the system responds, “Your coach invitations have been processed and necessary emails sent out.”
and the invitation is sent out

#/##

### Accept invitation

When I click on {Join Scholarship America Now, http://email.eduguide.org/wf/click?upn=3Z9rd2megDUiG-2Bhv-2FkwvPUsKAcD3aiaRPduQuK8H6dRGab-2B1tzHTgBPCJhgerRw1oNqA26wcjJI5r9-2BVAYUkCcNrjd-2FW-2BZjXp0ykw9Fwp7ypbtZOFhyKjr7MQ9Qkmv8P_H4TL-2F0jZH4aW-2FKw5U95YCiNs8-2F1oBT39zsfqLJuX5oY-2BdrDpKbLNg2vpA-2BxETj3wXSNOX07lomNdQyQwZaSkhsXUKWAvR9GMT33vR8YfR8HVOhB63on0UaEr39JZULFLel1tk0d6SIgLA2xZBdb1tYrFJcCqSSNJtkS7REQyuwTzkO8wADvcEagI98IQzZoi8LoAkwWtiXBLPdQfJOqyDQ-3D-3D}
Then I am taken to the coach Decision Tree

#/##

### Decision Tree

When I click “No, Join”
Then I am taken to the registration form

#/##

### Registration

When I enter First Name {Pantheras}
And Last Name {Johano}
And Mobile Phone
And Street
And City
And State
And Zip Code
And Country
And Email {32bpwr3+[SACoach@gmail.com](mailto:SACoach@gmail.com)}
And Confirm Email {32bpwr3+[SACoach@gmail.com](mailto:SACoach@gmail.com)}
And Password {PW}
And Confirm Password {PW}
And click “Join”
Then I am taken to the custom avatar prompt
And I am subscribed to the core learning path
