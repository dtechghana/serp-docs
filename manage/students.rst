Students Module
###############

Student information management is a large part of what the sERP software does, and thus this section of the guide provides information on managing the various aspects of sERP related to student bio data and attendance.

The Students module can be accessed from the :ref:`main navigation menu <setup_layout>`, and contains the following sub modules:

.. |edit_icon| image:: ../images/pencil.png
.. |delete_icon| image:: ../images/trash.png
.. |info_icon| image:: ../images/info.png
.. |warning_icon| image:: ../images/warning.png


.. _student_list:

Student List
************

This section enables you query sERP for student information based on mutiple criteria. To begin, select one of the following from the drop-down menu next to "Criteria":

* **All**: generate a list of all students currently registered
* **Name**: search for individual student by name. Enter part or all of the student's name in the box next to "Name"
* **Student ID**: search for individual student by student ID. Enter student's ID in the box next to "Student ID"
* **Gender**: generate a list of currently registered students, based on gender
* **Status**: generate a list of students based on status. Select status from drop-down menu next to "Status"
* **Class/Year Group**: generate a list of students currenty enrolled in a particular class, or past students from a year group. Select class or year group from drop-down menu next to "Class/Year Group"
* **Section**: generate a list of students based on section. Select section from drop-down menu next to "Section"
* **Campus**: generate a list of students registered in a particular campus. Select campus from drop-down menu next to "Campus"
* **Division**: generate a list of students registered in a particular division. Select division from drop-down menu next to "Division"
* **Dormitory**: generate a list of students registered in a particular dormitory. Select dormitory from drop-down menu next to "Dormitory"
* **Scholarship**: generate a list of students on a given scholarship


Student List Table
==================

Search results are displayed in the following format:

.. list-table::
	:header-rows: 1

	* - Student ID
	  - Name
	  - Gender
	  - Status
	  - Class
	  - Actions
	* - Student sERP ID
	  - Student full name and link to :ref:`student details <student_details>`
	  - Student's gender
	  - Student Status
	  - Student class and link to class details
	  - Actions: view, edit, withdraw or delete






.. _student_details:

Student Details
===============

**Viewing Students Details**

From the "Students" pane in the search results, click on the students name or simply click on "View Student's Details" (|info_icon|) from the "Actions" column for that student.

.. note::

	Student data is presented in the following sections for easy identification:

	* **Students Information**: general student information, including: student ID, full name, gender, status, date of birth, etc
	* ** Guardian's Information**: name, contact and other information pertaining to student's parent/guardian
	* **Other Information**: specialized information such as scholarships, fees category, last school attended, and reason for leaving last school
	* **Documents**: allows for uploading documents related to student. Accepted formats are: jpg, jpeg, png, pdf, doc, docx, xls, and xlsx
	* **Additional Information**: allows for adding of extra information which may not ordinarily be captured by sERP


	It is also possible to view student-specific academic and financial information such as progress reports, student bill and fees payment history.


Modifying Student Details
=========================

You may update information relating to students registered in sERP at anytime. To modify student details:

1. From the "Students" pane in the search results, click on "Edit Student's Details" (|edit_icon|) from the "Actions" column for that student. Or, click on "Edit Details" from the student details page
2. Alter the required information in the relevant section
3. Click "Update Student"



Withdrawing a Student
=====================

When a student is withdrawn, the student is added to the list of :ref:`withdrawn students <student_withdrawn>`, and will no longer be part of enrolled students in their class. However, the students data remains intact and can subsequently be re-admitted, if required. To withdraw a student:

1. From the "Students" pane in the search results, click on "Withdraw Student" (|warning_icon|) from the "Actions" column for that student
2. Confirm student withdrawal from the dialog box


Deleting a student
==================

1. From the "Students" pane in the search results, click on "Delete Student" (|delete_icon|) from the "Actions" column for that student
2. From the confirmation dialog box, click to confirm the deletion

.. warning::
	Deleting data is an irreversible process




.. _student_registration:

Student Registration
********************

This section provides an interface for adding student information into the sERP system. The student registration section can be accessed from the :ref:`main nagivation menu <setup_layout>` by going to Students -> New Registration.

1. Complete the following sections:


Personal Details
================

Captures general student information and bio data including:

	* Surname
	* First name
	* Other names
	* Date of Birth
	* Place of birth
	* Gender
	* Nationality
	* Religion

Academic Details
================

