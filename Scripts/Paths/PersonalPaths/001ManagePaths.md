# Manage Paths

## Create a Path

### Navigate to Path management

When I click on "Admin"
And then click on "Manage MyPath"
Then I am taken to the Path Management Page

###

### Create a new Path

When I click on "Add New Path"
Then I am taken to a new Path form

###

### Configure a New Path

When I enter a Path name into the field {Digital Ocean Test Path}
And click "Save"
Then I am taken to the new path's activity management dashboard

###

### Initiating Activity Creation

When I click "Add New Activity"
Then I am taken to a form for a new Activity

###

#### Configuring new Activity Title Page

When I enter an activity's title
and select a user type {Student}
and select a status {active}
and click "Save"
Then I'm returned to the activity dashboard
And the system responds, "Path activity has been saved"
And the button "Add Step" Appears

###

#### Initiate creating a New Step
When I click on "Add Step"
Then I am taken to a New Step Form

##### Creating a New Text Step
When I select Step Type {Slide}
And enter in content
And enter in an amount for Points {10}
And click "Save"
Then I am taken back to the Activity dashboard

###

##### Creating a new Comment Step

When I select Step Type {Comment}
And enter in content
And enter in an amount for Points {10}
And a low comment length requirement {5}
And a Medium comment length requirement {10}
And a High comment length requirement {15}
And click "Save"
Then I am taken back to the Activity dashboard

###

##### Creating a New Attachment Step

When I select Step Type {Attachment}
And enter in content
And enter in an amount for Points {10}
And a low comment length requirement {5}
And a Medium comment length requirement {10}
And a High comment length requirement {15}
And Click "Add Attachment" {camera}
And click "Save"
Then I am taken back to the Activity dashboard

###

##### Creating a Comment and Attachment Step

When I select Step Type {Attachment}
And enter in content
And enter in an amount for Points {10}
And a low comment length requirement {5}
And a Medium comment length requirement {10}
And a High comment length requirement {15}
And Click "Add Attachment" {camera}
And click "Save"
Then I am taken back to the Activity dashboard

##### Creating an Essay type Step

When I select Step Type {Attachment}
And enter in content
And enter in an amount for Points {10}
And a low comment length requirement {5}
And a Medium comment length requirement {10}
And a High comment length requirement {15}
And click "Save"
Then I am taken back to the Activity dashboard

###

#### Create an Adopt a Goal Step

##### Create an Admin Goal

Creating an Admin Goal and displaying it in the Path
 
##### Create a new admin goal.
The link is found under the admin menu. When saving, make sure the Status is Active and the box labelled “Expose to MyPath?” is checked.
Once you have done this, you will land on the goal view page - copy that URL and save it for later. {https://assets.ford.eduguide.org/goal/1930934/}
##### Adopt this new goal to a team.
The page you end up on from step 1 has a link at the top “Adopt Goal For Team”
Click that, select a team from the pulldown and click the button - this will load the team adopt form.
##### Fill out more info on the team goal.
This allows you to do more than admin goals, so you can pick dates, recurring steps, etc.
On the settings page, be sure that none of the checkboxes are checked and that Status is Active, then save.
##### Once this goal has been saved, you’ll end up on the team goal page.
Under the gear menu there is an option to duplicate the goal. This should be used to make a copy of the team goal to all other teams that should have the goal available under MyPath.
##### Expose new goal to the path system.
When you create a step, there is a new step type “Adopt A Goal”
Steps of this type will add a pulldown menu where you can select which admin goal the step should use.
Select the goal, save the step.
##### End user experience
When a user encounters a goal step they will have the option to adopt the goal.
This happens behind the scenes and will not take them out of MyPath.
 
## The workflow is a bit cumbersome, but since this is all really an experiment to see what the engagement is like, it’s ok for now. In step 1, the reason to save the URL is in case you ever need to review it or edit. There is no easy way to find that goal currently in the admin goal context. But really, edits should be done at the team level when you adopt it for the first team.

##### Configuring an Admin Goal

###### Step 1 - Goal Info
All I’ve done here is give the goal a name. But you can also provide notes and an image. You do not want to enter start/due dates here.
 
####### Step 2 - Steps
Again, no dates entered. This is a recurring step set to repeat 5x daily.
 
###### Step3 - Settings
No boxes are checked. By having them all unchecked, when the user adopts the goal they will never see a form. That’s because there is nothing for them to customize so the form is skipped and they get the goal behind the scenes.
 
 
# Whenever I adopt this goal, the start date will be that day. So if I start it tomorrow, the start date will be Jan 8.
 
# This start date is how we determine the recurrence of the step. So the overall goal becomes due on Jan 13 with a repeat due each day.
 
# Now you may wonder why it’s due on the 13th instead of the 12th. After all you could think the step cycle would be: 8, 9, 10, 11, 12 making the goal due on the 12th. That’s sort of true, but we want to give people until the very end of the day. If they complete the step at 11:59:59pm it should still count. So the due date becomes Jan 13 at midnight.

##### Associating Adopt a Goal Step with Admin Goal

When I select Step Type {Comment}
And enter in content
And select a Goal to Adopt {TAke 3 Slow Breaths Every Day}
And enter in an amount for Points {10}
And click "Save"
Then I am taken back to the Activity dashboard


