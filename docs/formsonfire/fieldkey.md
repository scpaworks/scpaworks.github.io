---
title: Field Names Reference
has_children: false
parent: Forms on Fire
nav_order: 1
---

# Field Names Reference

This acts as a reference for what each field name represents. When data is exported from Forms on Fire, it is labeled with its field name, a short code that uniquely identifies that field. Unfortunately, this isn't always the most descriptive label.

See below to see what question each field name corresponds to. Questions labeled (PAGE), (INFO), or (ACTION) are static fields, and do not receive any data from users.

To quickly search, try opening your browser's Find in Page search by pressing `ctrl + F`. Then, type the name of the field as it appears in the spreadsheet.

## Built-In Forms on Fire Fields
<table class="tg">
<thead>
  <tr>
    <th class="tg-0lax">Field Name</th>
    <th class="tg-0lax">Description</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">RowId</td>
    <td class="tg-0lax">Numerical ID for each data entry.</td>
  </tr>
  <tr>
    <td class="tg-0lax">Completed</td>
    <td class="tg-0lax">Date of submission completion.</td>
  </tr>
  <tr>
    <td class="tg-0lax">CompletedBy</td>
    <td class="tg-0lax">Name of the ACCOUNT that completed the form. **This is not the submitting participant's name!**</td>
  </tr>
  <tr>
    <td class="tg-0lax">Started</td>
    <td class="tg-0lax">Date and time the form was started.</td>
  </tr>
  <tr>
    <td class="tg-0lax">Received</td>
    <td class="tg-0lax">Date and time the submission was received by the database.</td>
  </tr>
  <tr>
    <td class="tg-0lax">CompletedAt</td>
    <td class="tg-0lax">Coordinates where the participant completed the form. This can be ignored.</td>
  </tr>
</tbody>
</table>

<!-- CUSTOM DATA FIELDS -->
## Registration Data Fields

