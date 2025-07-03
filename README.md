# final-exam-task-2
# University Management System (UMS)

## Description
This Java program simulates a University Management System with:
- A list of students.
- Each student has a list of learning courses.
- Each course contains:
  - Title
  - Acceptance prerequisites
  - Major topics

## Features
- Uses object-oriented programming principles.
- Prints detailed course information per student, to be clearer the titles, major topics and prerequisites
  are the same for all the students as only computer science students have Object Oriented Programming.
- Integrates real student data for Luka Manvelishvili (per Argus records).
- Fully modular with getters/setters.
- for the diagram this is the exact image of how the program looks visually:

┌─────────────────┐        1       ┌────────────────────────┐
│     UMS         │◄───────────────│      Student           │
├─────────────────┤                ├────────────────────────┤
│ - students: List<Student>        │ - fullName: String     │
├─────────────────┤                │ - courses: List<Course>│
│ + addStudent()   │                ├────────────────────────┤
│ + printStudentData(s:Student)    │ + getFullName()         │
└─────────────────┘                │ + setFullName()         │
                                   │ + getCourses()          │
                                   │ + addCourse(c:Course)   │
                                   └────────────────────────┘
                                           ▲
                                           │ many
                                           │
                                   ┌────────────────────────┐
                                   │      LearningCourse    │
                                   ├────────────────────────┤
                                   │ - title: String         │
                                   │ - acceptancePrerequisites: String │
                                   │ - majorTopics: String   │
                                   ├────────────────────────┤
                                   │ + getters/setters       │
                                   └────────────────────────┘
