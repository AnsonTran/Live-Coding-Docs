# Models
## Member
+ 1 First name
+ 1 Last name
- 1 ID

## Student (is a member)
- 1 Permissions

## Teacher (is a member)
- 1 Permissions

## Classes
- 0..n Students
- 0..n Teachers
- 0..n Assignments

## Assignment
- 1 Assignment ID
- 1 Description
- 1 Creation Date
- 0..1 Due Date
- 0..n Submissions
- 0..n Evaluations

## Environment
- 1..3 shells
- 1 output

## Submission
- 1 Submission ID
- 1..n Blocks of code (multiple languages)
- 0..n Comments
- 0..n Results

## Comment
- 1 Pointers to code
- 1 Block of text

## Permissions
- Create Classes
- Remove Classes
- Hide Classes
- View Classes

- Add Teachers
- Remove Teachers
- Add Students
- Remove Students

- Create Assignments
- Remove Assignments
- Hide Assignments

- Create Submissions
- Remove Submissions

- View List of Members
- View List of Students
- View Assignments
- View Submissions
- View Live Coding
