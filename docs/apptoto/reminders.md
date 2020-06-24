---
title: Reminders
parent: Apptoto
has_children: false
nav_order: 4
---

# Apptoto Reminders

## Table of Contents
1. <a href="#what-are-reminders">What are Reminders?</a>
2. <a href="#user-interface">User Interface</a>

<!-- WHAT ARE REMINDERS? -->
## What are Reminders?

Apptoto provides reminder functionality through **Auto Messages.** These are SMS (text) messages, emails, or voice calls that Apptoto automatically sends to participants of an event at predetermined times. Any number of Auto Messages can be sent out, but note that each Auto Message consumes one (1) account message credit.

There are three types of Auto Messages in Apptoto:
* **Initial/Booking** - sent at some time after the participant books an appointment
* **Reminder** - sent at some time before the appointment occurs
* **Followup** - sent at some time after the appointment is completed

**Rules** can be defined for reminders. These allow certain reminders to be sent out when specific content is included in an appointment. For instance, we can define a custom data type in an event as follows:

<a class="image" href="/assets/apptoto/customData.png"><img src="/assets/apptoto/customData.png" /></a>

Then, we can create reminders using Rules that are sent only when that appointment contains the `type: class` data field.

<a class="image" href="/assets/apptoto/rules.png"><img src="/assets/apptoto/rules.png" /></a>

<hr class="divider" />

<!-- USER INTERFACE -->
## User Interface

### Auto Messages and Rules Interface

Below is the interface of the Auto Messages page.

<a class="image" href="/assets/apptoto/remindersInterface.png"><img src="/assets/apptoto/remindersInterface.png" /></a>

Let's go over each section in the image above.

1. **Switch between rule and settings view** - allows switching between *Rules and Messages* view and the *Advanced Settings* view. In *Advanced Settings,* you can adjust options pertaining to message delivery.
2. **Save or discard edits** - the *Save* button saves edits to Auto Messages, while *Revert* discards any changes.
3. **Create new Auto Message* - using either button, you can create a new Auto Message of any type. This opens the Auto Message Editor.
4. **Create and view rules** - created rules appear here. For each rule, the logical statement used to filter events can be seen directly below the rule's title. New rules can also be added by clicking *New Rule.*
5. **Initial Auto Messages** - Auto Message reminders sent after a client has booked or been assigned to an appointment.
6. **Reminder Auto Messages** - Auto Message reminders sent before an appointment occurs.
     1. **When reminder occurs** - the time interval selected for the Auto Message
     2. **Reminder name and days when reminder is active** - displays the name given to the Auto Message and the days the reminder will be sent out.
     3. **Toggle reminder on/off** - toggles whether a reminder will send. An *off* setting will prevent that particular Auto-Message from sending.
     4. **Reminder Actions Menu** - allows quick access to functions for Auto Messages. This includes editing, cloning (copying), deletion, and adding a new Auto Message directly below the selected message.
7. **Followup Auto Messages** - Auto Message reminders sent after an appointment has ended.

### Message Editor

The message editor is where all Auto Messages are configured. Auto Messages require the following data:
* **Name** - a descriptive name for the reminder
* **Purpose** - whether the reminder is Initial/Booking, Reminder, or Followup
* **When** - time interval when reminder should be sent
     * **Time of Day** - this determines when Auto Messages are allowed to be sent. This should always be set to **Any** or a **Custom Schedule** that encompasses the entire day. Auto Messages will NOT send outside of hours specified.
* **Body** - the message contents. This can include text and *Fields.* Fields allow you to populate data from the appointment, such as the time of day or participant name.

<a class="image" href="/assets/apptoto/messageEditor1.png"><img src="/assets/apptoto/messageEditor2.png" /></a>

You can insert Fields in your message body using the **Insert Field** button. To add a field, simply select the category you'd like, and click the desired field value to insert it into your message.