<table class="tg">
<thead>
  <tr>
    <th class="tg-0lax">Field Name</th>
    <th class="tg-0lax">Question</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0lax">personalInfo</td>
    <td class="tg-0lax">(PAGE) Personal Information</td>
  </tr>
  <tr>
    <td class="tg-0lax">instructions</td>
    <td class="tg-0lax">(INFO) Instructions to user to fill out the form.</td>
  </tr>
  <tr>
    <td class="tg-0lax">dateCurrent</td>
    <td class="tg-0lax">Date</td>
  </tr>
  <tr>
    <td class="tg-0lax">name</td>
    <td class="tg-0lax">Name</td>
  </tr>
  <tr>
    <td class="tg-0lax">personalID</td>
    <td class="tg-0lax">Personal Identification Number</td>
  </tr>
  <tr>
    <td class="tg-0lax">county</td>
    <td class="tg-0lax">In which PA county are you located right now?</td>
  </tr>
  <tr>
    <td class="tg-0lax">streetAddress</td>
    <td class="tg-0lax">Street Address</td>
  </tr>
  <tr>
    <td class="tg-0lax">city</td>
    <td class="tg-0lax">City</td>
  </tr>
  <tr>
    <td class="tg-0lax">state</td>
    <td class="tg-0lax">State</td>
  </tr>
  <tr>
    <td class="tg-0lax">zipCode</td>
    <td class="tg-0lax">ZIP Code</td>
  </tr>
  <tr>
    <td class="tg-0lax">telephone</td>
    <td class="tg-0lax">Telephone</td>
  </tr>
  <tr>
    <td class="tg-0lax">email</td>
    <td class="tg-0lax">Email Address</td>
  </tr>
  <tr>
    <td class="tg-0lax">socialMedia</td>
    <td class="tg-0lax">LinkedIn / Facebook URL</td>
  </tr>
  <tr>
    <td class="tg-0lax">Nav1</td>
    <td class="tg-0lax">(ACTION) Navigation buttons for Page 1</td>
  </tr>
  <tr>
    <td class="tg-0lax">demographics</td>
    <td class="tg-0lax">(PAGE) Demographic Information</td>
  </tr>
  <tr>
    <td class="tg-0lax">race</td>
    <td class="tg-0lax">Race / Ethnicity</td>
  </tr>
  <tr>
    <td class="tg-0lax">otherRace</td>
    <td class="tg-0lax">Other race/ethnicity</td>
  </tr>
  <tr>
    <td class="tg-0lax">citizenStatus</td>
    <td class="tg-0lax">Are you a US Citizen?</td>
  </tr>
  <tr>
    <td class="tg-0lax">alienNumber</td>
    <td class="tg-0lax">ALIEN Registration Number</td>
  </tr>
  <tr>
    <td class="tg-0lax">returningCitizen</td>
    <td class="tg-0lax">Are you a returning citizen (ex-offender)?</td>
  </tr>
  <tr>
    <td class="tg-0lax">selectiveService</td>
    <td class="tg-0lax">Are you registered with Selective Service?</td>
  </tr>
  <tr>
    <td class="tg-0lax">veteran</td>
    <td class="tg-0lax">Are you a veteran or active Service member?</td>
  </tr>
  <tr>
    <td class="tg-0lax">Nav2</td>
    <td class="tg-0lax">(ACTION) Navigation buttons for Page 2</td>
  </tr>
  <tr>
    <td class="tg-0lax">serviceRecord</td>
    <td class="tg-0lax">(PAGE) Service Record</td>
  </tr>
  <tr>
    <td class="tg-0lax">branchOfService</td>
    <td class="tg-0lax">Branch of Service</td>
  </tr>
  <tr>
    <td class="tg-0lax">typeOfService</td>
    <td class="tg-0lax">Type of Service</td>
  </tr>
  <tr>
    <td class="tg-0lax">discharged</td>
    <td class="tg-0lax">Have you been discharged?</td>
  </tr>
  <tr>
    <td class="tg-0lax">dischargeType</td>
    <td class="tg-0lax">Discharge Type</td>
  </tr>
  <tr>
    <td class="tg-0lax">entryDate</td>
    <td class="tg-0lax">Entry Date</td>
  </tr>
  <tr>
    <td class="tg-0lax">dischargeDate</td>
    <td class="tg-0lax">Discharge Date</td>
  </tr>
  <tr>
    <td class="tg-0lax">serviceDisability</td>
    <td class="tg-0lax">Do you have a Service-connected Disability Rating?</td>
  </tr>
  <tr>
    <td class="tg-0lax">serviceDisabilityRating</td>
    <td class="tg-0lax">Disability Rating Percentage</td>
  </tr>
  <tr>
    <td class="tg-0lax">militarySpouseConditions</td>
    <td class="tg-0lax">Are you the spouse of a veteran who</td>
  </tr>
  <tr>
    <td class="tg-0lax">militarySpouseMarried</td>
    <td class="tg-0lax">Are you still married to the veteran referenced in the previous question?</td>
  </tr>
  <tr>
    <td class="tg-0lax">Nav3</td>
    <td class="tg-0lax">(ACTION) Navigation buttons for Page 3</td>
  </tr>
  <tr>
    <td class="tg-0lax">visitReason</td>
    <td class="tg-0lax">(PAGE) Reason for Visit</td>
  </tr>
  <tr>
    <td class="tg-0lax">visitReasonChoice</td>
    <td class="tg-0lax">Why are you here today?</td>
  </tr>
  <tr>
    <td class="tg-0lax">workshop</td>
    <td class="tg-0lax">Workshop:</td>
  </tr>
  <tr>
    <td class="tg-0lax">workshopCustom</td>
    <td class="tg-0lax">Other workshop:</td>
  </tr>
  <tr>
    <td class="tg-0lax">appointment</td>
    <td class="tg-0lax">Appointment:</td>
  </tr>
  <tr>
    <td class="tg-0lax">otherReason</td>
    <td class="tg-0lax">Other:</td>
  </tr>
  <tr>
    <td class="tg-0lax">employerVisit</td>
    <td class="tg-0lax">Are you here to see a specific employer?</td>
  </tr>
  <tr>
    <td class="tg-0lax">specificEmployer</td>
    <td class="tg-0lax">Employer:</td>
  </tr>
  <tr>
    <td class="tg-0lax">circumstancesChoice</td>
    <td class="tg-0lax">Please check all that apply:</td>
  </tr>
  <tr>
    <td class="tg-0lax">Nav4</td>
    <td class="tg-0lax">(ACTION) Navigation buttons for Page 4</td>
  </tr>
  <tr>
    <td class="tg-0lax">confirmSubmission</td>
    <td class="tg-0lax">(PAGE) Confirm Submission</td>
  </tr>
  <tr>
    <td class="tg-0lax">submitConfirmInfo</td>
    <td class="tg-0lax">(INFO) Instructions for submission</td>
  </tr>
  <tr>
    <td class="tg-0lax">cwds1</td>
    <td class="tg-0lax">(INFO) CWDS registration instructions part 1</td>
  </tr>
  <tr>
    <td class="tg-0lax">cwds2</td>
    <td class="tg-0lax">(INFO) CWDS registration instructions part 2</td>
  </tr>
  <tr>
    <td class="tg-0lax">Nav5</td>
    <td class="tg-0lax">(ACTION) Navigation and submission buttons for Page 5</td>
  </tr>
</tbody>
</table>
