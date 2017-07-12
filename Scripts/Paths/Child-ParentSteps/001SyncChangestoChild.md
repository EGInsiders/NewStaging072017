# Synchronize changes from parent step to child step
Given that you are editing a parent step

## Edit a Parent Step and synchronize changes to child step
When I add the word "Rosebud" to the body of the message in the step {https://assets.ford.eduguide.org/mypath/manage/step/1728/1731}
And enable "Sync most changes to child versions. Note: This will not modify child version comment lengths."
And Click "Save"
Then my changes are saved in both versions of the step
And the system responds, "Path step has been saved. Changes have been applied to all child versions"
