---
description: >-
  Exams, score entry, broadsheets, publishing, report cards, annual results, promotion and timetables.
icon: graduation-cap
---

# Dean of Studies

Portal: `/eedu/dean/`

The Dean runs the academic side of the school:
- creating each term's exams;
- getting scores entered;
- checking and publishing results;
- annual results and promotion;
- timetables;
- oversight of CBT and remote lessons;
- student records.

This manual also holds the **full results workflow**, which School Admins, HODs, Form Teachers and Portal Managers use too.

Read [Getting started](getting-started.md) first.

---

## Your sidebar

| Section | Items |
|---|---|
| **Academics** | Exams & Results · Timetable · E-learning · Pastoral Care |
| **People** | Students |
| **Communicate** | Messaging & Printing (Bulk SMS) |
| **School** | School |

## Your dashboard

- **Buttons:** *Create exam*, *Update result*, *Broadsheet* and *Bulk SMS*.
- **Needs your attention:** for example no exam yet this term, classes without a form teacher, or teachers without subjects.
- **Results progress** for the newest exam (choose another at the top): how much of each class's scoring is done, which subjects haven't started and who teaches them, and which classes are published or changed since publishing.
- The **term checklist**, **Class timetables**, **E-learning**, **Annual results and promotion** (in the last term), **Pastoral care** and your own **pastoral duties**.
- **Go to:** shortcuts such as *Examinations*, *Update result*, *Broadsheet* and *Print results*.

---

## Results

### How results work in eedu.ng

1. **An exam** is created for the term, for example *Third Term Examination*. It has a marking scheme (for example CA1 20 + CA2 20 + Exam 60) and a grading system.
2. **Teachers enter scores** for their subjects, part by part (**Update Result**).
3. **The broadsheet** puts every student's subject totals, overall total, average and position side by side for a class.
4. **Publishing** from the broadsheet takes a snapshot of each student's result, including the comment. Only published results reach students and parents.
5. **Report cards** are printed from **Print Results**, each with a QR code that proves it is genuine.
6. At the end of the session, **annual results** combine the exams marked *Use result for annual*, and decide promotion.

{% hint style="info" %}
Scores changed after publishing are **not** visible to students until the result is published again. This protects published results from quiet edits: every change is recorded and has to be deliberately republished.
{% endhint %}

### 1. Creating the term's exam
**Academics → Exams & Results → Examinations → Create Exam.** Portal Managers and HODs can do this too.

| Field | What to enter |
|---|---|
| Name of Exam | For example *First Term Examination* |
| Term, Section | The term and session |
| Marking Scheme | Pre-filled from the school's scheme. Must total 100. |
| Result infos | Extra lines for the report card, such as *Next term begins* or *School fees for next term* |
| Grading System | Pre-filled from the school's grades |
| Enable positioning | Show positions on broadsheets and report cards |
| Position all streams together | Rank the whole class across streams |
| Use result for annual | Include in the annual result. Normally on for main exams, off for tests. |
| Use pin to access result | Require a scratch card PIN before a student can see this result |
| Result Comments | Automatic comments by average |

You can't create two exams with the same name in the same term. Once an exam is created, only a Portal Manager can edit it or limit it to certain classes or subjects.

The **Examinations** page lists all exams. It shows the active term with a **Switch** link for Portal Managers, and shortcuts to every results screen.

### 2. Entering scores (Update Result)
**Academics → Exams & Results → Update Result**, then choose the exam.

1. Choose the **Class**, **Stream** and **Subject**. As Dean you can choose any subject; teachers see only their assigned ones.
2. Each student appears with a box for each part of the marking scheme, for example *CA1 (20%)*, *CA2 (20%)* and *EXAM (60%)*.
3. Type the scores and choose **Save** for that student. The card shows the **Total**, **Grade** and **Remark**, and who last updated it and when.
4. **clear** removes a student's entry for that subject, after you confirm.
5. The side panel shows progress: students in the class, results recorded, and results not yet recorded.

