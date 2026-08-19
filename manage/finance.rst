Finance Module
##############

The following sections provides information surrounding the management of financial aspects of sERP.

.. |edit_icon| image:: ../images/pencil.png
.. |delete_icon| image:: ../images/trash.png
.. |info_icon| image:: ../images/info.png
.. |money_icon| image:: ../images/money.png


.. _finance_set_fees:

Fees Configuration
******************

sERP offers various options for configuring and managing fees. Fees can be configured for individual students, one or more classes; based on student status and per :ref:`billable item <settings_fee_items>`.

1. From the :ref:`main nagivation menu <setup_layout>`, go to Finance -> Set Fees
2. Select the Academic Year and Term/Semester from the respective drop-down menus
3. Click on "Submit"


Once the term/semester and academic year have been specified, you can then go ahead to configure fees from the "Set Fees" pane as follows:

1. Select criteria


Settings fees by class
======================

	* Select option "One or more classes" from the drop-down menu next to "Set fees for"
	* From the drop-down menu next to "Class(se)", check the classes you wish to configure fees for
	* Select the student status from the drop-down menu next to "Status". You may also select "All Students" to configure fees for all status types


Set fees by individual student
==============================

You can set fees for an individual student which is different from fees set for the rest of the class.

	* Select option "Individual Student" from the drop-down menu next to "Set fees for"
	* From the drop-down menu next to "Student's Class", select the class the student is enrolled in
	* From the drop-down menu next to "Student", select the student


2. Select a billable item from the drop-down menu next to "Fee Item" to configure fees for that item
3. Specify the fee amount for that item
4. Click "Set Fees"

.. tip::

	The above steps need to be performed for each billable item


Deleting set fees
=================

**For Individual Items**

1. From the "Current Fees" pane, click on delete (X) next to the item you wish to remove fees for
2. Confirm deletion of fees


**For Entire Class**

1.  From the "Current Fees" pane, click on "clear set fees for this class" (|delete_icon|) from the "Actions" column for the class
2. Confirm deletion of fees

.. note::

	It isn't advisable to delete set fees if payment has been recorded against the item(s), as this has an effect on student's bill and payment history.

.. warning::
	Deleting data is an irreversible process


.


.. _finance_prepare_bill:

Student Billing
***************

This section covers information about billing management. sERP provides robust and flexible tools for preparing, updating and organizing students' bills. The billing management section can be accessed from the :ref:`main nagivation menu <setup_layout>` by going to Finance -> Prepare Bill.


1. Select billing criteria

Billing entire class
====================

	* Select option "By Class" from the drop-down menu next to "Show"
	* Select the class you wish to prepare bill for from the drop-down menu next to "Class"
	* Select the student status from the drop-down menu next to "Status". You may also select "All Students" to configure fees for all status types


Billing individual student
==========================

	* Select option "By Student" from the drop-down menu next to "Show"
	* Enter the ID of the student you wish to prepare a bill for in the box next to "Student ID"

2. Select Academic Year and Term/Semester from the releant drop-down menu
3. Click "Submit"


.. hint::

	sERP updates and populates the academic calendar period based on the selected class


4. From the "Bill Summary" pane, do one of the following:

	* Click on "Bill Student" from the "Actions" column for the student to prepare/update that student's bill, OR
	* Select one or more students by checking the check box for the student(s) and click "Generate/Update Bills"


Adding Custom Bills
===================

sERP allows you to add up to three (3) extra items to a student's bill, in addition to predefined :ref:`billable items <settings_fee_items>`. This is particularly useful in a scenario where it is required to bill a student for an item that typically wouldn't be added to a students bill.


.. note::

	1. :ref:`Fees <finance_set_fees>` would had to have been set for a class in order to be able to prepare bill for students in that class
	2. Each time any changes are made to the price of billable items, or student financial status, bills would have to be re-prepared/updated in order for student bill to reflect the changes


.


.. _finance_payment:

Payments
********

This section covers information about capturing payments. sERP allows for recording and generating receipts two (2) kinds of payments, namely:

* **Bill payments**: payments against bills that have previously been prepared in sERP
* **Non-bill payments**: payments received for items that haven't necessarily been billed

Bill payments
=============

1. From the :ref:`main nagivation menu <setup_layout>`, go to Finance -> Bill Payment
2. Select the following:

	* **Class**: the class in which the student you are recording payment for is enrolled
	* **Academic Year**: the academic year for which the payment was made
	* **Term/Semester**: the academic term for which the payment was made
	* **Student**: select the student you are recording payment for from the class register

