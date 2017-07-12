## Land on Demo Team Decision Tree

Given that I have clicked “Join Demo”
And I've been taken to the Demo Team Decision Tree Page
On Load, a button is displayed labeled “I'm a Student”

###

## Self identify as a student

When I click on “I'm a Student”
Then I am taken to the registration form for Students

{ ### }

## Register as a Student

Given that I am on a registration page for students
When I enter my registration information
And enter a team join code {5332179}
Then I am accepted onto the site
And added to the team {Justice League of America}
And I am added to the group {Logan, Winston}

{###}
