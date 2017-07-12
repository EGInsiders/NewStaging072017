Create a Folder
Delete a Folder
Rename a folder

## Move a Resource to a Folder

## Initiate move resource to folder
When I hover over the upper left corner of a resource
and click "Folders"
Then the Manage Folder Modal appears

###

## Add resource to existing folder(s)
When I click on a checkbox next to a folder
Then the resource is added to the folder

###

## Add resource to new folder
When I enter a folder name
and click "Add"
Then the new folder is displayed {White Folder}
And the checkbox next to it is checked
and the resource is added to the folder

###

# Star/Unstar a Resource

# Star a resource

When I hover over the upper the upper left corner of the resource's thumbnail image
And click "Star"
Then a star outlined by orange appears in the thumbnail

# Unstar a resource

When I hover over the upper the upper left corner of the resource's thumbnail image
And click "Unstar"
Then a star outlined by orange is removed from the thumbnail


###

# Edit a Resource

## Initiate Editing a Resource

When I hover over the upper the upper left corner of the resource's thumbnail image
And click "Edit"
Then I am taken to a page where I am able to edit the title and the description for the resource

## Change a resource's title and Description

Given that I am on the page where I can edit a resource
When I change the title
And I change the description
And click "Save"