Captures information pertaining to the student's relationship with the school, as well as other 'academic-specific' information, including:

	* Student ID

		.. hint::
			sERP provides the option to automatically generate student ID based on configured ID criteria. Altarnatively, you may manually enter the student ID

	* Date of registration
	* :ref:`Class <academic_classes>`
	* :ref:`Section <student_section>`
	* Status
	* :ref:`Scholarship <student_scholarships>`
	* :ref:`Fee Category <settings_fee_categories>`
	* Last school attended
	* Reason for leaving last school


Contacts
========

Captures student contact information:

	* Mobile number
	* Phone number
	* Area of residence
	* Current address
	* Postal address

Parents
=======

Captures student's parents' details, including:

	* Full name
	* Mobile number
	* Address
	* Email address
	* Occupation

Photo
=====

Upload image to be used as student photo ID


2. Click on "Add Student"


.. tip::
	If an error is produced during registration, you might need to clear your browser cache and reload the page and try again: https://kb.iu.edu/d/ahic


.

.


.. _student_past:

Past Students
*************

This section contains information about alumni, and is generally categorized into :ref:`year groups <academic_year_groups>`. The past students section can be accessed from the :ref:`main nagivation menu <setup_layout>` by going to Students -> Past Students.

1. Select search criteria:
	
	* **All**: show all past students
	* **Year Group**: show past students from specific alumni :ref:`year group <academic_year_groups>`

2. Click "List Students"


Available actions
=================

The following actions can be performed for past students:

* **View Student Details**: sERP retains student data even after completion
* **Edit Student Details**: allows authorized personnel to modify past student information
* **Record Bill Payment**: sERP allows for colleting arrears owed by students even after they may have left the school
* **Delete Student**: completely remove student records from sERP



.. _student_withdrawn:

Withdrawn Students
******************

This section contains information about students who have left the school but did not complete their programme. The withdrawn students section can be accessed from the :ref:`main nagivation menu <setup_layout>` by going to Students -> Withdrawn Students.

1. Select search criteria:
	
	* **All**: show all withdrawn students
	* **Date Withdrawn**: show withdrawn based on withdrawal date. This option allows you to specify a date range for the search

2. Click "List Students"


Available actions
=================

The following actions can be performed for past students:

* **View Student Details**: sERP retains student data even after completion
* **Edit Student Details**: allows authorized personnel to modify past student information
* **Re-admit student**: allows authorized personnel to re-enroll student into active students list, without having to re-enter their registration information
* **Delete Student**: completely remove student records from sERP



.. _student_attendance:

Attendance
**********

The attendance section enables authorized personnel record daily student attendance. Attendance data can subsequently be viewed from the :ref:`reports <reports_attendance>`. Attendance data is also included in student :ref:`progress reports <academic_terminal_reports>`.

The attendance section can be accessed from the :ref:`main nagivation menu <setup_layout>` by going to Students -> Attendance.

1. Select the class you wish to record attendance for from the drop down menu next to "Select Class"
2. Select the date you wish to record attendance for
3. Click on "List Students"
4. From the resulting class register, check the box in the column labelled "Present" for each student. If student is absent, simply leave the box unchecked.
5. Click "Record Attendance"




.. _student_section:

Sections
********

This section allows for managing sections. It can be accessed from the :ref:`main navigation menu <setup_layout>` by going to Students -> Sections.

Adding Sections
===============

1. From the "Add Section" pane, enter the name of section next to "Section Name"
	.. tip::
		You can add multiple sections at once by clicking on the (+) icon

2. Click on "Add Section/s"


.. _students_edit_section:

Modifying Section Data
======================

1. From the "Sections" pane, click on "Edit Section" (|edit_icon|)
2. Enter the new name of the section in the box next to "Section Name"
	
3.Click "Modify Section"



Delete Section
==============

1. From the "Sections" pane, click on "Delete Section" (|delete_icon|)
2. From the confirmation dialog box, click to confirm the deletion

.. warning::
	Deleting data is an irreversible process



.. _student_campuses:

Campuses
********

The campuses section of the student module provides interfaces that allow you add, modify and/or delete campus/location data. It can be accessed from the :ref:`main navigation menu <setup_layout>` by going to Students -> Campuses.

Adding Campus/es
================

1. From the "Add Campus" pane, enter the name of campus next to "Campus Name"
	.. tip::
		You can add multiple campuses at once by clicking on the (+) icon
2. Click on "Add Campus/es"


.. _students_edit_campus:

Modifying Campus Data
=====================