3. Click "Load" to display payment options and retreive student's financial records, which will be displayed in "Student Bill Summary" pane
4. Enter the following:

	* **Amount**: the amount received from the student
	* **Date paid**: the date in which the payment was made. Defaults to current date
	* **Apply to Bille Item(s)**: you may specify whether to apply payment to specific items, or simply select "Select All" to have sERP distribute the received amount to billed items automatically
	* **Payment Type**: the mode of payment
	* **Remarks**: enter a description for the payment being recorded

5. Click "Record Payment"
6. From the payment recorded confirmation page, click on "Generate Receipt" to prepare receipt for the payment


Non-bill Payments
=================

1. From the :ref:`main nagivation menu <setup_layout>`, go to Finance -> Non-bill Payment
2. Select the following:

	* **Class**: the class in which the student you are recording payment for is enrolled
	* **Academic Year**: the academic year for which the payment was made
	* **Term/Semester**: the academic term for which the payment was made
	* **Student**: select the student you are recording payment for from the class register

3. Click "Load" to display payment options
4. Enter the following:

	* **Amount**: the amount received from the student
	* **Date paid**: the date in which the payment was made. Defaults to current date
	* **Payment Type**: the mode of payment
	* **Remarks**: enter a description for the payment being recorded

5. Click "Record Payment"
6. From the payment recorded confirmation page, click on "Generate Receipt" to prepare receipt for the payment


.


Tracking and Managing Payments
******************************

sERP offers detailed and payment reporting. This sections covers how to obtain information about payments captured in sERP.

Viewing recent payments
=======================

From the :ref:`main nagivation menu <setup_layout>`, go to Finance -> View Payments. The "Fees Payments" pane displays a table showing the last 100 payments recorded in sERP, with the following information:

* Payment date
* Student details
* Amount paid
* Receipt number
* Academic year
* Term/Semester
* Paid to: details of staff who recorded the payment
* Date and time recorded
* Actions: view receipt, cancel payment and view payment history



Filtering payments
==================

1. Select filtering criteria (date or receipt number) from the drop-down menu next to "Filter By"
2. Enter date range or receipt no depending on selected criteria
3. Click "List Payments"


Intelligent search
------------------

The "Fees Payment" pane provides an intelligent search box which can be used to filter payment results. Simply type the receipt number, student name/ID, date or any other criteria into the box next to "Search" to locate the item quicker.


Payment reports
===============

sERP's payment reporting module offers even more comprehensive payment reporting and analytics, including additional search filters and options.

.. hint::

	Checkout our :ref:`payment reports <reports_finance_payments>` guide for more information


Viewing payment receipts
========================

From the "Fees Payment" pane:

* Click on the receipt number from the "Receipt No" column for the payment whose receipt you wish to view OR

* Click on "View Receipt" (|info_icon|) from the actions column for the payment whose receipt you wish to view


Cancelling a payment
====================

Admin and other authorized users may cancel a payment. To cancel a payment:

1. From the "Fees Payment" pane, click on "Cancel Payment" (**X**) from the "Actions column for the payment you wish to cancel
2. Review the payment details to verify
3. In the box beneath "Reason for cancelling Payment", enter the reason why you wish to cancel the payment
4. Click "Cancel Payment"


.


Debtors List
************

This section provides information about using sERP's debtors list feature, which enables you track all fee debtors.

1. From the :ref:`main nagivation menu <setup_layout>`, go to Finance -> Debtors List
2. Select the following:

	* **Academic Year**: academic year for which you wish to view debtors
	* **Term/Semester**: academic term/semester for which you wish to view debtors
	* **List By**: optionally, select criteria for which you want to query debtors:

		* By Class: select the class you wish to view report for
		* By Campus: select the campus you wish to restrict report to

	* **Filter By**: optionally, select report filters:

		* Amount paid: specify amount and criteria
		* Percentage paid: specify percentage and criteria

	* **Past Students**: optionally, select whether to include or exclude past students from the list, or only show past students
	* **Withdrawn Students**: optionally, select whether to include or exclude withdrawn students from the list, or only show withdrawn students

3. Click "List Debtors"


.


Bill Reminders
**************

Bill reminders enable you communicate to parents whose wards are owing fees by sending payment reminders. Reminders can be sent either via SMS or print. The bill reminder feature can be accessed from the :ref:`main nagivation menu <setup_layout>` by going to Finance -> Bill Reminder.

