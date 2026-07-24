SMS Module
##########

sERP integrates with the Darrel Technologies A2P SMS platform to deliver outbound SMS notifications and bulk messaging directly from within the system. To use SMS features, your SMS API credentials (API ID and API Key) must be configured in **Settings > SMS Settings**.

.. note::

	SMS messages are billed per unit based on your SMS agreement with Darrel Technologies. Each message sent is logged in the Sent Messages section.

.. |edit_icon| image:: ../images/pencil.png
.. |delete_icon| image:: ../images/trash.png


.. _sms_bulk:

Bulk SMS
********

Navigate to **SMS > Send SMS** to compose and send a bulk SMS message to a group of recipients.

1. Select the **Recipient Group** from the dropdown:

	* **All Students** — all currently enrolled students' parents/guardians
	* **All Staff** — all registered staff members
	* **Class** — parents of students in a specific class
	* **Year Group** — parents of students in a specific year group
	* **Campus** — parents of students in a specific campus
	* **Section** — parents of students in a specific section

2. Compose the message in the text area. A character counter shows the current length and number of SMS units that will be used
3. Review the estimated recipient count and cost
4. Click **Send**

.. tip::

	Use the **Preview** option to review the message before sending. Personalised messages (including the student's name) can be composed for individual sends.


.. _sms_bill_reminder:

Bill Reminders
**************

Navigate to **SMS > Bill Reminder** to send fee payment reminder messages to parents of students with outstanding balances.

1. Apply filters to narrow the recipient list:

	* **Class**: restrict to a particular class
	* **Campus**: restrict to a campus
	* **Section**: restrict to a section
	* **Amount Paid Filter**: include only students who have paid less than a specified amount or percentage

2. Review the resulting debtor list — this shows the student name, class, bill amount, amount paid, and balance
3. Compose the reminder message, or use the default template
4. Click **Send Reminder** to dispatch SMS to all listed parents

Alternatively, click **Print Reminders** to generate printed reminder notes instead of SMS.

.. note::

	Automated weekly fee reminders can also be configured via the cron-based reminder system — see :ref:`Automated Fee Reminders <finance_fee_reminders>`. The toggle lives in **Settings > SMS Settings**, alongside the other automated SMS triggers.


.. _sms_terminal_reports:

SMS Terminal Reports
********************

Navigate to **SMS > Terminal Reports** to send students' progress report summaries to parents via SMS at the end of a term.

1. Select the **Class** and **Academic Term**
2. sERP compiles a summary of each student's performance (total marks, position, aggregate) and formats it as an SMS message
3. Review the preview — confirm the number of recipients and SMS units
4. Click **Send** to dispatch

.. note::

	SMS terminal reports are sent to the mobile numbers registered for the student's parent/guardian in sERP.


.. _sms_payment_notifications:

Payment Notifications
*********************

sERP can automatically send an SMS confirmation to parents when a bill payment is recorded. This is configured in **Settings > SMS Settings**:

* **Payment Notification**: toggle ON to enable automatic SMS on every payment recorded
* **SMS Sender ID**: the name displayed as the sender on the parent's phone (subject to network carrier approval)

When enabled, each successful payment triggers an SMS to the registered parent/guardian number with the payment amount, balance, and receipt reference.


.. _sms_attendance_alerts:

Absence Notifications
*********************

When attendance is recorded and a student is marked absent, sERP can automatically send an SMS notification to the student's registered parent or guardian. This feature is active when SMS is configured and a guardian mobile number is available for the student.

The notification message includes the student's name, the date of absence, and a prompt to contact the school if the absence was unexpected.


.. _sms_sent:

Sent Messages
*************

Navigate to **SMS > Sent Messages** to view a log of all outbound SMS messages.

The log shows:

* Date and time sent
* Sender ID used
* Message content (truncated)
* Number of recipients
* Delivery status

Use the search field to filter by recipient number, message content, or date range. Individual message records can be expanded to view the full content and delivery details.
