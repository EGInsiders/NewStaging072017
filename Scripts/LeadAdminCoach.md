Story	Step	Expected Results	D
### Send Invitation			
	Given that I am viewing the Coach Invite Page		
	When I enter an email address into the field labeled "Add Email to Invite"		
	And select a coach role		
	And click "Send Invite"		
		Then the invitation confirmation modal appears	
		###	
### Confirm invitation			
	Given that I am viewing the invitation confirmation modal		
	When I enter a custom message		
	And click "Send Invite"		
		Then the modal clears	
		And the system responds, "Your coach invitations have been processed and necessary emails sent out."	
		###	
### User Responds to team invitation			[https://assets.ford.eduguide.org/team/627/invitation/5b24688239c1b720714040a82afae524](https://assets.ford.eduguide.org/team/627/invitation/5b24688239c1b720714040a82afae524)
	Given that the invitation arrives in my inbox		
	When I click on the link "Join [Team name] Now"		
		Then I am taken to the site	
		And asked "Do you have an account?"	
		###	
### Decision Tree			
	Given that I am viewing the Decision Tree		
	And, the page says, "In order to process the invitation, you must first create an account or log into an existing account."		
	And the page asks, "Do you have an account?"		
	When I click, "No, Join"		
		Then I am taken to the registration form	
		###	
### Register for an account			
	Given that I am on the registration form for team coaches		
	When I enter my first name		
	And Last Name		
	And Job Title		
	And Mobile Phone		
	And join code (pre-populated)		
	And Email address (pre-populated)		
	And confirm email address (pre-populated)		
	and Password		
	And Confirm Password (pre-populated)		
	And I click "Join"
  ###