<a class="image" href="/assets/apptoto/messageEditor3.png"><img src="/assets/apptoto/messageEditor3.png" /></a>

Fields always appear in your message body surrounded by curly braces. For example: `{% raw %} {{ user.email }} {% endraw %}` represents the attendee's email address.

<a class="image" href="/assets/apptoto/messageEditor5.png"><img src="/assets/apptoto/messageEditor5.png" /></a>

## How to Make New Reminders

### SMS Reminder

SMS reminders are text messages that are sent to appointment attendee's phone numbers. Attendees can respond to these messages to preform actions (confirm/reschedule/cancel appointments, for example) or communicate with relevant staff.

1. Click one of the **New Message** buttons and click **Add SMS**
2. Fill out the information about your reminder
     1. Name - enter a descriptive name for the reminder
     2. Purpose - select whether this reminder should be Initial/Booking, Reminder, or Followup
     3. When - enter the time before or after the appointment that this reminder should send
          1. **IMPORTANT** - make sure the **Time of day** is set to either *Any* or a *Custom Schedule* encompassing the entire day

          <a class="image" href="/assets/apptoto/messageEditor4.png"><img src="/assets/apptoto/messageEditor4.png" /></a>

     4. Body - enter the contents of the message. Fields can be added with the **Insert Field** button.
3. You can click Preview to see what your message will look like to the client

     <a class="image" href="/assets/apptoto/messageEditor2.png"><img src="/assets/apptoto/messageEditor2.png" /></a>

4. Click Done to save your Auto Message

### Email Reminder

Email reminders are email messages sent to participants' email addresses.

1. Click one of the **New Message** buttons and select **Add Email**
2. Fill out the information about your email reminder:
     1. Name - enter a descriptive name for the reminder
     2. Purpose - select whether this reminder should be Initial/Booking, Reminder, or Followup
     3. When - enter the time before or after the appointment that this reminder should send
          1. **IMPORTANT** - make sure the **Time of day** is set to either *Any* or a *Custom Schedule* encompassing the entire day

          <a class="image" href="/assets/apptoto/messageEditor4.png"><img src="/assets/apptoto/messageEditor4.png" /></a>

     4. Subject - enter the subject line of the email message
     5. Body - enter the contents of your email message. You can use the WYSIWYG editor to format text inside your message. Fields can also be inserted using the **Insert Field** button
3. Click Preview to view how your message will appear to the recipient
4. Click Done to save your Auto Message


### Voice Call Reminder

Voice call reminders are audio messages sent to clients' phones. This can either take the form of a pre-recorded MP3/WAV file, or a **Text-to-Speech (TTS)** voice.

1. Click one of the **New Message** buttons and choose **Add Call**
2. Fill out the information about your call reminder:
     1. Name - enter a descriptive name for the reminder
     2. Purpose - select whether this reminder should be Initial/Booking, Reminder, or Followup
     3. When - enter the time before or after the appointment that this reminder should send
          1. **IMPORTANT** - make sure the **Time of day** is set to either *Any* or a *Custom Schedule* encompassing the entire day

          <a class="image" href="/assets/apptoto/messageEditor4.png"><img src="/assets/apptoto/messageEditor4.png" /></a>

     4. Body - **If using TTS**, enter the message for your client in the body. This message will be translated into speech and sent to the client
     5. TTS Voice - select whether to use the female or male TTS voice
6. **If you are using a recorded MP3 or WAV message:**
     1. click the **Upload MP3/WAV** button
     2. Select your MP3 or WAV recording file
     3. You will know your upload completed successfully when you see two things:
          1. You see the **Upload completed** notification in the top-right of Apptoto

               <a class="image" href="/assets/apptoto/audioUpload.png"<img src="/assets/apptoto/audioUpload.png" /></a>

          1. The body of the reminder has changed to include the URL to your uploaded file

               <a class="image" href="/assets/apptoto/audioUpload2.png"><img src="/assets/apptoto/audioUpload2.png" /></a>
