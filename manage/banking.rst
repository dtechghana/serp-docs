Banking
#######

The Banking module allows you to manage the school's bank accounts and track financial transactions — including cheque payments, deposits, and cash transfers — directly within sERP.

Access the Banking module from **Finance > Banking** in the main navigation menu. Requires the **Banking** access role (role 51).

.. |edit_icon| image:: ../images/pencil.png
.. |delete_icon| image:: ../images/trash.png


.. _banking_accounts:

Managing Bank Accounts
**********************

Navigate to **Finance > Banking** to view the list of registered bank accounts.

Each account displays:

* Bank name
* Account name
* Account number
* Current balance

**Adding a Bank Account**

1. From the Banking list page, click **Add Bank Account**
2. Enter the following:

	* **Bank**: the name of the bank
	* **Account Name**: the name on the account
	* **Account Number**: the bank account number (numeric)

3. Click **Save**


**Removing a Bank Account**

From the bank accounts list, click the delete (|delete_icon|) button for the account you wish to remove and confirm.

.. warning::
	Deleting a bank account is irreversible and will remove all associated transaction records.


.. _banking_transactions:

Transaction Tracking
********************

Click on a bank account from the list to open its **Transaction Tracking** view. This shows all recorded transactions for the selected account within a given date range, along with the opening and closing balances.

**Filtering by date range**

Use the date range fields at the top of the transaction list to filter transactions by a specific period. Click **Filter** to apply.

**Recording a Cheque Payment**

1. From the transaction view, click the **Write Cheque** icon in the toolbar
2. Enter the cheque details (payee, amount, cheque number, date, description)
3. Click **Save**

**Recording a Deposit**

1. Click the **Enter Deposit** icon in the toolbar
2. Enter the deposit details (amount, date, description)
3. Click **Save**

**Recording a Cash Transfer**

1. Click the **Cash Transfer** icon in the toolbar
2. Enter the transfer details (amount, destination account, date, description)
3. Click **Save**

**Finding a Cheque**

Use the **Find Cheque** icon in the toolbar to search for a specific cheque by number.

**Printing / Exporting a Statement**

From the transaction toolbar, use:

* The **Print Statement** icon to print the current transaction list
* The **Export Statement** icon to download a PDF of the statement
