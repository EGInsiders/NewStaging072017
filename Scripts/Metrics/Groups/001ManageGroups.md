# Manage Groups

## Create a New Group

Given that I am on the metrics Page
When I click "Create Group"
And enter a Group Name [Rosebud]
And click "Save"
Then the group is created
and displayed under "Pending Groups"

## Delete a Group
Given that I am on the Edit Group Page
When I click "Delete" {Delete Group}
Then the system responds "Are you sure? / You're about to do something you might not be able to undo. / Are you sure you want to do this?

##Confirm Deletion of Group
When I click "Ok"
Then the system responds, "<Name of Group> Removed"
And the group has been deleted

# Invite Members to a Group
When I click on "Invite Members" {Helen Lynch}
Then I am taken to the Group Invitation page

# Assign Coaches as followers
When I click on "Assign Coaches"
And select coaches to assign
Then those coaches are added to the group as followers
And the system responds, "[Name of Coach] was added as a follower of [Name of Group]"