### 3. Entering scores from Excel
**Exams & Results → Download/Upload Excel**, then choose the exam.

1. **Generate Gradebook Excel Template:**
   - choose the **Class**, the **Streams** and the **Subjects**;
   - choose **Single file?** for one workbook, or one file per stream;
   - download.
2. Fill in the scores in the columns for each part of the marking scheme. Don't change the headings or the student rows.
3. **Upload Template:** choose the completed file and **Submit Uploads**.

### 4. Tracking who is entering scores
**Exams & Results → Track latest updates** lists the latest score entries: student, subject and class, score, who recorded it, and when. Use it to follow up teachers who haven't started, and to check changes after publishing.

### 5. The broadsheet
**Exams & Results → Broadsheet**, then choose the exam.
- Choose the **Class** and **Stream**.
- Each row shows the student, every subject's total, the **Total**, the **Subjects Offered**, the **Average**, and the **Position** when positioning is on.
- Sort by **Name** or **Position**.
- **Print** prints it. Tick *Check this box to print landscape* for wide classes.

{% hint style="info" %}
**Publishing and printing depend on your school's plan.** If your plan doesn't include them, the **Print** and **Publish** buttons are removed from the broadsheet, the annual broadsheet and report cards, and a notice says so. Scores can still be entered and the broadsheet viewed. See [Plans and subscriptions](plans.md).
{% endhint %}

