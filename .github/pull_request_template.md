<!--- Provide a general summary of your changes in the Title above -->

## Description
<!--- Describe your changes in detail -->

## Motivation and Context
<!--- Why is this change required? What problem does it solve? -->
<!--- If it fixes an open issue, please link to the issue here. -->

## How Has This Been Tested?
<!--- Please describe in detail how you tested your changes. -->
<!--- Include details of your testing environment, tests ran to see how -->
<!--- your change affects other areas of the code, etc. -->

## Screenshots (if appropriate):

## Types of changes
<!--- What types of changes does your code introduce? Put an `x` in all the boxes that apply: -->
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)

## Checklist:
<!--- Go over all the following points, and put an `x` in all the boxes that apply. -->
<!--- If you're unsure about any of these, don't hesitate to ask. We're here to help! -->
- [ ] My code follows the code style of this project.
- [ ] My change requires a change to the documentation.
- [ ] I have updated the documentation accordingly.

## For Peer Reviewers

- [ ] Does the branch name of this change match the project standards?
- [ ] Are the manual steps for testing these changes properly documented?
- [ ] Are the instructions for validating the functionality of these changes provided?
- [ ] Is there a documented rollback procedure in case of deployment failure?
- [ ] Has the code passed the linter(s)?
- [ ] Does the code avoid shorthand syntax when it affects readability?
- [ ] Does the code contain human readable comments wherever logic is present?
- [ ] Do functions in the code document their inputs and outputs in the docblock
    format?
- [ ] Is code formatted consistently with industry standards?
  - tabs/spaces are uniform
  - line returns are not gratuitous
  - line returns are not non-existent
  - line width should remain less than 80 columns unless unavoidable
  - function names should be named consistently and clearly
  - variable names should be named consistently and clearly
- [ ] Code is able to be checked out without errors
- [ ] Code does not contain mega functions
  - Multiple smaller functions are preferred over single larger functions
- [ ] Code does not throw errors in logs
  - `/var/log/syslog`
  - Docker logs?
  - Drupal reports?
  - Warnings on website pages?
  - Errors on website pages?
- [ ] Ensure all commits in the branch are accounted for
  - If commits do not show up in the diff, verify when they were previously
      merged into the code base and notate.
  - Remove any commits that are not part of the functionality of this change
- [ ] Ensure the code is based off of a recent branch of master/develop.
- [ ] Does a test for this code exist?
  - If a test does not exist, the code is not ready.
  - If there are obvious edge cases that are not tested, flag and create them.
- [ ] Do any other tests need to be added to fully test functionality?
- [ ] Does this code pass on all testing suites?
- [ ] Does this code cause anything else to break on any of the testing suites?
- [ ] Do the changes look correct in all supported browsers (last 2 versions)?
