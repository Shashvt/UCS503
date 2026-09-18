# Week 3 -- Frontend Implementation, Login Validation and Initial Testing

## Objective

The objective of this week was to begin implementation of the frontend
and improve the Login functionality by adding client-side validation and
testing different input conditions.

## Activities Completed

-   Started the basic frontend implementation of the project.
-   Reviewed the initial interface and the relationship between
    different frontend components.
-   Worked on the Login page.
-   Implemented client-side form validation using JavaScript.
-   Added checks for required input fields.
-   Added validation handling for incomplete and invalid input.
-   Displayed suitable validation feedback to the user.
-   Tested the Login form using different input conditions.
-   Checked that valid input was allowed to proceed while invalid input
    was handled before submission.
-   Reviewed basic software design and coding practices relevant to the
    implementation.

## Login Validation Implementation

JavaScript was used for the client-side validation of the Login form.

The validation process included:

1.  Reading the values entered by the user.
2.  Checking whether required fields contained input.
3.  Checking the input against the required validation conditions.
4.  Showing a validation message when the entered information was not
    acceptable.
5.  Allowing the form to proceed when the validation conditions were
    satisfied.

## Testing Performed

Different test inputs were used to verify the validation logic:

  -----------------------------------------------------------------------
  Test Condition                      Expected Behaviour
  ----------------------------------- -----------------------------------
  Empty fields                        Validation message should be
                                      displayed

  Partially completed form            User should be asked to complete
                                      the required input

  Invalid input                       Invalid input should be rejected

  Valid input                         Form should proceed
  -----------------------------------------------------------------------

This testing helped identify whether the validation logic behaved
correctly for different input cases.

## Software Design and Construction Concepts

Along with the implementation, I studied concepts from the Software
Engineering syllabus that are relevant to frontend construction,
including:

-   Separation of concerns
-   Levels of abstraction
-   Information hiding
-   Coupling and cohesion
-   Component-level design
-   Coding practices
-   Refactoring and maintaining readable code
-   Verification and validation

These concepts helped in understanding how individual frontend
functionality should fit into the overall system.

## My Contribution

My main contribution was the implementation and testing of
JavaScript-based validation for the Login page. I worked on the input
checks and validation behaviour and tested the form with multiple
conditions.

## Outcome

The frontend implementation was started and the Login page received
functional client-side validation. The validation was tested with
different inputs, providing a working foundation for further frontend
development and future integration with the rest of the system.
