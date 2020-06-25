---
title: Tools
parent: Apptoto
has_children: false
nav_order: 5
---

# Apptoto Tools

## Table of Contents
1. <a href="#contacts">Contacts</a>
     1. How to Add New Contacts
     2. How to Edit Existing Contacts
     3. How to Bulk Import New Contacts
1. <a href="#charts-and-reports">Charts and Reports</a>
1. <a href="#consent">Consent</a>
1. <a href="#log">Log</a>

<!-- Contacts -->
## Contacts

All contacts in Apptoto can be viewed on the Contacts page under the Tools section of Apptoto. Contacts can be part of multiple calendars, such as Apptoto or Google. Contacts contained in the address book can be quickly added to appointments.

<a class="image" href="/assets/apptoto/contacts.png"><img src="/assets/apptoto/contacts.png" /></a>

### How to Add New Contacts

1. Click the **Add Contact** button on the top-right of the Contacts page.
2. Enter the individual's contact information.
     1. **Address Book** - select the address book to store this contact in.
     2. **Auto Match:** - toggles whether this particular contact should be auto-populated in appointments.
     2. **Name** - the contact's full name.
     3. **Phone Numbers** - click **Add phone number** and enter the contact's phone number. Enter as many phone numbers for the contact as desired.
     4. **Email Addresses* - click **Add email address* and enter the contact's email address. Enter as many email addresses for the contact as desired.
     5. **ZIP Code** - enter the ZIP code of the client's primary location. This is for time zone determination.
     6. **Notes** - enter any notes about the client.
     7. **Preferences** - using the drop-down boxes, you can indicate if this contact has already opted-out of SMS, call, or email reminders.
     8. **External Id** - a unique identifier you can give the contact. Not necessary except in more advanced use-cases.
3. Click **Save** to add the new contact to the address book.

### How to Edit Existing Contacts

1. Search for the desired contact using the search bar at the top of the Contacts page.
2. Once the client is located, click the **Edit** button next to their row.
3. Modify the contact's information as needed.
4. Click **Save** to keep your changes.

<a class="image" href="/assets/apptoto/contactEdit.png"><img src="/assets/apptoto/contactEdit.png" /></a>

### How to Bulk Import New Contacts

You can bulk import appointments from a CSV or XML file. CSV (comma-separated values) files can be created from Excel spreadsheets.

#### Suggested CSV Layout

<table class="tg">
<thead>
  <tr>
    <th class="tg-0lax">Name</th>
    <th class="tg-0lax">Phone</th>
    <th class="tg-0lax">Email</th>
    <th class="tg-0lax">ZIP</th>
    <th class="tg-0lax">Notes</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">Leia Organa</td>
    <td class="tg-0lax">717-555-3374</td>
    <td class="tg-0lax">lorgana@email.com</td>
    <td class="tg-0lax">17101</td>
    <td class="tg-0lax">TEST CONTACT</td>
  </tr>
  <tr>
    <td class="tg-0lax">Han Solo</td>
    <td class="tg-0lax">410-555-8549</td>
    <td class="tg-0lax">hsolo@email.com</td>
    <td class="tg-0lax">21787</td>
    <td class="tg-0lax">TEST CONTACT</td>
  </tr>
  <tr>
    <td class="tg-0lax">Obi-Wan Kenobi</td>
    <td class="tg-0lax">717-555-9531</td>
    <td class="tg-0lax">owkenobi@email.com</td>
    <td class="tg-0lax">17325</td>
    <td class="tg-0lax">TEST CONTACT</td>
  </tr>
  <tr>
    <td class="tg-0lax">Qui-Gon Jinn</td>
    <td class="tg-0lax">717-555-0463</td>
    <td class="tg-0lax">qgjinn@email.com</td>
    <td class="tg-0lax">17012</td>
    <td class="tg-0lax">TEST CONTACT</td>
  </tr>
  <tr>
    <td class="tg-0lax">Rey Skywalker</td>
    <td class="tg-0lax">717-555-4296</td>
    <td class="tg-0lax">rskywalker@email.com</td>
    <td class="tg-0lax">17101</td>
    <td class="tg-0lax">TEST CONTACT</td>
  </tr>
  <tr>
    <td class="tg-0lax">Ahsoka Tano</td>
    <td class="tg-0lax">717-555-2986</td>
    <td class="tg-0lax">atano@email.com</td>
    <td class="tg-0lax">17340</td>
    <td class="tg-0lax">TEST CONTACT</td>
  </tr>
</tbody>
</table>

<a href="/assets/apptoto/contacts.csv">**Download the sample CSV file.**</a>

### Uploading Procedure
1. Click on the **Import Contacts** button at the top-right of the page.
1. You can drag and drop the CSV file into the file dropbox, or select **Choose File** to select the file from Windows Explorer.
     1. Alternatively, you can copy and paste the contents of your CSV file into the text box below the upload.
1. If you uploaded a file, click **Upload File** to submit your file for processing. If you pasted the contents of your CSV file, click **Upload Contents** instead.

     <a class="image" href="/assets/apptoto/csvUpload.jpg"><img src="/assets/apptoto/csvUpload.jpg" /></a>

1. Once Apptoto has accepted your file, you will be prompted to map CSV columns to Apptoto fields. For each column in your CSV, use the dropdown box to select the matching Apptoto field.
     1. i.e. for the Full Name column in your CSV, you would select Full Name in the dropdown.
     2. If you used the sample CSV file's format, there should be no need to adjust the default import settings.

     <a class="image" href="/assets/apptoto/importContacts.png"><img src="/assets/apptoto/importContacts.png" /></a>

1. (Optional) You may be prompted to set "repeatable sync options." If these appear, it is recommended that you use the following options:
     1. **Avoid duplicating contacts: ON**
     1. **Update existing contacts if found: OFF**
     1. **Delete contacts if they were removed: OFF**

1. Select the correct address book for this import. This is where the contacts will be stored. It is recommended that you use the Apptoto address book.
1. Click **Import** to begin importing your contact list.
1. You will see the following screen if the import has completed successfully. If the upload does not succeed, you will see an error message. Read the message to determine the issue, fix it, and then restart the upload process to try again. Alternatively, if only some rows have issues, you can choose to skip uploading just those rows.
1. Should you need to, you have the option to undo a successful import by clicking **Undo Import**.

<a class="image" href="/assets/apptoto/importCompleteContacts.png"><img src="/assets/apptoto/importCompleteContacts.png" /></a>
<hr class="divider" />
