# Edit Activity
When I click on "Edit Activity"
Then I am taken to the edit form for the activity

###

# Create Version

## Initiate a new Version
When I click "Create Version"
Then I am taken to a page which says, "You are creating a new version of You are what you eat. Select the user type that the new version is for and click Create Version."

####

## Create a new Version

When I select a user type {Coach}
And I click "Create Version"
Then I am taken to the dashboard for the new version
And the system says, "New version created, you can now manage this version"

###

# View Journal
When I click on "View Journal"
Then I am shown a list of the path's steps inside a journal

###

# View all user comments

When I click on "view all user comments" {Digital Ocean Test Path}
Then I am shown comments posted by users in the path