1. Select the following:

	* **Academic Year**: academic year for which you wish to view debtors
	* **Term/Semester**: academic term/semester for which you wish to view debtors
	* **List Debtors By**: optionally, select criteria for which you want to query debtors:

		* By Class: select the class you wish to view report for
		* By Campus: select the campus you wish to restrict report to

	* **Filter By**: optionally, select report filters:

		* Amount paid: specify amount and criteria
		* Percentage paid: specify percentage and criteria

2. Click on "List Debtors" to generate/view debtor's list
3. From the "Debtors" pane, select the student(s) whom you wish to send a reminder, by checking the respective check box
4. Click one of the following buttons:

	* **Continue**: draft and print payment reminder
	* **Send SMS Instead**: draft and send personalized payment reminder using the SMS module

	.. hint::

		Checkout our :ref:`SMS Bill Reminder guide <sms_bill_reminder>` for more information


.


Income and Expenditure
**********************

This feature provides a summary of accrued income (payments plus supplementary income) and expenditure incurred by your school. It also provides tools for recording expenditure and supplementary income (i.e. income received from alternative sources other than school fees and non-billed payments).

The income and expenditure feature can be accessed from the :ref:`main nagivation menu <setup_layout>` by going to Finance -> Income & Expenditure.

Balance
=======

This displays the current cash balance - essentially the difference between income and expenditure.


Adding Supplementary Income
===========================

1. From the "Income Breakdown" pane, click on "View/Add Supplementary Income" (|money_icon|)
2. Enter the following:

	* Payment date
	* Amount
	* Description for the payment

3. Click "Record Income"


Editing Supplementary Income
=============================

Admin users may edit a previously recorded supplementary income entry.

1. From the supplementary income table, click the edit (|edit_icon|) icon for the entry
2. Update the date, amount, and/or description in the modal dialog
3. Click "Save Changes"


Deleting Supplementary Income
==============================

1. From the supplementary income table, click the delete (|delete_icon|) icon for the entry
2. Confirm the deletion

.. warning::
	Deleting data is an irreversible process. Only admin users can delete supplementary income records.


Viewing and Recording Expenditure
=================================

From the "Expenditure Breakdown" pane, click on "View/Record Expenditure" (|edit_icon|) to access the expenditure management section.

Viewing Expenditure
-------------------

The "Expenditure History" pane displays the expenditure table, which displays a list of recorded expenditure under the following headings:

* Date
* Description
* Amount
* Payment Type

Recording Expenditure
---------------------

1. From the "Record Expenditure" pane, enter the following information:

	* Date
	* Amount
	* Expenditure Category
	* **Payment Type**: select the mode of payment — Cash, Cheque, Bank Transfer, or Mobile Money

		.. note::
			* Selecting **Cheque** reveals an additional "Cheque Number" field
			* Selecting **Bank Transfer** reveals an additional "Bank" field
			* Selecting **Mobile Money** reveals an additional "MoMo Reference / Transaction ID" field for recording the transaction reference

	* Expenditure Description

2. Click "Record Expenditure"


.. hint::

	sERP offers detailed reporting on both payments and expenditure. See our :ref:`Finance Reports <reports_finance>` guide for more information


.. _finance_online_payments:

Online Payments 
***************

In addition to USSD mobile money payments, sERP supports online card payments. This allows parents and students to pay school fees using debit/credit cards.

.. note::

	In **sERP v2.0** and later, online payments are processed through `Paystack <https://paystack.com>`_. There is no payment method selection step — submitting the form redirects to Paystack's own hosted checkout page, where the payer chooses card, mobile money, or bank transfer.

Initiating an Online Payment (Admin)
======================================

1. Navigate to **Finance > Online Payments**
2. Search for and select the student
3. Enter the payment amount
4. Select the payment method (v1.11 only — see note above for v2.0 and later)
5. Click **Initiate Payment**

A unique payment reference is generated and the payment request is sent to the payment gateway. The status updates automatically once the gateway confirms the transaction.

Initiating an Online Payment (Parent/Student Portal)
======================================================

Parents and students can initiate online payments directly from their portal:

1. Navigate to **Finance > Fees & Payments** (or **Bills** from the portal menu)
2. Click the **Pay Online** button
3. Complete the payment form with the amount and payment method
4. Submit — the portal redirects to the hosted payment page