1. From the "Campuses" pane, click on "Edit Campus" (|edit_icon|)
2. Here you can:
	* Enter the name of the campus in the box next to "Campus Name", 
	* In the box next to "Headmaster's Signature", select a JPEG image for the headmaster's signature, which will appear on student :ref:`progress reports <academic_terminal_reports>`.
	
3.Click "Modify Campus"



Delete Campus
=============

1. From the "Campuses" pane, click on "Delete Campus" (|delete_icon|)
2. From the confirmation dialog box, click to confirm the deletion

.. warning::
	Deleting data is an irreversible process


.. _student_dormitories:

Dormitories
***********

This section allows for managing student dormitories. It can be accessed from the :ref:`main navigation menu <setup_layout>` by going to Students -> Dormitories.

Adding Dormitories
==================

1. From the "Add Dormitory" pane, enter the name of dormitory next to "Dormitory Name"
	.. tip::
		You can add multiple dormitories at once by clicking on the (+) icon

2. Click on "Add Dormitory/ies"


.. _students_edit_dormitory:

Modifying Dormitory Data
========================

1. From the "Dormitories" pane, click on "Edit Dormitory" (|edit_icon|)
2. Enter the new name of the dormitory in the box next to "Dormitory Name"
	
3.Click "Modify Dormitory"



Delete Dormitory
================

1. From the "Dormitories" pane, click on "Delete dormitory" (|delete_icon|)
2. From the confirmation dialog box, click to confirm the deletion

.. warning::
	Deleting data is an irreversible process



.. _student_promotions:

Promotions
**********

The promotion section offers a flexible and easy way to move students from one class to another. This is particularly useful for handling bulk promotions at the end of each academic term/semester. The promotion section can be accessed from the :ref:`main navigation menu <setup_layout>` by going to Students -> Promotions.

From the "Promote Students" pane:

1. Select the class from which you would like to promote students, from the drop down menu nex to "Class"
2. From the drop menu next to "Student", check the box next to each student in the selected class you wish to promote. Alternatively, simply check the box next to "Select All" to promote all students in the class.
3. From the drop down menu next to "Move To", you can select from the following:

	* **Past Students**: select this option to move student(s) to alumni :ref:`year group <academic_year_groups>`. You'd then need to specify which year group to move the student(s) to from the drop down menu next to "Year Group"
	* **Withdrawn List**: select this option to add selected student(s) to the list of :ref:`withdrawn students <student_withdrawn>`
	* You may also move the selected student(s) to a new class by simply selecting the new class you wish to move the student(s) to

4. Click "Save"


.. _student_prefects:

Prefects
********

This section allows you to appoint students to prefectorial positions. The prefects section can be accessed from the :ref:`main navigation menu <setup_layout>` by going to Students -> Prefects.

1. Enter the ID of the student you wish to appoint prefect in the box next to "Student ID"
2. Ener the prefectorial position you wish to appoint the student to in the box next to "Position"
3. Click "Save"

Updating prefectorial postion
=============================

1. From the "Prefects" pane, click on "Modify Positon" (|edit_icon|) next to the prefect
2. Enter the new position
3. Click "Save"



.. _student_scholarships:

Scholarships
************

This section allows you to define and manage scholarships. Scholarships provide a way of waiving all or partial fees for selected students. The scholarship section can be accessed from the :ref:`main navigation menu <setup_layout>` by going to Students -> Scholarships.

Creating a new scholarship
==========================

From the "Add Scholarship" pane:

1. Enter a name for the new scholarship in the box next to "Scholarship Name"
2. Specify a percentage value between 1-100 in the box next to "Percentage"
3. Check the box next to each billable item you would like the scholarship to be applied to next to "Fee Items Affected". You may select all items by checking the box next to "Select All"
4. Click on "Add Scholarship"

.. note::
	When a student is assigned to a scholarship, the items on the student's bill will be discounted by the total amount representing the percentage value defined for that scholarship


Modifying a scholarship
=======================

1. From the "Existing Scholarships" pane, click on "Edit Scholarship" (|edit_icon|) from the "Actions" column for the scholarship
2. Update the following:

	* Scholarship Name
	* Percentage
	* Fee Item Affected

3. Click on "Modify Scholarship"


Deleting a scholarship
======================

1. From the "Existing Scholarships" pane, click on "Delete scholarship" (|delete_icon|)
2. From the confirmation dialog box, click to confirm the deletion

.. warning::
	Deleting data is an irreversible process


.


.