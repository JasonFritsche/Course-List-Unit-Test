# Course-List-Unit-Test

## Course.cs
Contains the Course class and constructor.

## CourseList.cs
Contains the courseList class. 
Contains an array of courses, CourseArray
Contains the GetCourseByCourseID method. This method iterates through the array of courses and compares the course ID to the argument that was passed in which is an id. If a match is found, the course is returned. If no match is found, null is returned as per the homework requirement.

## CourseListTest.cs
Contains two methods used to conduct testing
GetCourseByCourseIDTestWhenCourseExists() tests outcome if the course is found.
GetCourseByCourseIDTestWhenCourseDoesNotExist() tests outcome if no match is found.
