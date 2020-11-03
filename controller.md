# Controllers
## validateService
* static int    validate(String ID, String password)
* static int    isStudent(String ID)
* static int    isTeacher(String ID)

## adminService(Permissions)
* static String createClass(String name)
* static int    removeClass(String classID)
* static int    hideClass(String classID)

* static String addTeacher(String classID, String teacherID)
* static String addTeacher(String classID, [String teacherID])
* static String removeTeacher(String classID, String teacherID)
* static String removeTeacher(String classID, [String teacherID])

* static String addStudent(String classID, String studentID)
* static String addStudent(String classID, [String studentID])
* static String removeStudent(String classID, String studentID)
* static String removeStudent(String classID, [String studentID])

## assignmentService(Permissions)
* static String createAssignment(String description)
* static int    removeAssignment(String assignmentID)
* static int    hideAssignment(int hidden)

* static String createComment(String submissionID, String comment)
* static int    removeComment(String commentID)

* static String createSubmission(String assignmentID, String studentID, [String code])
* static String removeSubmission(String assignmentID, String studentID, [String code])
