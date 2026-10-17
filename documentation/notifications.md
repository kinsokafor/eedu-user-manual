---
description: >-
  The emails, texts and in-app notifications eedu.ng sends, who gets each one, and how School Admins change the
  wording, switch messages on or off and check what was delivered.
icon: envelope-open-text
---

# Emails and notifications

eedu.ng tells people when something that concerns them happens: a result is published, a payment is received, a staff member is added, a test is set. Each message can go out three ways:

- **Email**, in your school's name, with your logo and colour.
- **SMS** (text), using your school's own bulk SMS account.
- **In-app**, under the **Notifications** bell (🔔) in the top bar.

Each message type has its own default ways of sending, and your school can change them (see [Changing the wording](#changing-the-wording-school-admins)).

## Who gets messages about a student

A student's account holds the family's contact details, so:

- **Emails and texts about a student go to the parent or guardian**, using the email address and phone number on the student's record. They're addressed to the parent by name when the record has one (Guardian, Father or Mother), otherwise to "Parent/Guardian of" the student.
- **In-app notifications go to the student**, under the bell in the student portal.

Keep the phone number on each student's record up to date: most parents are reached by SMS, because few student records have an email address.

## What eedu.ng sends

**Always sent** means the message can't be switched off, by the school or by the person. **Off until switched on** means the school must choose to send it.

### Accounts

| Message | Who gets it | Sent by default as | Notes |
|---|---|---|---|
| Welcome to a new school | The person who registers a school | Email, in-app | The first set-up steps and the trial end date. Always sent. |
| Welcome to new staff | A staff member added to the school | Email, in-app (SMS available) | Says who added them, their role and how to sign in. Always sent. |
| New student: portal access for parents | Parents | SMS, email | Carries the student's passcode. **Off until switched on.** |
| Password recovery code | Anyone who asks on the **forgot password?** page | Email | Sent straight away. Always sent. See [Forgotten password](getting-started.md#forgotten-password). |
| Password changed | The account owner | Email, in-app | Sent after a password is reset, in case it wasn't them. Always sent. |

### Staff

| Message | Who gets it | Sent by default as | Notes |
|---|---|---|---|
| Staff member added | School Admins and Portal Managers | Email, in-app | Not sent to the person who added the staff member. |
| Pastoral duty assigned | The staff member | Email, in-app | When a manager adds them to the pastoral team. |
| New counselling referral | Counsellors | Email, in-app | Says who referred, but nothing about the student. |
| New chat message | Staff | Email | A message or reply in **Message Center**. At most one email per conversation per day. |

### Results, lessons and tests

| Message | Who gets it | Sent by default as | Notes |
|---|---|---|---|
| Result published | Parents (email, SMS) and the student (in-app) | Email, SMS, in-app | Term and annual results. Publishing the same result again doesn't send it again. |
| CBT test published | Students of the class | In-app (email available) | With the opening and closing times. Not sent if the test is unpublished or closed first. |
| Assignment set | Students of the class | In-app (email available) | With the due date. |
| Lesson published | Students of the class | In-app | A lesson with a publish time is announced at that time. |
| Marked work returned | The student | In-app (email available) | With the score. |
| Timetable published | Students of the class | In-app | At most once a day per class. |

### Fees and payments

| Message | Who gets it | Sent by default as | Notes |
|---|---|---|---|
| New fee issued | Parents and students of the class | Email, in-app (SMS available) | Sent **10 minutes** after the fee is created, so a mistake can be fixed first. It uses the amount at that time, and nothing is sent if the fee is deleted. |
| Payment receipt | Parents and the student | Email, SMS, in-app | Every fee payment, at the bursary or through a virtual account. Always sent. |
| Wallet top-up receipt | Parents and the student | Email, SMS, in-app | Top-ups at the school office. Always sent. |

### Attendance

| Message | Who gets it | Sent by default as | Notes |
|---|---|---|---|
| Arrived at school | Parents (SMS) and the student (in-app) | SMS, in-app | When the student clocks in at the gate. **Off until switched on**: each clock-in costs an SMS. |
| Left school | Parents (SMS) and the student (in-app) | SMS, in-app | When the student clocks out. **Off until switched on.** |

### Your school's plan

These go to the school's School Admins and Portal Managers. All are always sent.

| Message | When |
|---|---|
| Subscription status changed | The plan starts, is renewed, enters its grace period or ends. |
| Trial ending soon | 7, 3 and 1 days before a trial ends. |
| Plan invoice issued | eedu.ng issues the term's invoice. |
| Plan invoice reminder | 3 days before an unpaid invoice is due, and once it is overdue. |
| Plan payment receipt | eedu.ng records a payment on your invoice. |

Reminders are sent each morning at about 8:00.

### Messages that need something set up first

- **A feature your plan doesn't include** sends nothing. For example, there are no test notices without CBT, and no fee notices without the bursary.
- **Texts** need bulk SMS in your plan and set up for your school (see [Bulk SMS](school-admin.md#bulk-sms)). They use your school's SMS units.
- **Emails** need eedu.ng's email sending to be set up. The **Email** chip at the top of the Email & notifications page says whether it is.
- **A person with no email address or phone number** can't get that kind of message. They still get in-app notifications if they have an account.

## Quiet hours for texts

Texts that aren't urgent wait until your school's **quiet hours** end. By default nothing is texted between **9:00pm and 7:00am**, and those texts go out at 7:00am. Payment and wallet receipts are sent straight away, at any hour. Change the hours on the [Sender & quiet hours](#sender-and-quiet-hours) tab.

## Unsubscribing

Emails that aren't always sent have an **Unsubscribe** link at the bottom. It stops that kind of email (for example all results emails) to that address, after the person confirms on the page that opens. Receipts and account messages still arrive.

## Changing the wording (School Admins)

**Communicate → Messaging & Printing → Message templates**

School Admins, Portal Managers and Software Engineers can change every message their school sends. The page lists the messages by group. Each one shows its channels, **Customised** if your school has changed it, **Off** if it's switched off, and **Not in plan** if your plan doesn't include the feature.

Choose a message to open it:

1. **Send this message:** switch it on or off. Messages that are always sent can't be switched off.
2. **Channels:** choose **Email**, **SMS** and **In-app**. SMS shows in amber when bulk SMS isn't set up for your school; texts are skipped until it is.
3. **The wording**, one tab per channel:
   - **Email:** the **Subject**, the **Headline** (the large text at the top), the **Message** and the **Button text**. The button always opens the portal.
   - **SMS:** the text. Under it, the number of characters and SMS pages each text will use with the example values. Characters such as ₦ or emoji make every page shorter (70 characters instead of 160).
   - **In-app:** the short text shown under the bell (up to 300 characters).
4. **Insert a detail:** click a chip such as *Student First Name* or *Fee Amount* to put it where your cursor is. When the message is sent, it's replaced with each person's own details. Only the details listed for that message can be used.
5. **Preview:** the message as people will see it, with example values and your school's branding. Switch between computer and phone width.
6. **Save.** **Send test to me** emails the message, as you've written it, to your own address. **Reset to default** goes back to the original wording. **History** lists earlier versions: **Load into editor** brings one back, and saving it makes it the current wording again.

{% hint style="info" %}
A message that's **Off until switched on** (the passcode message, gate texts) only starts going out after you switch it on and save.
{% endhint %}

### Sender and quiet hours

**Message templates → Sender & quiet hours**

- **Sender name:** shown as the sender in inboxes. It defaults to your school's name. Emails come from eedu.ng's own address, so inboxes don't mark them as fake.
- **Reply-to email:** where replies from parents and staff go. It defaults to your school's email address.
- **Accent colour:** the colour of buttons and links in your emails. It defaults to your school's colour.
- **SMS quiet hours:** see [Quiet hours for texts](#quiet-hours-for-texts).

## Checking what was sent

**Communicate → Messaging & Printing → Delivery log**

- **Sent**, **Waiting**, **Failed** and **Skipped** totals for the last 7 days.
- Every email, text and in-app notification your school sent, newest first: who it went to, which message, the channel, its status and when. Search by name, email or phone, and filter by status or channel.
- **Waiting** messages show when they will go out, for example after quiet hours, or a retry after a temporary problem.
- **Failed** or **Skipped** messages show why, for example *Bulk SMS is not enabled for this school* or *No longer applies*. **Retry** queues one again.

eedu.ng sends a little at a time so it stays within its email provider's limits. Receipts and account messages always go first, so a large announcement never holds up a payment receipt.

## (Software Engineer) Platform defaults and sending

- **Platform defaults:** on the Message templates page, switch from your school to **Platform defaults** to edit the wording every school starts with. A school that has customised a message keeps its own version. eedu.ng's own messages, such as *New school registered* (sent to Software Engineers when a school signs up) and the password emails, are only edited here.
- **Sending health** (on the Delivery log, Software Engineers only) covers all schools:
  - each way of sending email (**Host mail**, **Brevo API**, **Dry run**), whether it's ready or paused and why, and how much of this hour's and today's allowance is used;
  - the limits per minute, hour and day. Normal messages may use 70% of each hour's and day's limit; the rest is kept for receipts and account messages;
  - what is waiting in the queue;
  - **Routing:** which way of sending is used first;
  - the **Sender address**, the **Brevo API key** (never shown once saved), and a pause between emails for strict hosts;
  - **Dry run:** emails are written to the server instead of being sent, and texts are skipped. Use it on test copies of real data;
  - **Run queue now** sends what's due straight away instead of waiting for the next minute.
- If the email host or provider refuses for sending too much, that way of sending pauses (for 15 minutes, then 1 hour, then 6 hours) and messages use the other way or wait. **Resume** clears a pause.
