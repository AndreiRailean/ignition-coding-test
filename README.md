# Ignition JavaScript Interview Test

The purpose of this test is to evaluate your ability with the following aspects of writing JavaScript code:
* Creation of a Library Function
* Usage of Regular Expressions
* Writing a Test
* Building a simple Component
* Using react component State
* Reading existing code and fixing bugs
* Writing a more advanced component using lifecycle hooks
* API Interaction (no server knowledge required)

Bonus Points:
* Usage of TypeScript
* Usage of third party dependencies
* Efficient algorithms

## Setup

To aid with completing these exercises, a set of prerequisites have been assembled for you. When you pull this repository, you'll need to run 
`yarn install` to fetch all dependencies. We suggest you use an online tool like **CodeSandbox** to host and share your exercise with us. This will make it easy for you to avoid having to deal with dependencies in your local environment.

## Exercises
*If you cannot complete these exercises in less than 2 hours, you may find technical interview difficult.*

### 1. `isValidDecimal` String Validator Function
Write a function `isValidDecimal` that takes a `string` and returns 
- `true`, if it receives a string representing a valid decimal
- `false`, if input is not a valid decimal

#### Notes:
- **Use regular expressions** to power your validation logic
- Assume that `.` (dot) is a decimal separator

### 2. Simple React Component
Create a component that has a Input for entering amounts and a Button.
When you input a value that is a valid decimal and press a button, component should say "Valid" in green. When value is not valid, it should say "Not Valid" in red.

#### Notes:
Design choices are up to you and will be evaluated as part of your ability to contribute to the evolution of Ignition's user interface.
Show usage of `useState` react hook to manage a controlled input

### 3. Advanced Component
Render a 3 x 3 grid of 9 buttons.
When component renders, it should select one button at random and highlight it. When highlighted button is clicked it should cause another button to be highlighted at random. When an unhighlighted button is clicked, it should become highlighted.

### 4. Fix an error in component
You have a component that performs a network request to fetch data from the server. It is supposed to show 5 rows of data at a time, but instead of showing different rows it shows the same row 5 times. And "load more" button doesn't seem to work.

### 5 Write a test
Write a `jest` test to cover all cases you can think of for `isValidDecimal` library function

## Submitting your result
Please send a link to your CodeSandbox to the recruiter. 
Your submission will be evaluated by the interviewer and will be discussed during technical interview

## Technical Interview
During technical interview, you will be asked to complete another test, which will build upon your solutions submitted above. This part of the test will evaluate your ability to solve problems on the spot. No pressure will be applied and the problems shouldn't be too hard, but it will help guide the technical discussion and evaluation of your problem-solving ability.