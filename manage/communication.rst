Communication
#############

sERP v1.11 introduces a suite of in-app communication tools that complement the existing SMS functionality. These tools enable two-way communication between administrators, teachers, students, and parents — all within the platform.

Access the Communication tools from the **Communication** section in the main navigation menu.

.. note::

	Access to the communication tools for **staff** users is controlled by the following access roles, which must be assigned by an administrator via :ref:`Manage Users <users_edit>`:

	* **Messaging** (role 94) — required for staff to send and receive in-app messages
	* **Forums** (role 95) — required for staff to view and participate in discussion forums
	* **Conferences** (role 96) — required for staff to schedule and manage parent-teacher conferences

	Students and parents have access to the features relevant to them (Messages, Conferences for parents, Forums) automatically through their portal accounts, without requiring these roles.

.. |edit_icon| image:: ../images/pencil.png
.. |delete_icon| image:: ../images/trash.png


.. _communication_messaging:

Messages
*********

The in-app messaging system allows direct communication between any two users in sERP — across user types (staff, student, parent).

Inbox
=====

Navigate to **Communication > Messages** to view your inbox. Messages are grouped by thread (conversation). Unread message counts are displayed as a badge next to the Messages menu item.

The inbox table shows:

* Thread subject
* The other participant(s) in the conversation
* Last message preview
* Date of last message
* Read/unread status

Click a thread to open and read the full conversation.

Composing a New Message
=======================

1. Click **Compose** from the Messages inbox
2. Select the **Recipient Type** (Staff, Student, or Parent)
3. Select the specific recipient from the dropdown (populated based on type)
4. Enter the **Subject**
5. Type your message in the body
6. Click **Send**

Replying to a Message
=====================

1. Open a thread from the inbox
2. Type your reply in the reply box at the bottom of the thread
3. Click **Send Reply**

All replies are appended to the same thread for a coherent conversation history.

.. note::

	Messages are accessible to all user types: staff can message students, parents, or other staff; students and parents can message staff. Portal users (students and parents) access the Messages section from the **Communication** menu in their portal.


.. _communication_conferences:

Parent-Teacher Conferences
**************************

The Conferences module enables school staff to schedule and manage parent-teacher meetings.

Scheduling a Conference
=======================

1. Navigate to **Communication > Conferences**
2. Click **Schedule Conference**
3. Fill in:

	* **Teacher**: select the participating teacher
	* **Parent**: select the parent/guardian
	* **Student**: select the relevant student
	* **Date & Time**: the scheduled date and time
	* **Duration**: expected meeting duration in minutes
	* **Topic**: subject or agenda for the meeting

4. Click **Schedule**

The conference appears in the list with status **Pending**. The parent can view their scheduled conferences from the parent portal.

Conference Status
=================

Conferences progress through the following statuses:

* **Pending**: scheduled but not yet confirmed
* **Confirmed**: confirmed by the teacher or admin
* **Completed**: the meeting has taken place
* **Cancelled**: the meeting was cancelled

Use the action buttons in the conference list to update the status.

.. tip::

	Parents can see their upcoming conferences under **Communication > Conferences** in the parent portal, alongside the scheduled date, time, teacher name, and topic.


.. _communication_feedback:

Feedback
*********

The Feedback module allows students and parents to submit structured ratings and comments on teachers and school services.

Submitting Feedback (Student/Parent Portal)
============================================

1. From the portal, navigate to **Communication > Feedback**
2. Select the **Feedback Type** (e.g. Teacher Feedback, General School Feedback)
3. If providing teacher feedback, select the teacher from the dropdown
4. Select a **Rating** from 1 (Poor) to 5 (Excellent)
5. Enter your **Comments**
6. Click **Submit Feedback**

Viewing Feedback (Admin)
========================

Navigate to **Communication > Feedback** from the admin panel to view all feedback submissions.

The feedback table shows:

* Submitter (student or parent)
* Feedback type and target (e.g. specific teacher)
* Rating
* Comments
* Date submitted

.. note::

	Feedback scores feed directly into the :ref:`Teacher Performance Report <reports_teacher_performance>`, which aggregates average ratings per teacher across the school.


.. _communication_forums:

Discussion Forums
*****************

Discussion forums enable collaborative conversations between staff, students, and parents, grouped by class or subject.

Viewing Threads
===============

Navigate to **Communication > Forums** to see the list of discussion threads. Filter threads by class or subject using the dropdown filters. Pinned threads appear at the top of the list.

Each thread shows:

* Thread title
* Posted by (user name and type)
* Class/subject scope
* Number of replies
* Date of last post

Starting a New Thread
=====================

1. Click **New Thread**
2. Select the **Class** and/or **Subject** scope (optional — leave blank for a school-wide thread)
3. Enter the thread **Title**
4. Write the opening post
5. Click **Post Thread**

Replying to a Thread
====================

1. Click on a thread title to open it
2. Read the posts in the thread
3. Enter your reply in the text box at the bottom
4. Click **Post Reply**

Moderation
==========

Administrator and staff users can:

* **Pin** a thread to keep it at the top of the list
* **Lock** a thread to prevent further replies
* **Delete** a post or thread

.. note::

	Students and parents can participate in forums from their respective portals via the **Communication > Forums** menu item.
