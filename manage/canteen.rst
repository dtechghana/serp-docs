Canteen Module
##############

The Canteen module allows you to configure, record, and track canteen payments for students. It is accessed via the main navigation and requires the relevant Canteen access role(s) to be enabled for your user account.

.. note::

	Canteen must first be enabled in **Settings > Student Settings > Canteen** before it appears in the navigation menu.

.. |edit_icon| image:: ../images/pencil.png
.. |delete_icon| image:: ../images/trash.png


.. _canteen_setup:

Canteen Setup & Configuration
*****************************

Before a payment can be recorded for a student, that student must first be set up for canteen — this determines whether they participate, and the daily amount they're charged. Navigate to **Canteen > Setup** to configure this.

Setting Up an Entire Class
=====================================

1. Choose **By Class** from the Setup Group dropdown
2. Select the class
3. Switch **Paying Canteen?** on
4. Enter the daily **Amount** charged for this class
5. Click **Save** — every student currently in the class is updated with this setting

Setting Up an Individual Student
=====================================

1. Choose **By Student** from the Setup Group dropdown
2. Enter or search for the Student ID
3. Switch **Paying Canteen?** on
4. Enter the daily **Amount** charged for this student
5. Click **Save**

.. tip::

	Use the class-wide option to set up everyone at once, then switch to the individual-student option only for exceptions (a different daily amount, or opting a specific student out).

.. note::

	Turning **Paying Canteen?** off for a student or class does not delete any of their payment history — it only stops new payments from being recorded for them going forward.

A staff member can be restricted to only setting up classes assigned to them (configured per class); an administrator (or a staff member with no such restriction) can set up any class.


.. _canteen_payment:

Recording Canteen Payments
**************************

Navigate to **Canteen > Record Payment**. A student must already be set up for canteen (see above) before a payment can be recorded for them — the amount charged is the one configured during Setup, not entered manually here.

Record Payment for a Single Student
=====================================

1. Search for the student using the name or student ID search box
2. Select the student and confirm the date, term, and academic year
3. Click **Record Payment**

Record Payment for an Entire Class
=====================================

1. Select the class from the class dropdown
2. Select the date
3. Click **Record Class Payment** — this records a payment, at each student's own configured daily amount, for every student in the class who is set up for canteen and hasn't already been marked as paid for that date

.. tip::

	Use the class payment option at the start of a school day when most of the class pays canteen, then handle latecomers or exceptions individually afterward.

A student cannot be paid twice for the same day — attempting to record a second payment for a date already recorded is rejected.


.. _canteen_tracking:

Collections Tracking
*********************

Navigate to **Canteen > Tracking** to see, for a class and date range, which school days each student paid for and which they didn't — a grid view intended for following up on students who are falling behind, rather than a totals report (see Reports, below, for totals).

Filter by:

* **Class**
* **Period**: a preset range (e.g. this week, this month) or a custom **From**/**To** date range
* **Term/Semester** and **Year**


.. _canteen_reports:

Canteen Payment Reports
***********************

Navigate to **Canteen > Reports** to view canteen collection totals.

Filter the report by:

* **Campus**: restrict to a campus (for multi-campus setups)
* **Class**: restrict to a particular class
* **Period**: a preset range or a custom **From**/**To** date range
* **Term/Semester** and **Year**

The report shows collection totals per student/class for the selected period. Click **Print** to generate a printable report.

.. note::

	The Canteen module is separate from the **Store & Inventory** (Point of Sale) module — Canteen records recurring daily meal payments against a per-student configured amount, while Store & Inventory records one-off item sales from a school shop or store. See :doc:`/manage/finance` for Store & Inventory. The two share no data or configuration with each other.
