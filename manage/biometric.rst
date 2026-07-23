Biometric Attendance
####################

.. note::

   This feature is available in **sERP v2.1** and later.

sERP can capture student and staff attendance automatically from biometric devices — fingerprint, facial recognition, or card-based terminals — in addition to manual entry (see :ref:`Student Attendance <student_attendance>` and :ref:`Staff Attendance <hr_staff_attendance>`). Access biometric administration from the main navigation menu under **Biometric**.

.. note::

   Manually-recorded attendance always takes precedence. If a class or staff member's attendance for a given date has already been recorded manually, biometric capture will not overwrite it.


.. _biometric_integration_options:

Integration Options
********************

There are three ways to connect a biometric device to sERP, and a school can use any combination of them:

Direct Device Push
==================

The device sends attendance records straight to sERP as they happen, if it has its own internet connectivity and supports a configurable push destination. This gives near real-time attendance updates.

Local Relay Agent
==================

A small program runs on a computer within the school's network, communicates with the device locally, and periodically forwards attendance records to sERP. This is the recommended option when the device itself isn't (or shouldn't be) directly exposed to the internet.

CSV / Excel Import
===================

If neither of the above is available, punch records exported from the device as a spreadsheet can be uploaded and imported manually — see :ref:`biometric_csv_import` below. This uses the same underlying pipeline as the live options, so imported records are processed identically.


.. _biometric_devices:

Managing Devices
******************

Navigate to **Biometric > Devices** to register and manage biometric terminals.

Registering a Device
=======================

1. Click **Register Device** and complete the form: device name, type (Fingerprint, Face, Card, or Other), whether it's used for students, staff, or both, its physical location, and its integration mode (Local Relay Agent, Direct Device Push, or CSV Import Only).
2. Click **Register Device**. A one-time **Device Key** and **Secret** are shown — copy these into the device or relay agent's configuration immediately.

.. warning::

   The device secret is shown only once and cannot be retrieved again. If it's lost, use **Rotate Secret** to generate a new one — the device or relay agent will need to be reconfigured with the new value.

Rotating a Secret
===================

If a device's secret is compromised or lost, click the rotate icon next to it in the devices list and confirm. A new secret is generated and shown once; update the device/relay configuration accordingly.

Enabling / Disabling a Device
================================

Use the power icon next to a device to temporarily disable it (rejecting further punches) without deleting its history, or re-enable it later.


.. _biometric_mapping:

Mapping Device Users
***********************

A biometric device identifies people by its own internal user ID, which won't match a student's ID or a staff member's ID in sERP. Navigate to **Biometric > Mapping** to link them.

Any device user ID that has sent a punch but isn't yet linked to a student or staff record appears in this list.

1. For each unmapped entry, choose **Student** or **Staff** and enter the corresponding sERP ID.
2. Click **Map**.

Once mapped, any attendance punches already received for that device user ID are automatically resolved — there's no need to wait for the device to send new punches.


.. _biometric_settings:

Settings
**********

Navigate to **Settings > Biometric Attendance** to configure:

* **Enable biometric attendance** — master on/off switch for the whole feature.
* **Automatically resolve punches into attendance records** — when enabled, an automated process (running roughly hourly) turns received punches into attendance and staff attendance records. Disable this if you'd prefer to review punches before they're applied.
* **Staff late-arrival cutoff time** — a staff member whose first punch of the day is after this time is marked *Late* instead of *Present*.
* **Notify staff by SMS when marked late** — sends an SMS to a staff member's registered mobile number when biometric capture marks them late.


.. _biometric_csv_import:

CSV Import
************

Navigate to **Biometric > Import CSV** to import a punch export from a device as a spreadsheet.

1. Choose which device to attribute the punches to (or leave as **CSV Import (generic)**), and select your file (.xlsx, .xls, .csv, or .ods).
2. Click **Next: Map Columns**, then match each required field — **External User ID**, **Punch Date/Time**, and optionally **Type** (In/Out) — to the corresponding column in your file.
3. Click **Run Import**.

The results screen shows how many rows imported successfully and how many failed, with a downloadable CSV of any failed rows and the reason for each failure (e.g. a missing user ID or an unrecognised date format).

Imported punches are processed by the same automatic resolution described in :ref:`biometric_settings` above — there is no separate step for CSV-imported data.
