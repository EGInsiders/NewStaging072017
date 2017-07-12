# 

## Initiate posting a comment in repsonse to a library resource
When I click on Commment under the description of a resource {CNN - Breaking News}
Then a comment field is shown in a modal

###

## Post a Comment
Given that I am viewing Resource information in a modal
when I click inside the field labeled "Comment"
And enter a message
And then click "Comment"
Then my message is saved

###

# Delete a comment
When I click on the command menu
and click "Delete"
Then the system responds "Are you sure?"
And when I respond "Yes"
Then my message is removed
And the system responds, "post deleted"

###

# Edit a Comment

## Initiate editing a comment
Given that I'm viewing a resource's information inside the modal
When I click on the command menu next to a post
and click "Edit"
Then the posted comment is displayed in an editable field

## Change a posted comment
When I change the contents of a posted comment
And click "Save"
Then my changes are saved
And the system responds, "Post Edited"

###
