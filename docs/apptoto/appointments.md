---
title: Appointments
parent: Apptoto
has_children: false
nav_order: 2
---

# Apptoto Appointments

## Table of Contents
1. <a href="#user-interface">User Interface</a>
1. <a href="#how-to-create-an-appointment">Create Appointment</a>
1. <a href="#how-to-edit-an-appointment">Edit Appointment</a>
1. <a href="#showhide-calendars">Show/Hide Calendars</a>
1. <a href="#change-the-date">Change the Date</a>
1. <a href="#import-appointments-from-file">Import Appointments from File</a>

<!-- USER INTERFACE -->
## User Interface

Below is the interface for managing appointments in Apptoto.

<a class="image" href="/assets/apptoto/appointmentsInterface.png"><img src="/assets/apptoto/appointmentsInterface.png" /></a>

<hr class="divider">

<!-- MAKE AN APPOINTMENT -->
## How to Create an Appointment

1. Click the Add Appt. button.
1. In the Appointment Editor, enter the information for your appointment.

<a class="image" href="/assets/apptoto/appointmentEditor.png"><img src="/assets/apptoto/appointmentEditor.png" /></a>

1. Click Save to save the appointment details. You will be prompted to enter participants.
1. Enter any participants you want to add to the event.
1. If you'd like to add the event to a Sign Up Page:
     1. In the Appointment Editor's right-hand sidebar, click **Add to Existing Signup Page**.
     1. Select the Sign Up Page that corresponds to your event's location.
1. Review the event information, and hit close to finish editing.

<a class="image" href="/assets/apptoto/appointmentEditor2.png"><img src="/assets/apptoto/appointmentEditor2.png" /></a>

<hr class="divider">

<!-- EDIT AN APPOINTMENT -->
## How to Edit an Appointment

1. Click on the name of the appointment.
1. Edit the contents of the appointment in the Appointment Editor.

<hr class="divider">

<!-- SHOW/HIDE CALENDARS -->
## Show/Hide Calendars

1. Click the name of the calendar corresponding to the location you'd like to select.
1. All other calendars will be hidden from your view.
1. To disable filtering, click the **all** link next to the Calendars label.

<a class="image" href="/assets/apptoto/changeCalendarView.png"><img src="/assets/apptoto/changeCalendarView.png" /></a>

<hr class="divider">

<!-- CHANGE THE DATE -->
## Change the Date

1. Using the calendar navigation controls on the left side of the Appointments page, select the date you'd like to view.
1. You can quickly view the current or next day's date by clicking the **Go to today &#124; tomorrow** button below the calendar controls.

<a class="image" href="/assets/apptoto/calendarControls.png"><img src="/assets/apptoto/calendarControls.png" /></a>

<hr class="divider">

<!-- IMPORT APPOINTMENTS -->
## Import Appointments from File

You can bulk import appointments from a CSV or XML file. CSV (comma-separated values) files can be created from Excel spreadsheets.

### Suggested Layout

| Appointment type | Full Name | Date | Start Time | End Time | Phone | Email |
|------------------|-----------|------|------------|----------|-------|-------|
| Customer Service Bootcamp | John Smith | 6/12/2020 | 9:00AM | 10:00AM | 123-555-6789 | jsmith@email.com |
| Resume Writing Workshop | Adam Green | 6/12/2020 | 11:00AM | 12:00PM | 717-555-1234 | agreen@email.com |
| Social Media Workshop | Ashley Stauffer | 6/12/2020 | 2:00PM | 3:00PM | 333-555-7777 | ashstauffer@email.com |

<a href="/assets/apptoto/sampleCSV.csv">**Download the sample CSV file.**</a>

### Uploading Procedure
1. Click on the Import button at the top-right of the page.
1. You can drag and drop the CSV file into the file dropbox, or select **Choose File** to select the file from Windows Explorer.
     1. Alternatively, you can copy and paste the contents of your CSV file into the text box below the upload.
1. If you uploaded a file, click **Upload File** to submit your file for processing. If you pasted the contents of your CSV file, click **Upload Contents** instead.

<a class="image" href="/assets/apptoto/csvUpload.jpg"><img src="/assets/apptoto/csvUpload.jpg" /></a>

1. Once Apptoto has accepted your file, you will be prompted to map CSV columns to Apptoto fields. For each column in your CSV, use the dropdown box to select the matching Apptoto field.
     1. i.e. for the Full Name column in your CSV, you would select Full Name in the dropdown.

<a class="image" href="/assets/apptoto/importCSV.jpg"><img src="/assets/apptoto/importCSV.jpg" /></a>

1. (Optional) You may be prompted to set "repeatable sync options." If these appear, it is recommended that you use the following options:
     1. **Avoid duplicating appointments: ON**
     1. **Update existing appointments if found: ON**
     1. **Delete appointments if they were removed: OFF**

1. Under the **Step 3. Provide Default Values (or template) for required fields**, make sure you have the correct calendar selected. The selected calendar should correspond with the location of the appointments.
1. (Optional) You may be prompted to create unique appointment identifiers for your import. This happens when the CSV contains insufficient information for Apptoto to index it automatically.
     1. Take a look at the table under the **Step 1. Map columns to fields** heading. The bottom row shows the field names of each column.

     <a class="image" href="/assets/apptoto/tableFieldNames.png"><img src="/assets/apptoto/tableFieldNames.png" /></a>

     1. You must enter a combination of these fields in the Unique Appt Id field under Step 3 of the importing process. Here is a suggested format:

          {% raw %}
          {{ title }} - {{ name }} - {{ date }} - {{ time }}
          {% endraw %}

1. Click **Import** to begin importing your appointment data!
1. You will see the following screen if the import has completed successfully. If the upload does not succeed, you will see an error message. Read the message to determine the issue, fix it, and then restart the upload process to try again. Alternatively, if only some rows have issues, you can choose to skip uploading just those rows.
1. Should you need to, you have the option to undo a successful import by clicking **Undo Import**.

<a class="image" href="/assets/apptoto/importComplete.png"><img src="/assets/apptoto/importComplete.png" /></a>