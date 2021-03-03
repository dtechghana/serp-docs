Academic Module
###############

This section of our guide covers the various tools and features available in sERP for managing academics related data; from general academic information, to student performance assessment.

.. |edit_icon| image:: ../images/pencil.png
.. |delete_icon| image:: ../images/trash.png
.. |drop_arrow| image:: ../images/drop-arrow.png


.. _academic_classes:

Classes
*******

This section allows you manage all information related to your school's classes in sERP. The classes section can be accessed from the :ref:`main navigation menu <setup_layout>` by going to Academic -> Classes.


Add Class
=========

1. Click the drop down arrow ( |drop_arrow| ) in the "Add Class" pane to reveal the form options
2. From the "Add Class" pane, enter the following:

	.. note::
		* **Academic Calendar**: select the academic calendar category for the class
		* **Class Name**: enter the name of the class as you'd like it to appear
		* **Campus**: select the campus/location where this class belongs
		* **Division**: select the division this class belongs
		* **Class Teacher**: select and assign a class teacher for this class. *(This requires a user account to have been created, and assigned to a staff in sERP)*
		* **Class Code**: enter a code for this class. (*This is required for* :ref:`student ID generation <setup_student_prefix>`)

	.. tip::
		You can add multiple classes at a go by clicking on the drop down arrow ( |drop_arrow| ) in the "Quick Add Class(es)" pane

3. Click on "Add Class"


View Class Summary & Roster
===========================

From the "Existing Class List" pane, locate and click on the name of the class to display the class summary and list of students enrolled in that class. You may also export the student list.

.. _academic_edit_class:

Modifying Class Data
====================

1. From the "Existing Class List" pane, click on edit class (|edit_icon|) in the "Action" column for the class
2. Modify the following:

	.. note::
		* **Academic Calendar**: select the academic calendar category for the class
		* **Class Name**: enter the name of the class as you'd like it to appear
		* **Campus**: select the campus/location where this class belongs
		* **Group**: select the class group to add this class to
		* **Division**: select the division this class belongs
		* **Class Teacher**: select and assign a class teacher for this class. *(This requires a user account to have been created, and assigned to a staff in sERP)*
		* **Class Prefect**: select and assign class prefect for this class from roster
		* **Class Code**: enter a code for this class (*This is required for* :ref:`student ID generation <setup_student_prefix>`). Changes have no effect on existing student ID
		* **SBA Configuration**: specify the :ref:`SBA configuration <settings_sba>` to be used for this class
		* **SBA Assign. Staff**: select a list of staff/teachers who can record marks for student assessment in this class


3. Click "Save"


Delete Class
=============

1. From the "Existing Class List" pane, click on "Delete Class" (|delete_icon|) in the "Action" column for the class
2. From the confirmation dialog box, click to confirm the deletion

.. warning::
	Deleting data is an irreversible process