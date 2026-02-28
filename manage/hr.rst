HR Module
#########

The HR module covers all aspects of staff management, including staff records, payroll processing, and tax and regulatory compliance. Access it from the main navigation menu under **HR**.

.. |edit_icon| image:: ../images/pencil.png
.. |delete_icon| image:: ../images/trash.png
.. |info_icon| image:: ../images/info.png


.. _hr_departments:

Departments
***********

Departments allow you to group staff by their organisational unit (e.g. Administration, Teaching, Accounts).

Add Department
==============

1. From the "Add Department" pane, enter the department name
2. Click **Add Department**

Modifying & Deleting Departments
=================================

Use the edit (|edit_icon|) and delete (|delete_icon|) icons in the departments list to modify or remove a department. A department cannot be deleted if staff members are currently assigned to it.


.. _hr_add_staff:

Add Staff
*********

To register a new staff member in sERP:

1. Navigate to **HR > Add Staff**
2. Fill in the staff details form:

	.. note::

		* **First Name / Surname**: staff's full legal name
		* **Staff ID**: auto-generated based on the configured :ref:`staff ID prefix <setup_staff_prefix>`, or entered manually
		* **Department**: select the staff member's department
		* **Staff Type / Designation**: select the staff member's role (e.g. Teacher, Administrator)
		* **Employment Date**: the date the staff member was employed
		* **Mobile Number**: used for SMS notifications and MFA
		* **Email**: staff email address
		* **Bank Name / Account Number**: required for payroll bank advice generation
		* **Basic Salary**: monthly gross salary before deductions
		* **TIN**: Tax Identification Number (required for PAYE compliance)
		* **SSNIT Number**: Social Security number (required for SSNIT contributions)
		* **SSNIT Contributor**: toggle whether SSNIT deductions apply to this staff member

3. Click **Add Staff** to save

.. tip::

	A user account must also be created for any staff member who needs to log in to sERP. See :doc:`/setup/users` for instructions.


.. _hr_staff_list:

Staff List
**********

Navigate to **HR > Staff List** to view all registered staff members. The list shows each staff member's ID, name, department, designation, and action buttons.

Click a staff member's name or the info icon (|info_icon|) to view their full profile, including personal details, employment details, payroll history, and uploaded documents.

Modifying Staff Details
=======================

1. From the Staff List, click the edit icon (|edit_icon|) for the staff member
2. Update the relevant fields
3. Click **Save Changes**

Staff Documents
===============

Staff documents (appointment letters, certificates, etc.) can be uploaded from the staff details page under the **Documents** tab. Accepted formats: jpg, jpeg, png, pdf, doc, docx, xls, xlsx.


.. _hr_payroll:

Staff Payroll
*************

Navigate to **HR > Staff Payroll** to generate the monthly payroll.

1. Select the **Month** and **Year** for the payroll run
2. Click **Generate Payroll** — sERP computes gross salary, all deductions, and net pay for each active staff member
3. Review the payroll summary table
4. Click **Print** or **Download** to export the payroll report

Payroll is calculated as follows::

	Net Pay = Basic Salary + Allowances − PAYE − SSNIT (Employee Share) − Trustee − Custom Deductions

.. note::

	Payroll data is archived monthly. To view a previously generated payroll, navigate to **HR > Staff Payroll** and select the relevant month and year from the archive dropdown.


.. _hr_salary_deductions:

Salary Deductions
*****************

Custom salary deductions (e.g. loans, advances, union dues) can be configured per staff member.

1. Navigate to **HR > Salary Deductions**
2. Select the staff member from the dropdown
3. Enter the deduction description and amount
4. Click **Add Deduction**

Deductions are applied automatically in the next payroll run. Remove a deduction using the delete icon (|delete_icon|) once it is no longer applicable.


.. _hr_bank_advice:

Bank Advice
***********

Navigate to **HR > Bank Advice** to generate a bank transfer instruction list for salary disbursement.

1. Select the payroll month and year
2. Click **Generate Bank Advice**
3. The report lists each staff member's name, account number, bank, and net pay amount — formatted for submission to your bank

Click **Print** to produce a printable bank advice document with school letterhead.


.. _hr_paye:

PAYE Returns
************

Navigate to **HR > PAYE Returns** to generate the monthly Pay As You Earn tax return report in compliance with GRA requirements.

1. Select the month and year
2. Click **Generate PAYE Report**
3. The report lists each staff member's gross income, chargeable income, applicable tax reliefs, and PAYE deducted
4. Click **Download Excel** to export in a format suitable for submission to GRA

.. note::

	Tax rates are configured in **Settings > HR Settings > Income Tax Rates** and should be updated whenever GRA publishes revised rates.


.. _hr_trustee:

Trustee Contributions
*********************

Navigate to **HR > Trustee Contributions** to generate the monthly employer trustee (Tier 2 / Tier 3 pension) contribution report.

1. Select the month and year
2. Click **Generate Report**
3. The report shows each staff member's employer and employee trustee contribution amounts

The trustee remittance rate is configured in **Settings > HR Settings > Trustee Remittance Rate**.


.. _hr_ssnit:

SSNIT Contributions
*******************

Navigate to **HR > SSNIT Contributions** to generate the monthly Social Security contribution report for submission to SSNIT.

1. Select the month and year
2. Click **Generate Report**
3. The report lists each SSNIT-contributing staff member's employee contribution (5.5%) and employer contribution (13%)
4. Click **Download Excel** to export in the format required by SSNIT

.. note::

	Only staff members with **SSNIT Contributor** toggled on are included in this report.


.. _hr_paye_calculator:

PAYE Calculator
***************

Navigate to **HR > PAYE Calculator** to calculate the PAYE liability for a given gross income amount, based on the currently configured GRA tax bands. This is a reference tool only and does not affect any payroll records.

Enter a gross salary amount and click **Calculate** to see the computed taxable income, applicable reliefs, and PAYE due.
