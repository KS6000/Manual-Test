# Manual-Test
Lexology login page

Test Case 1


Feature: Account Login

Scenario: Valid Username and Valid Password

Given I am on the Login Page

When I enter a Valid Username and Valid Password

And I click on the Login button

Then I should go into the next section after a successful Login



Test Case 2

Feature: Account Login page

Scenario: Invalid Username and Valid Password

Given I am on the Login Page

When I enter an Invalid Username and Valid Password

And I click on the Login button

Then I should get an error stating Invalid email/password


Test Case 3

Feature: Account Login Page

Scenario: Valid Username and Invalid Password

Given I am on the Login Page

When I enter a Valid Username and Invalid Password

And I click on the Login button

Then I should get an error stating Invalid email/password


Test Case 4

Feature: Account Login Page

Scenario: Invalid Username and Invalid Password

Given I am on the Login Page

When I enter an Invalid Username and Invalid Password

And I click on the Login button

Then I should get an error stating Invalid email/password
