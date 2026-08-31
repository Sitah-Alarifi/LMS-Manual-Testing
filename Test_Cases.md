# Moodle LMS Manual Testing - Test Cases

This document contains 12 manual test cases executed on the Moodle Learning Management System (LMS).

## Test Case 01 - Login with Valid Credentials

**Test Case ID:** TC-01  
**Scenario:** Verify login with valid credentials  
**Precondition:** User has a valid student account.

**Steps:**
1. Open the Moodle LMS login page.
2. Enter a valid username.
3. Enter a valid password.
4. Click the Login button.

**Expected Result:**  
User should successfully log in and access the Moodle LMS.

---

## Test Case 02 - Login with Invalid Credentials

**Test Case ID:** TC-02  
**Scenario:** Verify login with invalid credentials

**Steps:**
1. Open the Moodle LMS login page.
2. Enter an invalid username or password.
3. Click the Login button.

**Expected Result:**  
An error message should appear and access should be denied.

---

## Test Case 03 - Login with Empty Fields

**Test Case ID:** TC-03  
**Scenario:** Verify required login fields

**Steps:**
1. Open the Moodle LMS login page.
2. Leave the username and password fields empty.
3. Click the Login button.

**Expected Result:**  
The system should prevent login and indicate that login information is required.

---

## Test Case 04 - View Available Courses

**Test Case ID:** TC-04  
**Scenario:** Verify that the student can view available courses

**Steps:**
1. Log in to Moodle.
2. Open the Dashboard or My Courses page.
3. Review the available courses.

**Expected Result:**  
Courses available to the student should be displayed correctly.

---

## Test Case 05 - Access a Course

**Test Case ID:** TC-05  
**Scenario:** Verify access to an enrolled course

**Steps:**
1. Log in to Moodle.
2. Open My Courses.
3. Select a course.

**Expected Result:**  
The selected course page should open successfully and display its content.

---

## Test Case 06 - Navigate Through Course Content

**Test Case ID:** TC-06  
**Scenario:** Verify course navigation

**Steps:**
1. Open a course.
2. Navigate between course sections.
3. Open an available learning activity or resource.

**Expected Result:**  
The student should be able to navigate through the course and access available content.

---

## Test Case 07 - Complete a Course Activity

**Test Case ID:** TC-07  
**Scenario:** Verify activity completion functionality

**Steps:**
1. Open an available course activity.
2. Complete the required activity.
3. Return to the course page.

**Expected Result:**  
The completed activity should be recorded or displayed as completed.

---

## Test Case 08 - View Grades

**Test Case ID:** TC-08  
**Scenario:** Verify access to grades

**Steps:**
1. Log in to Moodle.
2. Open the relevant course.
3. Navigate to the Grades section.

**Expected Result:**  
The student should be able to access and view available grades.

---

## Test Case 09 - Access a Quiz

**Test Case ID:** TC-09  
**Scenario:** Verify quiz access

**Steps:**
1. Open the course.
2. Navigate to an available quiz.
3. Open the quiz page.

**Expected Result:**  
The quiz information and attempt option should be displayed successfully.

---

## Test Case 10 - Start and Answer a Quiz

**Test Case ID:** TC-10  
**Scenario:** Verify quiz attempt functionality

**Steps:**
1. Open an available quiz.
2. Start the quiz attempt.
3. Answer the quiz questions.
4. Save or proceed through the attempt.

**Expected Result:**  
The system should accept and save the selected answers.

---

## Test Case 11 - Submit Quiz Attempt

**Test Case ID:** TC-11  
**Scenario:** Verify quiz submission

**Steps:**
1. Complete the quiz questions.
2. Open the attempt summary.
3. Click "Submit all and finish".
4. Confirm the submission if required.

**Expected Result:**  
The quiz attempt should be submitted successfully.

---

## Test Case 12 - View Quiz Results

**Test Case ID:** TC-12  
**Scenario:** Verify quiz results and feedback

**Steps:**
1. Submit the completed quiz.
2. Open the quiz review/results page.
3. Review the score and feedback.

**Expected Result:**  
The system should display the quiz result, score, and available feedback.

---
