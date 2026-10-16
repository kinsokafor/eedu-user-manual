---
description: >-
  Running the school day to day: students, staff, results, fees, attendance, bulk SMS and pastoral care.
icon: school
---

# School Admin

Portal: `/eedu/school-admin/`

School Admins run the school day to day:
- students and staff;
- results;
- fees, accounts, the canteen and the bookstore;
- attendance;
- timetables, CBT and remote lessons;
- pastoral care and bulk SMS.

School-wide set-up (grading, marking scheme, active session, promotion rules) belongs to the Portal Manager; see the [Portal Manager manual](portal-manager.md).

Read [Getting started](getting-started.md) first.

---

## Your sidebar

| Section | Items |
|---|---|
| **Academics** | Exams & Results · Timetable · E-learning · Pastoral Care |
| **People** | Students · Staff |
| **Money** | Fees & Accounts · Canteen & Bookstore |
| **Gate** | Attendance |
| **Communicate** | SMS & Printing (Bulk SMS, ID cards, scratch cards) |
| **School** | School (your schools) · Plan & Invoices |

If you work in more than one school, switch between them from the school card at the top of the sidebar or the school button in the top bar (see [Getting started](getting-started.md#switching-schools)).

## Your dashboard

- **Buttons** for your most common jobs: *Add student*, *Import students*, *Add staff*, *Bulk SMS* and *Record payment*.
- **Needs your attention:** for example term dates not set, teachers without subjects, classes without a form teacher, or no fees for this term.
- **Headline numbers:** students, staff, fees recovered and outstanding, and present today.
- **Cards:**
  - **This term** and the **term checklist** (what to do at the start of a term);
  - **Results progress** for the newest exam, class by class;
  - **School fees this term** and **At the gate today**;
  - **Canteen today**, **Class timetables** and **E-learning**;
  - **Pastoral care**: safeguarding flags waiting for acknowledgement, serious concerns still open, follow-ups due this week and recent concerns.
- **Go to:** shortcuts to the pages you use most. A locked shortcut belongs to a feature your plan doesn't include.

---

## Students

### Adding one student
**People → Students → Add Student**
1. Enter the **Student Name** (surname, middle name, other names), **Gender**, **Phone Number** and **Email**.
   - The phone number should be the parent's. It is used for fee reminders and pastoral SMS.
   - Email is optional.
2. Choose the **Class**, **Stream**, **Term** and **Section** the student is joining.
3. Add a **Student Picture** if you have one. It is used on the ID card.
4. Save. The student gets a **passcode**, which is also their first password.

### Importing many students
**People → Students → Import Students**
1. **Download template.** It is an Excel file with one row per student.
   - Required columns are marked `*`.
   - Class, Stream and Gender have drop-downs with your school's values.
   - Your school's own bio-data fields are included.
2. Fill it in and save it as `.xlsx` or `.csv`. One file can hold up to the number of students shown on the screen.
3. Choose the **Section** and **Term** the students are joining, upload the file, and wait for the check.
4. Review the result:
   - **Ready** rows will import.
   - **Warnings** (for example "a student with this name is already in JSS 1 this term") are ticked and will import. Untick any you don't want.
   - **Errors** (a missing name, an unknown class) won't import. Fix them in the file and upload again.
5. Choose **Import N students** and confirm.
6. Choose **Download passcodes** and keep the file safe: passcodes are login details.

### Finding and viewing students
- **People → Students → Students Management** shows:
  - this term's population compared with last term;
  - recently added students;
  - the latest class changes.
- **View Students** lists students by **Academic Year**, **Term**, **Class** and **Stream**, with search. Use the two buttons above the list to switch between:
  - **cards**: photo, name, class, passcode and phone, with *View profile*;
  - **a table**: photo and name (with the passcode under it), class, gender, parent phone and **View**.
- Click a student's name, card or row to open their profile.

### The student profile

At the top, a banner with the student's photo, name, class and stream, passcode, gender and status, and:
- **Message**, to write to the student;
- **Edit**;
- **⋯** (Software Engineers, Portal Managers and School Admins): **Change password** and **Log in as** the student.

**Overview** (for the school you're working in):
- **This term's class**, **latest average** (with the change since the result before), **position** out of the class, and **attendance** this term (days present; it needs the term's dates under Attendance → Term Duration).
- **Recent results:** each exam with its term, the average, the position, and the strongest and weakest subject.
- **Fees** (Bursars, School Admins and Portal Managers, when Bursary is on): total, paid and balance for the term, and the **wallet balance**.
- **Class history:** the classes the student has been in, newest first.
- **Pastoral** section, when Pastoral Care is on: house and boarding, this term's merits and demerits, welfare alerts at the top of the page, and behaviour, welfare and counselling summaries as your role allows.

**Beside the overview:**
- **Details:** the personal details that are filled in (names, phone, date of birth, parent, address, home town, LGA, state of origin).
- **Records:** **Academic reports**, **Financial reports**, **Attendance report**, **Bio / meta data** and, when allowed, **Pastoral record**.
- **Pass:** the QR code and passcode used on the ID card.

### Editing a student
Profile → **Edit**. Change the name, gender, phone, email or picture. To change a student's class, use Manage Class List.

### Manage Class List
**People → Students → Manage Class List**
- Tabs: **Active**, **Archive** and **Deleted** students for the active term.
- Search, or filter by class and stream. Open a student to:
  - change their **Class** and **Stream** for this term;
  - untick **Active** to archive them, for example when they have left;
  - **Delete** an archived student, or **Undo** a deletion.
- Every change is listed under "Latest Class Modifications" with who made it and when.

### Printing a class list
**People → Students → Print Class List.** Tick the columns you want (name, passcode, gender, phone…), choose the class, and print.

---

## Staff

### Adding staff
**People → Staff → Add Staff** (or **+ New → Add staff** in the top bar)

Someone who already works in another eedu.ng school keeps one account, so eedu.ng checks their email first.

1. **Check the email.** Enter the staff member's email and press **Enter** or **Check** (it also checks by itself when you stop typing):
   - **Record found:** they already have an account. Their card is shown with the schools they're in. Choose **Add staff to** *your school* to link them; nothing else to fill in.
   - **No account uses this email:** choose **Register new staff** to fill in their details (the email is carried over).
   - **This email belongs to an account that isn't staff** (for example a student): use a different email for the staff member.
   - **Staff has no email:** choose this button to go straight to the new-staff form.
2. **New staff:** fill in the **Staff Name** (surname first), **Gender**, **Phone Number**, **Email**, **Role** and **Staff Picture**, and save. They're added to your school.
3. The new staff member signs in with their passcode (or email). Their first password is their passcode.

Close the box (× or **Esc**) to leave without adding anyone.

{% hint style="info" %}
School Admins can add staff to, and remove them from, **the schools they manage themselves**. You can't remove yourself from a school; ask a Software Engineer.
{% endhint %}

### Finding staff
**People → Staff → Staff** lists your school's staff as **cards** or as **a table** (the two buttons above the list): photo, name and passcode, role or job title, email and phone, and **View**. Click a name, card or row to open the profile.

### The staff profile

At the top, a banner with the staff member's photo, name, role or job title, passcode, gender and status, and **Message**, **Edit** and **⋯** (**Change password**, **Log in as**) for those allowed.

**Overview** (for the school you're working in):
- **Classes taught** and how many subjects, **score entry** for the newest exam (how much of their scoring is done), **form class**, and **attendance** this term (days clocked in).
- **Teaching:** the subjects they teach in each class, and score entry for the newest exam class by class, slowest first (**Show all** for the rest).
- **Schools:** every school they work in, with *This school* marked, and when they were added here.
- **Form teacher of:** the classes they're form teacher of.

**Records** (beside the overview):

| Record | What it does |
|---|---|
| Attendance report | Their clock-in and clock-out history and attendance score |
| **Subjects** | The classes and subjects they teach. **Teachers can only enter scores for subjects ticked here.** (Teachers, lecturers and form teachers.) |
| Bio / meta data | Their full details |
| Signature | The signature printed on report cards, for result signatories |
| Permissions | Grant permission to be absent (see below) |
| Remove from school | Remove them from this school. Their account and history stay. |

**Details** and the **Pass** (QR code and passcode) are beside the overview too.

### Granting permission (exeat) to staff
Staff profile → **Permissions**:
1. Enter the **Reason** and the **Start Date** and **End Date**.
2. Save. The staff member shows as *On permission* at the gate, and those days don't count as absences.

Existing permissions are listed below the form.

{% hint style="warning" %}
Student permissions can't be granted from a student's profile yet.
{% endhint %}

### Printing a staff list
**People → Staff → Print Staff List.** Choose the columns, then print.

---

## Results

As School Admin you can:
- enter and view scores for **every** subject and class;
- see broadsheets;
- print report cards;
- publish term and annual results.

The term's exams are created by a Dean, HOD or Portal Manager: you don't have the **Create Exam** button.

The full results workflow is in the [Dean manual](dean.md#results):
- **Update Result**, to enter scores;
- **Broadsheet** and **Publish**;
- **Print Results**, where you pick results to print or print a whole class; every printed result carries a **QR code** anyone can scan to check it's genuine (see [Report cards](dean.md#6-report-cards-print-result));
- **Annual Broadsheet**, **Annual Results** and promotion;
- **Download/Upload Excel**;
- **Track latest updates**;
- **Performance Analysis**.

---

{% hint style="info" %}
**Some of what follows depends on your school's plan:** publishing and printing results, fees and accounts, bulk SMS, attendance at the gate, timetables, CBT, remote lessons and pastoral care. A screen your plan doesn't include shows a 🔒 notice. See [Plans and subscriptions](plans.md).
{% endhint %}

## Fees, accounts, canteen and bookstore

Everything in the [Bursar manual](bursar.md) is available to you:
- creating fees, recording payments, exemptions and debtor reminders;
- accounts, journals and the trial balance;
- wallet top-ups, canteen items and sales reports, canteen settings;
- the bookstore.

As School Admin you can also:
- **void** a canteen sale or book sale;
- hand over pack books to a student who hasn't paid, giving a reason.

---

## Attendance

**Gate → Attendance**
- **Clock In** and **Clock Out** screens for the gate (see the [Security manual](security.md)).
- **Attendance:** a calendar. Pick a day to see who was in, with their times.
- **Term Duration:** the term's opening and closing dates.
- **Holidays:** add a holiday with a name and date range. Holidays don't count as absences.

A person's attendance history is on their profile (**Attendance Report**):
- choose a date range;
- see the **Attendance score**, **Days in attendance**, **Days absent**, and every clock-in and clock-out.

---

## Bulk SMS

**Communicate → SMS & Printing → Send Bulk SMS** (or **+ New → Send bulk SMS**)
- **Step 1, choose who gets it:**
  - **Quick select** (beside the list on a computer, above it on a phone): **All students**, **All staff**, a **class**, or a class and stream (open **Class and stream**). Each chip shows how many people it covers; it's ticked when they're all chosen and outlined when only some are. Tap it again to take them off.
  - **One by one:** tick people in the list. Search by name.
  - The bar at the bottom shows how many you've chosen, with **Clear** and **Write message**.
- **Step 2, write it:** the screen shows *Sending to N people* with the first names. Type the **Message** (the counter shows how many SMS pages it will use) and send. **Change recipients** goes back with your choice kept.
- Messages to students go to the parent phone number on the student's record.
- **Bulk SMS Reports:** your SMS account, unit balance, delivery report, message history and credit (payment) history.
- **Recharging:** pay at nigeriabulksms.com, using your account's email address as the payment narration.

Bulk SMS must be included in your school's plan, and then set up for your school by eedu.ng support.

---

## Timetable, CBT, Remote Lessons

- **Timetable** (Academics → Timetable): Class Timetables, Bell Schedule and My Timetable. See the [Dean manual](dean.md#timetables).
- **CBT and Remote Lessons** (Academics → E-learning): see the [Teacher manual](teacher.md). As School Admin you see and manage every subject's tests and lessons.

## Pastoral Care

As School Admin you are a pastoral **manager**:
- you see all behaviour records and welfare notes;
- you can change or withdraw any entry and record suspensions;
- you name the pastoral team;
- you read the access log.

You never see counselling notes, only that a session took place. See the [Pastoral Team manual](pastoral-team.md#managers).
