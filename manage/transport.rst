Transport Management
#####################

.. note::

   This feature is available in **sERP v2**.

sERP's Transport module manages a school's vehicle fleet, drivers, routes, and the students assigned to each — with boarding safety and billing built in rather than run as separate systems. Access it from the main navigation menu under **Transport**.

Transport roles are granted per user under **Users > Edit User**, the same way as any other module: **Access Dashboard**, **Fleet & Driver Management**, **Route & Stop Planning / Student Allocation**, **Boarding Check-in**, **Fee Collection**, and **Reports** can be assigned independently, so (for example) gate staff can be given check-in access without any administrative visibility into the rest of the module.


.. _transport_vehicles:

Vehicles
********

Navigate to **Transport > Vehicles** to register and manage the fleet.

1. Click **Add Vehicle** and complete the form: **Registration No.**, **Make / Model**, **Seating Capacity**, **Fuel Type**, **Roadworthy Expiry**, **Insurance Expiry**, and **Next Service Date**.
2. Click **Save**.

A vehicle's **Status** can be set to inactive without deleting it — useful for a vehicle temporarily out of service.


.. _transport_drivers:

Drivers
*******

Navigate to **Transport > Drivers** to register drivers and assign them to vehicles.

Registering a Driver
======================

1. Click **Add Driver** and select the **Staff Member** this driver record corresponds to (the staff account must already exist — see :doc:`/manage/hr`).
2. Enter **License No.**, **License Class**, and **License Expiry**.
3. Click **Save**.

Assigning a Driver to a Vehicle
==================================

Each vehicle has one active driver at a time. From the drivers list, select a vehicle for a driver and confirm — this closes out their previous assignment (if any) and opens a new one, keeping a full assignment history rather than overwriting it.


.. _transport_routes:

Routes & Stops
**************

Navigate to **Transport > Routes** to plan routes, and from a route, its **Stops**.

1. Click **Add Route** and enter a **Route Name**, optional **Description**, and **Status**.
2. Open the route and click **Add Stop** for each stop along it, giving each a **Stop Name** and **Scheduled Time**. Stops can be reordered.


.. _transport_allocations:

Student Allocation & Manifests
*******************************

Navigate to **Transport > Student Allocations** to assign students to a vehicle, route, and stop.

1. Enter the **Student ID**, then select the **Route**, **Stop** (filtered to that route), **Vehicle**, and **Fee Zone**.
2. Click **Save**.

Re-allocating a student (e.g. after a route change) updates their existing allocation rather than creating a duplicate — a student has one active allocation at a time.

.. _transport_fee_exempt:

.. note::

   The **Exempt from Fee?** checkbox keeps a student on the route — their allocation is untouched, and they still appear on manifests and check-in — but bills them GH₵0 for transport instead of their zone's amount. Use this for a scholarship case or similar, rather than un-allocating the student.

**Manifest**: navigate to **Transport > Manifest** for a live, per-vehicle roster of every allocated student, generated from current allocations — there's nothing to separately prepare or refresh.


.. _transport_fee_zones:

Fee Zones & Billing
********************

Navigate to **Transport > Fee Zones** (under **Transport > Setup**) to define the distance/zone-based fee tiers available on the Student Allocations screen.

1. Click **Add Zone** and enter a **Zone Name** (e.g. "Zone A"), the **Amount (per term)**, and **Status**.
2. Click **Save**.

Transport fees are billed through the same Finance module as tuition — not a parallel system. A student's zone fee becomes an individual-student fee the moment they're allocated, and transport payments use the same payment screen, receipts, and reports as any other fee (see :ref:`finance_payment`), so they appear in the Debtors List and Payment History alongside everything else.


.. _transport_checkin:

Boarding Check-in & Alerts
****************************

Students board and alight either manually, from **Transport > Check-in**, or automatically via RFID/NFC — see :ref:`transport_devices` below. Both sources write to the same check-in record, so a vehicle's history is complete regardless of which method was used for a given tap.

**Manual check-in**: select the vehicle, then mark each student as boarded or deboarded from the manifest shown.

**Departed / Delayed broadcasts**: the **Mark Bus Departed** and **Mark Bus Delayed** buttons on the Check-in screen (also available from the paired tablet's Driver Console app — see below) send an immediate SMS to every allocated student's parent on that vehicle, independent of individual boarding check-ins.

.. note::

   Parent/admin SMS alerts for Transport must be switched on first, at **Settings > SMS Settings > Transport Alerts**. This is off by default, the same convention as every other SMS alert type.


.. _transport_devices:

RFID/NFC Check-in & Live GPS Tracking
****************************************

RFID/NFC boarding and live GPS tracking both run through one standardized device per vehicle: a ruggedized Android tablet (NFC + GPS + LTE) mounted in the vehicle, running the companion **Driver Console** app. NFC is the same 13.56MHz contactless technology as a transit or payment card, so this satisfies RFID check-in without any separate specialized reader hardware.

Registering a Device
=======================

Navigate to **Transport > Devices**.

1. Click **Register Device**, name it, and select the vehicle it's mounted in.
2. Click **Register Device**. A one-time **Device Key** and **Secret** are shown — these pair the Driver Console app on that tablet (either by scanning the QR code shown, or entering them manually in the app).

.. warning::

   The device secret is shown only once and cannot be retrieved again. If it's lost, rotate it from the devices list and reconfigure the Driver Console app with the new value.

A device can be temporarily disabled from the devices list without losing its history, the same as a biometric device (see :ref:`biometric_devices`).

Assigning Student Cards
===========================

Navigate to **Transport > Student NFC Cards** to link a physical card's UID to a student.

1. Enter the **Student ID** and the card's **Card UID**.
2. Click **Assign Card**.

A student has one active card at a time — assigning a new card automatically revokes their previous one. Click into the **Card UID** field and tap the card against a USB NFC reader in keyboard-wedge mode to fill it in automatically (the reader types the UID directly, no driver needed), or type the UID in by hand if one isn't available.

Live Map
===========

Navigate to **Transport > Live Map** for each vehicle's most recent GPS position, reported automatically by its paired tablet whenever its Driver Console app has a route in progress.


.. _transport_driver_console:

The Driver Console App
*************************

The Driver Console is a separate, dedicated app for the tablet mounted in each vehicle — not a role within the parent/student :doc:`sERP mobile app </manage/mobile-app>`, and not something a driver logs into with a personal account. Once paired to a registered device (see above), it authenticates as that device, not a user.

On the tablet, the Driver Console app provides:

* Continuous NFC scanning for boarding/deboarding taps, queued on the device and synced automatically — including after a connectivity gap, with nothing lost in the meantime.
* **Start Route** / **End Route**, which also fires the Departed broadcast and begins GPS reporting for the trip.
* **Bus Delayed**, sending the same broadcast as the Check-in screen's own button.
* Screen pinning, so the tablet stays on the Driver Console app and can't be navigated away from accidentally while mounted.

The app is installed by sideloading (it is not distributed through an app store, since it only ever runs on school-owned, mounted tablets) and is provisioned once per tablet.
