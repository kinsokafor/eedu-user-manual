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
| **Bursary** | Fees & Accounts · Canteen & Bookstore |
| **Management** | School · Students · Staff |
| **Utilities** | Attendance · SMS & Printing (Bulk SMS) |

## Your dashboard

- Counters for students, staff and fees.
- A card for each switched-on feature: Canteen, Bookstore, Timetable, CBT, Remote Lessons and Pastoral Care.

The Pastoral Care card also shows:
- safeguarding flags waiting for acknowledgement;
- serious concerns still open;
- follow-ups due this week;
- recent concerns.

---

## Students

### Adding one student
**Management → Students → Add Student**
1. Enter the **Student Name** (surname, middle name, other names), **Gender**, **Phone Number** and **Email**.
   - The phone number should be the parent's. It is used for fee reminders and pastoral SMS.
   - Email is optional.
2. Choose the **Class**, **Stream**, **Term** and **Section** the student is joining.
3. Add a **Student Picture** if you have one. It is used on the ID card.
4. Save. The student gets a **passcode**, which is also their first password.

### Importing many students
**Management → Students → Import Students**
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
- **Management → Students → Students Management** shows:
  - this term's population compared with last term;
  - recently added students;
  - the latest class changes.
- **View Students** lists students by **Academic Year**, **Term**, **Class** and **Stream**, with search. It shows each passcode, gender and parent phone number. Switch between grid and list views.
- Click a student to open their **profile**:
  - QR ID card;
  - **Academic Reports**, **Financial Reports**, **Attendance Report** and **Bio/Meta Data**;
  - **Edit** and **Change password**;
  - **Message Student**;
  - **Pastoral** section, when Pastoral Care is on:
    - house and boarding;
    - this term's merits and demerits;
    - welfare alerts at the top of the page;
    - behaviour, welfare and counselling summaries, as your role allows.

### Editing a student
Profile → **Edit**. Change the name, gender, phone, email or picture. To change a student's class, use Manage Class List.

### Manage Class List
**Management → Students → Manage Class List**
- Tabs: **Active**, **Archive** and **Deleted** students for the active term.
- Search, or filter by class and stream. Open a student to:
  - change their **Class** and **Stream** for this term;
  - untick **Active** to archive them, for example when they have left;
  - **Delete** an archived student, or **Undo** a deletion.
- Every change is listed under "Latest Class Modifications" with who made it and when.

### Printing a class list
**Management → Students → Print Class List.** Tick the columns you want (name, passcode, gender, phone…), choose the class, and print.

---

## Staff

### Adding staff
**Management → Staff → Add Staff**
1. Enter the staff member's email address, or leave it blank if they have none, and choose **Continue**.
2. What happens next depends on whether the email is known:
   - **Already on eedu.ng** (for example, they work in another school): eedu.ng shows "Record found!". Choose **Add staff to** *your school* to link them.
   - **New:** fill in the **Staff Name**, **Gender**, **Phone Number**, **Email**, **Role** and **Staff Picture**, and save.
3. The new staff member signs in with their passcode (or email). Their first password is their passcode.

### The staff profile
Open a staff member from **Management → Staff → Staff**.

| Item | What it does |
|---|---|
| Attendance Report | Their clock-in and clock-out history and attendance score |
| Upload Signature | The signature printed on report cards, for result signatories |
| Bio/Meta Data | Their details |
| **Subjects** | The classes and subjects they teach. **Teachers can only enter scores for subjects ticked here.** |
| Permissions | Grant permission to be absent (see below) |
| Remove Staff | Remove them from this school. Their account and history stay. |
| Edit / Change password | Change their details, their role, or set a new password |

### Granting permission (exeat) to staff
Staff profile → **Permissions**:
1. Enter the **Reason** and the **Start Date** and **End Date**.
2. Save. The staff member shows as *On permission* at the gate, and those days don't count as absences.

Existing permissions are listed below the form.

> Student permissions can't be granted from a student's profile yet.

### Printing a staff list
**Management → Staff → Print Staff List.** Choose the columns, then print.

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
- **Print Result**;
- **Annual Broadsheet**, **Annual Results** and promotion;
- **Download/Upload Excel**;
- **Track latest updates**;
- **Performance Analysis**.

---

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

**Utilities → Attendance**
- **Clock In** and **Clock Out** screens for the gate (see the [Security manual](security.md)).
- **Attendance:** a calendar. Pick a day to see who was in, with their times.
- **Term Duration:** the term's opening and closing dates.
- **Holidays:** add a holiday with a name and date range. Holidays don't count as absences.

A person's attendance history is on their profile (**Attendance Report**):
- choose a date range;
- see the **Attendance score**, **Days in attendance**, **Days absent**, and every clock-in and clock-out.

---

## Bulk SMS

**Utilities → SMS & Printing → Bulk SMS**
- **Send Bulk SMS:**
  - Choose the recipients: quick-select all students, all staff, a class or a stream, or pick people by name.
  - Type the **Message** and send.
  - Messages to students go to the parent phone number on the student's record.
- **Bulk SMS Reports:** your SMS account, unit balance, delivery report, message history and credit (payment) history.
- **Recharging:** pay at nigeriabulksms.com, using your account's email address as the payment narration.

Bulk SMS must first be enabled for your school by eedu.ng support.

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
