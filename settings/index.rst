Settings & Configuration
########################

sERP has many options which control how the software operates. This section details the setup and configuration options available.

.. |edit_icon| image:: ../images/pencil.png
.. |delete_icon| image:: ../images/trash.png


.. _settings_general:


General Settings
****************

.. |wrench_icon| image:: ../images/wrench.png

1. From the :ref:`welcome menu <setup_layout>`, click on "Settings"
2. From the "General Settings" section, click on any wrench (|wrench_icon|) icon on the right section of the page
3. Enter the following details:

	* **School Emblem**: Select and upload image file representing your school's logo (*only JPEG files are supported, and image file should be under 400px*)

	* **School Name**: Enter your school name as you wish it to appear throughout the sERP, including on printed documents

	* **School SubName**: Whatever you enter here will appear on a different line next to your school's name in smaller text in both on-screen and printed documents

	* **Motto**: Enter your school motto or slogan

	* **Email Address**: This is the default email address that will appear on all printed documents, and will also appear as the sender on all email correspondences

	* **Postal Address**: Enter your school P.O. Box or Ghana Post Digital address

	* **Phone Number(s)**: Enter your school contact numbers. Multiple numbers may be entered, seperated by a comma

	* **Tax Identification Number (TIN)**: Enter your school tax identifiction number (TIN)

4. Click the "Save" button after entering the above information.



.. _settings_student_prefix:

Student ID Prefix
=================

1. From the general settings page, click the wrench (|wrench_icon|) icon next to "Student ID Prefix"
2. In the "Student ID Prefix", enter the value you wish to use as the student ID prefix
3. Click "Save"


.. _settings_staff_prefix:

Staff ID Prefix
===============

1. From the general settings page, click the wrench (|wrench_icon|) icon next to "Staff ID Prefix"
2. In the "Staff ID Prefix", enter the value you wish to use as the staff ID prefix
3. Click "Save"



.


.



.. _settings_student:

Student Settings
****************

1. From the :ref:`welcome menu <setup_layout>`, click on "Settings"
2. Click on  "Student Settings"


Scholarships
============

Displays the number of scholarships defined in the system. Click on the wrench icon (|wrench_icon|) to view and manage scholarships.

.. tip::
	Checkout our :ref:`student_scholarships` guide for more information


Campuses
========

Displays the number of campuses defined in the system. Click on the wrench icon (|wrench_icon|) to view and manage campuses.

.. tip::
	Checkout our :ref:`student_campuses` guide for more information


Dormitories
===========

Displays the number of dormitories defined in the system. Click on the wrench icon (|wrench_icon|) to view and manage dormitories.

.. tip::
	Checkout our :ref:`student_dormitories` guide for more information

.


.



.. _settings_academic:

Academic Settings
*****************

1. From the :ref:`welcome menu <setup_layout>`, click on "Settings"
2. Click on  "Academic Settings"


.. _settings_calendar:

Default Academic Calendar
=========================

From the Academic Settings section, click on the wrench (|wrench_icon|) icon to the right of "Default Academic Year / Term".

**Setting the default calendar**

1. From the "Update Default Academic Calendar" pane, select:

	* **Category**: the category (i.e. Trimester or Semster) you wish to set the default calendar for
	* **Default Calendar**: the academic calendar item from the list of created calendar entries

		.. tip::
			If no calendar entries exist, you would need to :ref:`create a new academic calendar entry <settings_calendar_data>`

2. Click "Save"




.. _settings_calendar_data:

**Adding a new calendar data entry**

1. From the "Update Default Academic Calendar" pane, click on the "Manage Entries" button
2. From the "Add Academic Calendar Details" pane, enter the following:

	* **Academic Year**: select the academic year you wish to add a calendar entry for
	* **Label**: (optional) enter a name to identify the calendar entry. Defaults to "Default" if none is entered
	* **Category**: select the category (i.e. Trimester or Semester) this calendar entry applies to
	* **Term/Semseter**: select the term/semester you wish to add a calendar entry for
	* **Begins**: select the start date for the term/semester
	* **Ends**: select the end date for the semester

3. Click "Save"



.. _settings_divisions:

Divisions
=========

This displays the number of divisions currently configured in sERP. Click on the wrench (|wrench_icon|) icon to manage divisions.

.. tip::
	Check out our :ref:`academic_divisions` guide for more information


.. _settings_classes:

Classes
=======

This displays the number of classes currently configured in sERP. Click on the wrench (|wrench_icon|) icon to manage classes.