### Publishing results
On the broadsheet choose **Publish**, then **Publish Result**, and confirm.
- eedu.ng publishes each student in turn and shows its progress, for example "Done publishing Ada Okeke's result". Keep the page open until it finishes.
- If the exam uses **Use pin to access result**, each student's result stays locked until the student enters a scratch card PIN (see the [Students and Parents manual](student-and-parent.md#checking-results-with-a-scratch-card)).
- Form teachers can publish their own class. Deans, HODs, School Admins and Portal Managers can publish any class.
- Republish whenever scores or comments change.
- **Parents are told** when a student's result is published, by email and SMS, and the student gets a notification in the portal. Republishing the same exam doesn't send it again. Annual results are announced the same way. See [Emails and notifications](notifications.md#results-lessons-and-tests).

### 6. Report cards (Print Result)
**Exams & Results → Print Results**, then choose the exam.
This screen works on **published** results, so publish from the broadsheet first.

1. The page shows the exam's name and term. Choose the **Class** and **Stream**.
2. At the top: how many students have results, the **class average**, the **highest** and the **lowest** average.
3. Each student's row shows their photo and name (opens their profile), **average**, **position** out of the class, **total** and **subjects**. The list button shows every subject's score. Order the list **By position** or **By name**.
4. **To change a comment:** click it, type, and it saves by itself about two seconds after you stop typing; **Done** closes it. The change goes straight into the published result.
   **Note:** Publishing the class again from the broadsheet rewrites the comments. Make comment changes *after* the final publish.
5. **Print:**
   - **One student:** **View** on their row.
   - **Some students:** tick them (or **Select all**), then **View and print** in the bar at the bottom.
   - **The whole class:** **Print whole class**.

   The results open one after another, in the order of the list, with **Back** and **Print** at the top. **Print** sends them all to the printer, one per page.

The report card has:
- the school letterhead;
- the student's details;
- the key to grades;
- every subject with each part of the marking scheme, the total, grade and remark;
- the overall total, subjects offered, average and position;
- the form teacher's comment;
- the result infos;
- the signatories;
- a **QR code** to verify the result (below).

#### Verifying a printed result (QR code)

Every printed result carries a QR code with the words *Scan to verify this result* and a web address. Anyone (a parent, another school, an employer) can scan it with a phone camera, or type the address, without signing in. It opens the school's **official record** of that result:
- the school's name and logo, and a **Verified result** badge;
- the student, class, exam and term;
- the total, average, position, number of subjects, and each subject's score and grade;
- when the record was last updated.

If anything on the paper differs from that page, the paper has been changed. A made-up or damaged code shows **Not verified**, and a result the school has withdrawn shows **Result withdrawn**.

Each code is unique to its result and can't be guessed, so nobody can look up another student's result from it. The page always shows the current record: if you correct a score and republish, the page shows the corrected result, so reprint the card.

### 7. Performance analysis
Open an exam from the Examinations list. **Performance Analysis** shows each class's card: the best students and statistics by subject. Use it at staff meetings.

### 8. Annual results and promotion
At the end of the session, after the last term's results are published:

1. **Exams & Results → Annual Broadsheet.** Choose the **Class** and **Section**.
2. Each student shows every subject's annual score, the **Total**, **Subjects Offered**, **Average**, **Position**, and a **Comment** of **Promoted** or **Not promoted**.
   - The comment is worked out from the school's promotion rules (see the [Portal Manager manual](portal-manager.md#promotion-rules)).
   - If a comment looks wrong, check the scores and the promotion rules.
3. **Publish Result.** This needs a Dean, HOD, School Admin or Portal Manager; form teachers can't publish annual results.
4. **Exams & Results → Print Annual Result** prints annual report cards.

When the Portal Manager moves the school to the new session, students marked **Promoted** move up a class automatically.

---

## Timetables

**Academics → Timetable** (only when Timetables are switched on for your school).

### Bell schedule
**Timetable → Bell Schedule.** The periods of the school day for one term. Every class uses the same periods.

1. Choose the **Term** at the top.
2. **Start with a typical day** gives you a ready-made day to adjust. Or use **Add period**.
3. For each period set a **Name**, when it **Starts** and **Ends**, and its **Type**: *Lesson*, *Break*, *Assembly* or *Other*.
4. **Save schedule.** Periods that overlap are refused. You can't turn a period that already has lessons into a break or remove it, until you clear its lessons.

The school's days off (from Attendance settings) are left out automatically.

### Class timetables
**Timetable → Class Timetables** shows every class with its status:
- **Published**, **Draft** or **Not started**;
- how many lessons are filled;
- how many have no teacher.

Choose **Edit** on a class, or open **Class Timetable** and choose the class and stream.

1. **Tap a period** to set it.
2. Choose the **Subject**. Choose *No lesson* for a free period.
3. Tick the **Teachers**. Staff assigned to that subject in that class are listed first and marked *Assigned*. You can tick more than one teacher, for example for a practical.
4. **Save.**
   - If a teacher is already teaching another class in that period, eedu.ng refuses and tells you where.
   - Other issues (for example, a teacher not assigned to that subject) save with a warning.
5. **Clear lesson** empties a period.
6. When the class is ready, choose **Publish**. Teachers and students only see published timetables. If some lessons have warnings, you're asked to confirm.
7. **Print** prints the class's week.

### Starting a new term
When a term has no timetable yet, the Timetables page offers **Copy timetable** from another term. The bell schedule and lessons are copied as drafts, and teachers who have left are dropped. Review each class and publish.

### My Timetable
**Timetable → My Timetable** shows your own lessons. You can also view any class's published timetable, and print it.

---

## CBT and Remote Lessons

As Dean you are a manager in both:
- you see and edit every subject's questions, tests, lessons and assignments;
- you can reset a student's test attempt, giving a reason.

The step-by-step guides are in the [Teacher manual](teacher.md#cbt-computer-based-tests).

---

## Students

Under **People → Students** you can:
- add students;
- import students from Excel;
- view and edit student records and bio-data;
- manage the class list;
- print class lists.

The steps are the same as in the [School Admin manual](school-admin.md#students).

## Pastoral Care

As Dean you are a pastoral **manager**, like the School Admin. See the [Pastoral Team manual](pastoral-team.md#managers).

## Bulk SMS

**Communicate → Messaging & Printing → Send Bulk SMS / Bulk SMS Reports.** See the [School Admin manual](school-admin.md#bulk-sms).