Successful payments are automatically applied to the student's fee account and a payment record is created.

.. note::

	The USSD payment platform (``*789*87#``) handles mobile money payments (MTN MoMo, Telecel Cash, AirtelTigo Money). The online integration extends this to card-based and digital wallet payments.


.. _finance_fee_reminders:

Automated Fee Reminders
***********************

sERP can send automated weekly SMS fee reminders to parents of students with outstanding balances.

To enable automated reminders:

1. Navigate to **Settings > SMS Settings**
2. Toggle **Send automated weekly fee reminder SMS to parents?** to ON

When enabled, the reminder script runs every Monday at 8am and sends SMS to all parents with a balance due, using the existing SMS integration.

.. note::

	SMS API credentials must also be configured on the same **Settings > SMS Settings** page for automated reminders to function.


.. _finance_fixed_assets:

Fixed Assets Register
*********************

.. note::

   This feature is available in **sERP v2.0** and later.

The Fixed Assets Register tracks every physical asset owned by the school — from buildings and vehicles to ICT equipment and laboratory apparatus. Each asset is assigned a unique code, linked to a category and optionally a department, and is subject to a computed depreciation schedule.

Asset Categories
================

Before registering assets, define categories under **Fixed Assets > Categories**. Each category specifies a default useful life (years) and a default depreciation rate.

Seven categories are pre-seeded: Buildings, Vehicles, ICT Equipment, Fixtures & Fittings, Furniture, Land (non-depreciating), and Laboratory Equipment.

Adding an Asset
===============

1. Navigate to **Fixed Assets > Register** and click **Add Asset**.
2. Complete the form: name, category, department (optional), location, serial number, supplier, acquisition date, cost, salvage value, useful life, and depreciation method (Straight-Line or Declining Balance).
3. The asset code is auto-generated (e.g. ``FA-ICT-0001``).

Depreciation
============

Navigate to **Fixed Assets > Depreciation** to compute annual depreciation for all active assets. Depreciation can be run per-asset or in bulk for a given calendar year. Results are stored and show opening value, depreciation charge, and closing book value.

Disposals
=========

When an asset is retired, navigate to its detail view and select **Dispose**. Specify the disposal type (Sale, Write-Off, or Damaged), the disposal date, and any proceeds received. The asset status is updated automatically.

Reports
=======

The **Fixed Assets > Reports** page provides a summary of asset values by category, a full register listing, and a depreciation history per asset.


.. _finance_accounting:

Double-Entry Accounting
***********************

.. note::

   This feature is available in **sERP v2.0** and later.

sERP includes a complete double-entry bookkeeping system. Financial transactions from fee payments, POS/store sales, canteen, and payroll are posted to the general ledger automatically, with manual journal entry also supported.

Chart of Accounts
=================

Navigate to **Accounting > Chart of Accounts** to view and manage accounts. Accounts are classified as Asset, Liability, Equity, Revenue, or Expense and carry a normal balance direction (debit or credit). System accounts (used in auto-posting) are marked and cannot be deleted.

A default Chart of Accounts is seeded on installation and can be extended to suit the school's needs.

Financial Periods
=================

Create accounting periods under **Accounting > Periods** (e.g. "Jan–Mar 2025"). Periods can be closed to prevent further posting.

Journals
========

Five journal types are supported:

- **Receipt** — income received (fee payments, POS sales)
- **Payment** — expenditure paid out
- **Contra** — internal transfers between accounts
- **Journal** — general manual adjustments
- **Payroll** — monthly payroll entries

Each journal entry must balance (total debits = total credits). A unique reference is auto-generated per entry.

Journals can be reversed, which creates a mirror entry with opposite debits/credits.

Auto-Posting
============

The following transactions post journal entries automatically when processed:

- Fee payments (billable and non-billable)
- POS / store sales
- Canteen payments
- Expenditure records
- Monthly payroll (via **Accounting > Sync > Payroll**)

Any posting failures (e.g. missing COA account) are logged under **Accounting > Posting Failures** and can be resolved manually.

Reports
=======

- **Trial Balance** — debit/credit totals per account for a date range
- **Income Statement** — revenue minus expenses (surplus/deficit)
- **Balance Sheet** — assets, liabilities, and equity as at a date
- **General Ledger** — running balance for a single account
- **Budget vs Actual** — budgeted vs actual amounts per period

Data can be exported to **CSV** (compatible with Excel) or **IIF** (Intuit Interchange Format for QuickBooks import).

