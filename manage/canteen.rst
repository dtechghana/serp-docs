Canteen Module
##############

The Canteen module allows you to record and track canteen payments for students. It also includes a Point of Sale (PoS) sub-module for managing a school store or tuck shop. Both can be accessed via the main navigation — the Canteen module requires the Canteen access role to be enabled for your user account.

.. note::

	Canteen must first be enabled in **Settings > Student Settings > Canteen** before it appears in the navigation menu.

.. |edit_icon| image:: ../images/pencil.png
.. |delete_icon| image:: ../images/trash.png


.. _canteen_payment:

Recording Canteen Payments
**************************

Navigate to **Canteen** to record payments for student canteen usage.

Record Payment for a Single Student
=====================================

1. Search for the student using the name or student ID search box
2. Select the student from the results
3. Enter the payment amount and date
4. Click **Record Payment**

Record Payment for an Entire Class
=====================================

1. Select the class from the class dropdown
2. Enter the payment amount (applied uniformly to all students in the class)
3. Select the date
4. Click **Record Class Payment**

.. tip::

	Use the class payment option at the start of a term or week when all students in a class pay the same canteen fee.


.. _canteen_reports:

Canteen Payment Reports
***********************

Navigate to **Canteen > Reports** to view canteen payment records.

Filter the report by:

* **Date range**: from and to dates
* **Class**: restrict to a particular class
* **Campus**: restrict to a campus (for multi-campus setups)

The report shows the student name, class, date, amount, and recording staff member. Click **Print** to generate a printable report.


.. _canteen_pos:

Store & Inventory (PoS)
***********************

The PoS sub-module manages a school store or canteen inventory. Navigate to **Finance > Store & Inventory** to access it.

Adding Items
============

1. Navigate to **Store & Inventory > Items**
2. Click **Add Item**
3. Enter the item name, category, unit price, and opening stock quantity
4. Click **Save**

Recording a Sale
================

1. Navigate to **Store & Inventory > New Sale**
2. Search for and select items; enter quantities
3. Select the customer (student or walk-in)
4. Click **Complete Sale** — stock is automatically decremented

Sales Reports
=============

Navigate to **Store & Inventory > Sales Report** to view sales by date range, item, or campus. Staff with the store access role can only view their own campus sales.

.. note::

	Stock levels are updated in real time as sales are recorded. Low-stock items can be identified from the Items list.
