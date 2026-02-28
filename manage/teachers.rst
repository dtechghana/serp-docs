Teacher Portal
##############

The Teacher Portal provides teaching staff with a dedicated interface for managing their classes, assignments, notes, lesson plans, and attendance — without requiring access to the full administration panel.

.. note::

	Access to the Teacher Portal requires a staff user account with the **Teacher Portal** access role (role 50) assigned by an administrator, or an administrator account (access level 100). See :doc:`/setup/users` for instructions on assigning roles.

The Teacher Portal is accessed at ``/teacherportal`` on your sERP installation.

.. |edit_icon| image:: ../images/pencil.png
.. |delete_icon| image:: ../images/trash.png
.. |info_icon| image:: ../images/info.png


.. _teacher_dashboard:

Dashboard
*********

The Teacher Portal dashboard provides an at-a-glance summary of:

* **My Classes**: the classes assigned to this teacher (as class teacher or SBA staff)
* **Assignments Posted**: total assignments created this term
* **Pending Grading**: number of assignment submissions awaiting grading
* **Recent Submissions**: the most recently submitted student assignments

Click on any class or assignment from the dashboard for quick access.


.. _teacher_classes:

My Classes
**********

Navigate to **Teacher Portal > My Classes** to view all classes where you are assigned as the class teacher or as an SBA staff member.

Each class card shows the class name, number of enrolled students, and links to the class's assignments, notes, and attendance.


.. _teacher_assignments:

Assignments
***********

Navigate to **Teacher Portal > Assignments** to create and manage assignments for your classes.

Creating an Assignment
======================

1. Click **Add Assignment**
2. Select the **Class** and **Subject**
3. Enter the **Title**, **Description**, **Instructions**, and **Due Date**
4. Click **Save Assignment**

The assignment becomes immediately visible to students in the student portal.

Grading Submissions
===================

1. From the Assignments list, click **View Submissions** for any assignment
2. The submissions table shows each student's name, submission status, submitted content, and any attached files
3. Click **Grade** to enter a grade (letter or percentage) and written remarks
4. Click **Save Grade** — the grade is visible to the student once saved

.. note::

	The completion rate (percentage of students who submitted) is shown for each assignment.


.. _teacher_notes:

Notes
*****

Navigate to **Teacher Portal > Notes** to upload class study notes for students.

Uploading Notes
===============

1. Click **Upload Notes**
2. Select the **Class** and **Subject**
3. Enter a title or description for the notes
4. Attach the file (PDF, Word, or image formats accepted)
5. Click **Upload**

Uploaded notes are immediately accessible to students via **Student Portal > Study Notes**.

.. tip::

	Notes can also be managed from the main admin panel at **Academic > Notes**.


.. _teacher_lesson_plans:

Lesson Plans
*************

Navigate to **Teacher Portal > Lesson Plans** to create and manage your lesson plans.

1. Click **Add Lesson Plan**
2. Fill in: Class, Subject, Title, Objectives, Activities, Resources, Lesson Date, and optionally attach a file
3. Toggle **Share with Students** to make the plan visible in the student portal
4. Click **Save**

Your existing lesson plans are listed with their class, subject, date, and sharing status.


.. _teacher_attendance:

Attendance
**********

Navigate to **Teacher Portal > Attendance** to mark attendance for your classes.

1. Select the **Class** from the dropdown
2. Select the **Date** (defaults to today)
3. The class register appears with all enrolled students
4. For each student, click **Present** or **Absent**
5. Click **Submit Attendance**

.. note::

	If attendance has already been recorded for the selected class and date, the existing record is displayed. You can update it before submitting.

	When a student is marked absent, an SMS notification is automatically sent to their registered parent or guardian (if SMS is configured and the guardian has a mobile number on file).


.. _teacher_performance:

Class Performance
*****************

Navigate to **Teacher Portal > Performance** to view academic performance summaries for your classes.

The performance view shows:

* **Assignment Completion Rate**: for each class, the percentage of expected submissions received, shown as a progress bar
* **Class Summary**: total assignments posted, total submissions, and number graded for each class

This view helps teachers identify classes where engagement is low and follow up accordingly.