.. tip::
	Check out our :ref:`academic_classes` guide for more information


.. _settings_subjects:

Subjects
========

This displays the number of subjects currently configured in sERP. Click on the wrench (|wrench_icon|) icon to manage subjects.

.. tip::
	Check out our :ref:`academic_subjects` guide for more information


.. _settings_events:

Event Types
===========

This displays the number of event types currently configured in sERP. Click on the wrench (|wrench_icon|) icon to manage calendar.

.. tip::
	Check out our :ref:`Events Calendar <academic_calendar>` guide for more information




.. _settings_sba:

SBA Configuration
=================

SBA configuration determines the grading and comments criteria to be used in student performance assessments. At least one SBA configuration must be configured in order to use sERP, and each class has to be assigned an SBA configuration.

The SBA configuration section can be accessed from the academic settings page by clicking on the wrench icon (|wrench_icon|) next to SBA Configuration.


**Adding a new Configuration**

1. From the "Existing Configurations" pane, click on "Add New SBA Configuration" (**+**)
2. Enter the following information:

	* **Configuration Name**: a value to identify the new configuration
	* **No. of Class Work Columns**: the number of classworks given as part of student assessment within a term/semester. sERP supports a minumum of 4 and maximum of 8 classworks
	* **Class A{N} Max. Score**: the maximum attainable marks for each classwork defined above
	* **Classwork Scale %**: the percentage value that the sum of all classworks will be scaled to
	* **Exam Scale %**: the percentage value that the total exam score will be scaled to for assessment
	* **Grade Type**: select the GES format for grading and remarks to be used with this SBA configuration

3. Click on "Submit"



.. _settings_miscellaneous:

Miscellaneous Settings
======================

The following options can be toggled:

	* **Display student photo on terminal report?**: whether or not to display students' photos on progress reports. This requires that a photo has been uploaded for the student.
	* **Display attendance on terminal report?**: whether or not to display students' attendance on progress reports. Attendance will only be displayed if recorded using the :ref:`attendance module <student_attendance>`.
	* **Show student aggregate on terminal report?**: whether or not to display students' aggregate on progress reports. If set to yes, an entry box will be provided on student progress report to :ref:`record aggregate score <academic_report_data>`.
	* **Show subject positions on terminal report?**: whether or not to display students' subject positions on progress reports
	* **Show class/overall positions on terminal report?**: whether or not to display students' class position on terminal report



.


.



.. _settings_hr:

HR Settings
***********

1. From the :ref:`welcome menu <setup_layout>`, click on "Settings"
2. Click on  "HR Settings"


Departments
===========

This displays the number of departments currently configured in sERP. Click on the wrench (|wrench_icon|) icon to manage departments.

.. tip::
	Check out our :ref:`hr_departments` guide for more information


Staff Types
===========

This displays the number of staff positions/designations currently configured in sERP. Click on the wrench (|wrench_icon|) icon to manage staff positions/designations.

**Adding a new staff type**

1. From the "Add Staff Grade/Post", enter the staff position/designation in the box next to "Staff Grade/Post"
2. Click "Add Staff Type"


Income Tax Rates
================

Indicates whether or not tax rates have been configured. Tax rates are used in computing income tax (PAYE) as per Ghana Revenue Authority requirements. Click on the wrench (|wrench_icon|) icon to manage income tax rates.

**Viewing current tax rates**

The "Current Tax rates" pane displays the tax rates as presently configured in sERP.


**Updating tax rates**

Income tax rates are periodically ammended and published on the GRA website: https://gra.gov.gh/

To update tax rates:

1. Obtain the "monthly" tax rates from the GRA website, for example: https://gra.gov.gh/new-tax-rates-effective-1st-january-2020-2/
2. Enter the "CHARGEABLE INCOME" (amount only) and "TAX RATES" into the boxes provided
3. Click "Save"


Employer's File No./Social Security
===================================

Indicates whether or not the employer's SSNIT number has been set. Click on the wrench (|wrench_icon|) icon to manage.

To set the SSNIT number:

1. From the "Set File No. / Social Security" pane, enter your (school's) SSNIT number in the box next to "File No. / Social Security"
2. Click "Save"


Employee Contribution Rate
==========================

Indicates whether or not the employee contribution rate has been set. This defaults to 5.5%, and typically wouldn't need to be changed. Click on the wrench (|wrench_icon|) icon to manage.

To set employee contribution rate:

1. From the "Set Employee Contribution Rate", enter the contribution rate in the box next to "New Rate"
2. Click "Save"


SSNIT Remittance (1st Teir) Rate
================================

Indicates whether or not the SSNIT contribution rate has been set. This defaults to 13.5%, and typically wouldn't need to be changed. Click on the wrench (|wrench_icon|) icon to manage.

To set SSNIT contribution rate:

1. From the "Set SSNIT Remittance Rate", enter the contribution rate in the box next to "New Rate"
2. Click "Save"



Trustee Remittance (2nd Tier) Rate
==================================

Indicates whether or not the Trustee contribution rate has been set. This defaults to 5.5%, and typically wouldn't need to be changed. Click on the wrench (|wrench_icon|) icon to manage.

To set Trustee contribution rate:

1. From the "Set Trustee Remittance (2nd Tier) Rate", enter the following:

	* **Name Of Trustee**: name of your National Insurance Trust institution
	* **New Rate**: new value for Trustee contribution rate

2. Click "Save"

.

.


.. _settings_finance:

Finance Settings
****************

1. From the :ref:`welcome menu <setup_layout>`, click on "Settings"
2. Click on "Finance Settings"


.. _settings_fee_items:

Fee Items
=========

Fee items basically represent the items listed on a student's bill, for which an amount will be billed based on the :ref:`configured fees <finance_set_fees>` for that item. Click on the wrench (|wrench_icon|) icon to manage billable items.


**Adding a new fee item**

1. From the "Add Fee Item" pane, enter the name of the item you wish to add

	.. tip::
		You can add multiple items at a go by clicking on the (**+**) icon

2. Click "Add"


**Deleting a fee item**

1. From the "Registered Fee Items" pane, click on delete (|delete_icon|) in the action column for the item
2. From the confirmation dialog box, click to confirm the deletion

.. warning::
	Deleting data is an irreversible process


.. _settings_fee_categories:

Fee Categories
==============

sERP includes a feature that allows for segregated billing. By default, registered students are billed for all :ref:`fee items <settings_fee_items>`; however, using fee categories, you can exempt certain groups of students from being billed (and consequently paying) for specific billable items.

Click on the wrench (|wrench_icon|) icon to manage fee categories.

**Adding a new fee category**

From the "Add Category" pane:

1. Enter a name of the category in the box next to "Category Name"
2. Under "Fee Items", select the applicable fee items for the fee category
3. Click "Add"


.. note::
	* Students assigned to a fee category would only ever be billed for the items you select here
	* Students would explicitly have to be assigned to a fee category in order for their bills to be affected by it.


**Deleting a fee category**

1. From the "Registered Fee Items" pane, click on delete (|delete_icon|) in the action column for the item
2. From the confirmation dialog box, click to confirm the deletion

.. warning::
	Deleting data is an irreversible process


** Assigning a fee category to a student**

Fee categories can be assigned to a student either during student registration or by editing the student's details after registration. See our :ref:`student_registration` and :ref:`student_details` guides for more information.



Billing Footnotes
==================

Footnotes can be included on student's bills for the purpose of conveying specific information to parents, for example: payment schedule, term/semester reopening dates, etc. Click on the wrench (|wrench_icon|) icon to manage billing footnotes.

**Adding footnotes**

1. Enter up to 5 footnotes in the boxes provided next to "Footnote {N}"
2. Click "Save"




.

.



.. _settings_sms:

SMS Settings
************

1. From the :ref:`welcome menu <setup_layout>`, click on "Settings"
2. Click on "SMS Settings"
3. Here, you can setup the following:

	* **SMS API ID**: enter your D-Tech SMS API ID
	* **SMS API Key**: enter your D-Tech SMS API Key
	* **Send payment confirmation to parent?**: toggle to determine whether or not sERP sends payment notification to parent/guardian each time payment is applied to student bill
	* **Default Sender ID**: this is the default value that will appear as the sender of all automated SMS notifications. "SchoolERPGH" will be used as the sender ID if not specified

Setting the API ID and Key
==========================

1. Click the wrench (|wrench_icon|) icon next to "API ID" as per above
2. Enter your API User ID and API in the relevant boxes provided
3. Click "Save"

.. tip::
	**Locating your SMS API details**:

	1. Create a D-Tech SMS account, if you haven't already done so: https://dtechghana.com/sms/app/signup
	2. Log in to the SMS dashboard at https://dtechghana.com/sms/app/login
	3. From the navigation menu, go to "API" -> "API Access" to obtain User ID and API Key





.


.

