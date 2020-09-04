---
title: Triage Intake Process
parent: Apptoto
has_children: false
nav_order: 1
youtubeID: 5e5KW2xRzFo
---

# Triage Intake Process

## Contents
1. <a href="#process-diagram">Process Diagram</a>
2. <a href="#apptoto-scheduling-steps">Apptoto Scheduling Steps</a>
     1. <a href="#strongmethod-1-calendar-view-schedulingstrong">Method 1: Calendar View Scheduling</a>
     2. <a href="#strongmethod-2-bookingavailability-page-schedulingstrong">Method 2: Booking/Availability Page Scheduling</a>
3. <a href="#intake-process-video">Intake Process Video</a>
4. <a href="#setting-intake-navigator-availability">Setting Intake Navigator Availability</a>

## Process Diagram

<a href="/assets/apptoto/triageProcessPDF.pdf"><button type="button" name="button" class="btn">Download the PDF</button></a>

<div class="embed-container">
  <iframe
      src="/assets/apptoto/triageProcessPDF.pdf"
      width="50%"
      height="750px"
      frameborder="0"
      allowfullscreen="1"
  >
  Your browser does not support PDF viewing. Please download the PDF to view it.
  </iframe>
</div>

<hr class="divider" />

## Apptoto Scheduling Steps

There are two primary scheduling methods:
* **Calendar view scheduling** - book the appointment the traditional way through the Apptoto calendar interface
* **Booking/availability page scheduling** - book the appointment through a specific intake navigator's availability page

### **Method 1: Calendar View Scheduling**

Advantages:
* Can select from any intake navigator in the system when scheduling
* Allows rapid appointment scheduling & viewing of all scheduled appointments quickly

Disadvantages:
* Must know the availability of each intake navigator beforehand

**Steps:**

1. Log into the Apptoto portal. You will be automatically redirected to the Appointment Calendar view.
2. Click **+Add Appt**

     <a class="image" href="/assets/apptoto/triage1.png"><img src="/assets/apptoto/triage1.png" /></a>

3. Enter the appointment details in the fields. You can add the participant information to the event body to save time, and it will be automatically populated to the correct field. Click **Save** to keep your changes.

     <a class="image" href="/assets/apptoto/triage2.png"><img src="/assets/apptoto/triage2.png" /></a>
4. The event details and participant summary will show once you click **Save**. Review these details for accuracy, and then click **Close** to close the dialog. The appointment will appear in the calendar.

     <a class="image" href="/assets/apptoto/triage3.png"><img src="/assets/apptoto/triage3.png" /></a>

5. The appointment is booked and the participant will receive scheduled reminders!

### **Method 2: Booking/Availability Page Scheduling**

Advantages:
* Quickly see the availability of intake navigators in a visual format
* Easy to schedule appointments for a single intake navigator

Disadvantages:
* Can only see one intake navigator's page at a time
* Participant must do mobile authentication where they are texted a one-time code that must be entered into the system (this can be skipped if the participant does not have a cellphone)

**Steps:**

1. Open the URL of the intake navigator's availability page for which you are scheduling. Example URL: <code>{% raw %}intake_johnsmith.apptoto.com{% endraw %}</code>

     1. To find the URLs of all availability pages, click Booking Pages in the Apptoto main navigation to the left.

          <a class="image" href="/assets/apptoto/triage4.png"><img src="/assets/apptoto/triage4.png" /></a>

     2. You can open an availability page from the Booking Pages area by clicking its URL in the list.

          <a class="image" href="/assets/apptoto/triage5.png"><img src="/assets/apptoto/triage5.png" /></a>

2. Click a time that is available for the intake navigator and works for the participant. Available times are shown in green, while unavailabile times are shown in gray.

     <a class="image" href="/assets/apptoto/triage6.png"><img src="/assets/apptoto/triage6.png" /></a>

3. Enter the participant's phone number. If the participant does NOT have a cellphone, type "southcentral" to bypass phone authentication.
4. Enter the participant's name and email address into the fields. Review the appointment details at the top, and click **Book Now** to save the appointment.

     <a class="image" href="/assets/apptoto/triage7.png"><img src="/assets/apptoto/triage7.png" /></a>

5. The appointment summary page will appear. You can choose to reschedule or cancel the appointment from this page. If you are satisfied, click the back button on your browser *twice* to return to the availability page.

## Intake Process Video
{% include youtubePlayer.html id=page.youtubeID %}

## Setting Intake Navigator Availability

1. Click **Booking Pages** on the left-hand navigation menu.

     <a class="image" href="/assets/apptoto/intakeNav1.png"><img src="/assets/apptoto/intakeNav1.png" /></a>

2. Find the booking page that corresponds to the intake navigator you are setting availability for. The URL always follows the same format: <code>{% raw %}https://intake_NavigatorName.apptoto.com{% endraw %}</code>

3. Click the **Settings** button in the Actions column for the intake navigator's availability page. You will be taken to the Booking Page Details page.

     <a class="image" href="/assets/apptoto/intakeNav2.png"><img src="/assets/apptoto/intakeNav2.png" /></a>

4. Click Availability in the toolbar directly under the "Booking Page Details: intake_..." heading.

     <a class="image" href="/assets/apptoto/intakeNav3.png"><img src="/assets/apptoto/intakeNav3.png" /></a>

5. There are two sections to the availability settings. The first (shown below) allows setting available times and filtering events.

     <a class="image" href="/assets/apptoto/intakeNav4.png"><img src="/assets/apptoto/intakeNav4.png" /></a>

     You can use the fields at the bottom ("When" and "Ignore") to filter which events on your calendar count as busy. For example, if you have a weekly appointment called "Staff Meeting" you don't want to appear busy during, you can type "staff meeting" into the "Ignore" field.

6. The second section allows setting holidays. Any days specified will have no available appointment slots.

     <a class="image" href="/assets/apptoto/intakeNav5.png"><img src="/assets/apptoto/intakeNav5.png" /></a>

7. Once you are done setting availability, click **Save** to save your changes.
