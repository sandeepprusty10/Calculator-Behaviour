# Addition

Scenario: Add two numbers
  
Given I have a working calculator

When I enter "number 1"
And I press "+" button
And I enter "number 2"
And I press "=" button

Then I see the "added-sum" as the result

Scenario: Add more numbers 

Scenario: Result is too large to display

Scenario: Numbers can be negative

Scenario: Numbers can be fraction

Scenario: Number can be irrational

Scenario: Length of each number

Scenario: If number 1 or number 2 is not entered

Scenario: If the number is real or complex

Scenario: If we are in between some operation
