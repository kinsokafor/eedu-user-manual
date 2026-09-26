# Portal Manager and eEdu Administrator

Portal: `/eedu/admin/`

- **Portal Manager:** the person who owns a school's eedu.ng account. It's usually the proprietor or an ICT officer. Whoever signs the school up becomes its Portal Manager.
- **Software Engineer:** eedu.ng support staff. They can do everything a Portal Manager can, in every school, plus the platform settings marked **(Software Engineer)** below.

A Portal Manager also holds the School Admin, Dean and Bursar permissions. Everything in the [School Admin](school-admin.md), [Dean](dean.md) and [Bursar](bursar.md) manuals is available to you as well. This manual covers what only Portal Managers and Software Engineers do: setting the school up, its settings, and the yearly session change.

---

## 1. Signing a school up

1. On the eedu.ng home page choose **Sign Up**.
2. **Step 1, School Identity:** school type (Nursery & Primary, Secondary, or Tertiary Institution), school name and address.
3. **Step 2, Contact information:** website, phone numbers, email, and the current academic session.
4. **Step 3, Your Information:** your name, email, phone number and password, and acceptance of the terms.
   - The password must have an upper-case letter, a lower-case letter and a number, and be at least 6 characters.
5. Choose **Sign Up**. You become the school's Portal Manager and can sign in straight away.

> The school type can't be changed casually later: it decides the class names (JSS 1… / Primary 1… / Level 100…), the terms or semesters, and the default subjects. Choose carefully.

---

## 2. First-time set-up checklist

Work through these in order before staff start entering results.

| # | Task | Where |
|---|---|---|
| 1 | Check the school's name, address, logo and colours | Ask eedu.ng support (School Basic Info is Software Engineer only) |
| 2 | Add class streams (arms) | Management → School → School Settings → Class Streams |
| 3 | Set the grading system | School Settings → Grading System |
| 4 | Set the marking scheme | School Settings → Marking Scheme |
| 5 | Set automatic result comments | School Settings → Result Comments |
| 6 | Choose who signs report cards | School Settings → Result Signatory |
| 7 | Add staff and give each a role | Management → Staff → Add Staff |
| 8 | Assign each teacher's classes and subjects | Staff profile → Subjects |
| 9 | Assign form teachers | School Settings → Form teachers |
| 10 | Add or import students | Management → Students → Add Student / Import Students |
| 11 | Add bio-data fields your school needs | School Settings → Student & staff meta data settings |
| 12 | Set promotion rules | School Settings → Promotion Control |
| 13 | Set attendance options, term dates and holidays | Utilities → Attendance |
| 14 | Set up fee accounts, then create fees | Bursary → Fees & Accounts (see the [Bursar manual](bursar.md)) |
| 15 | Switch on the extra features you want | Dashboard cards (section 6) |
| 16 | Create the term's exams | Academics → Exams & Results → Examinations → Create Exam |

---

## 3. School Settings

**Management → School → School Settings.** Only Portal Managers and Software Engineers can open these screens.

### Class Streams
The arms of each class, for example *Gold*, *Diamond*, *A*, *B*.
- Enter a **Stream name** and an **Order** (the order they appear in lists).
- In tertiary institutions streams are called **Departments**.

### Grading System
The grade bands used on report cards and broadsheets. Each row has:
- **Min** and **Max** scores (0–100);
- **Grade** (for example A1);
- **Remark** (for example *Excellent*);
- a **Color**.

> **Important:** the band that starts at **0** is treated as the *fail* band everywhere: in promotion decisions and in counting failed subjects. Make sure your lowest band starts at 0 and covers only failing scores.

### Marking Scheme
How each subject's 100 marks are split.
- Each row has a **Name** (for example *First CA*), an **Abbreviation** (for example *CA1*), a **Total** and an **Order**.
- The totals must add up to exactly **100**, or the scheme is refused.
- This is the school's default. Each exam can have its own scheme (section 7).

### Result Comments
Automatic comments by average.
- Each row has a **Comment**, and the **Min** and **Max** average it applies to.
- For example: "An excellent result. Keep it up." for 75–100.
- Publishing fills in each student's comment from these bands. Form teachers can then change individual comments on **Print Result**. Publishing again resets them to the automatic comment.

### Result Signatory
The people whose names and signatures appear on report cards.
- For each: the **Staff** member, **Preferred Name**, **Designation** (for example *Principal*) and **Position** on the card (left, centre or right).
- Upload each signatory's signature from their staff profile (**Upload Signature**). School Admins, Deans and Portal Managers can do this.

### Form teachers
One form teacher per class and stream: **Class**, **Stream** and **Form teacher**.

Form teachers:
- see and publish their class's broadsheet;
- comment on report cards;
- see their class's pastoral records.

An exam can override this list for one term.

### Active Session
The session and term the whole school is working in. See [section 5](#5-changing-term-or-session).

### Promotion Control
Rules the annual broadsheet uses to decide **Promoted** or **Not promoted**. See [section 5](#promotion-rules).

### Student & staff meta data settings
Extra bio-data fields beyond the built-in ones. For each field:
- **Label** (what people see);
- **Key** (a short internal name);
- **As** (the kind of input);
- **Type** (Student or Staff);
- **Is required?**

The screen lists recommended keys, such as `date_of_birth`, `address`, `state`, `lga`, `home_town`, `father`, `mother`, `guardian` and `whatsapp`. Using exactly these keys places the fields in the right sections of the bio-data page. These fields also appear in the student import template.

### Software Engineer only
- **School Basic Info:** name, address, motto, contacts, colours, logo, school type and status.
- **Classes & Subjects Customization:** the school's class list and subject list.
- **Attendance:** day or boarding school, and whether attendance is enabled.
- **Map Class Names:** rename the standard classes, for example "Primary 4" to "Basic 4".

---

## 4. Staff and access

See the [School Admin manual](school-admin.md#staff) for adding staff. As Portal Manager, remember:

- **Roles offered depend on the school type.**
  - Nursery, primary and secondary: Portal Manager, School Admin, Dean, Teacher, Form Teacher, Bursar, Security, Canteen.
  - Tertiary: Portal Manager, School Admin, HOD, Lecturer, Bursar, Security, Canteen.
- **Teachers only see their own subjects.** Open the teacher's profile → **Subjects** and tick the subjects they teach in each class. A teacher with no subjects assigned cannot enter scores.
- **Form teacher** is a role *and* an assignment. Give the person the Form Teacher role, then assign them a class in School Settings → Form teachers.
- **Resetting a password:** open the person's profile → **Change password**.
- **Signing in as a user:** Software Engineers, Portal Managers and School Admins see **Login to profile** on a profile. It opens eedu.ng as that person. Use it only to check what someone sees or to reproduce a problem, then sign out.

---

## 5. Changing term or session

### Moving to the next term
1. Make sure the term's results are published (see the [Dean manual](dean.md#publishing-results)).
2. Go to **School Settings → Active Session**.
3. Choose the new **Term**, keep the same **Section** (session), and save.
4. eedu.ng shows "Class list maintenance ongoing in the background". Every active student is carried into the new term in the same class and stream. It runs in batches and may take a few minutes for a large school.

### Moving to a new session (promotion)
1. Before the change:
   - The annual results must be published (Academics → Exams & Results → Annual Broadsheet → **Publish Result**).
   - Check the Promotion Control rules.
2. Set **Active Session** to the new session and First Term.
3. Class list maintenance then places each student:
   - **Promoted** on their annual result, or in a class listed under *Promote all students in these classes*: moved to the next class.
   - **Not promoted:** stays in the same class.
   - **In the last class** (for example SSS 3): becomes **Alumni**.
4. Afterwards, check **Management → Students → Manage Class List** and correct any individual student (see the [School Admin manual](school-admin.md#manage-class-list)).

### Promotion rules
**School Settings → Promotion Control** has three parts.

1. **Promotion Control:** per class, subjects with a rule.
   - **Must Pass:** the student must pass every subject marked Must Pass.
   - **A Cat / B Cat / C Cat:** subject groups. The student must pass *at least one* subject in each group you define.
2. **Maximum Fails:** per class, the number of failed subjects that stops promotion (4 if you add the class without a number).
3. **Promote all students in these classes:** classes where everyone moves up regardless of results, for example nursery classes.

A student is **Not promoted** if their annual average is in the fail band, or if any of the rules above isn't met. Otherwise they are **Promoted**.
- A subject counts as failed when its score is in the grading band that starts at 0.
- With no rules set for a class, everyone whose average passes is promoted.
- The comment is calculated automatically on the annual broadsheet. Fix the scores or the rules, not the comment.

---

## 6. Switching features on and off

Your dashboard has a card for each optional feature with an on/off switch:
- **Timetables**
- **CBT**
- **Bookstore**
- **Remote lessons**
- **Pastoral care**

- Switching a feature **on** makes its menus, screens and dashboard cards available to the staff and students who use it.
- Switching it **off** hides it again. **Nothing is deleted.** Switching back on restores everything.
- Check the school name in the sidebar before switching. The switch applies to the school currently selected.

Canteen and wallets are always available. The canteen can't take sales until the bursar sets its accounts (see the [Bursar manual](bursar.md#canteen-and-wallet-settings)).

---

## 7. Examinations

Create each term's exams under **Academics → Exams & Results → Examinations → Create Exam**. Portal Managers, Deans and HODs see this button.

| Field | Meaning |
|---|---|
| Name of Exam | For example *Third Term Examination* or *Mid-Term Test* |
| Term, Section | The period the exam belongs to |
| Marking Scheme | Starts with the school's scheme. Change it for this exam if needed (must total 100). |
| Result infos | Extra lines printed on the report card, for example *Next term begins: 8 Jan 2027* |
| Grading System | Starts with the school's bands |
| Enable positioning | Show each student's position in class |
| Position all streams together | Rank a whole class across its streams, instead of within each stream |
| Use result for annual | Include this exam in the annual (cumulative) result. Normally on for main exams and off for mock and mid-term tests. |
| Use pin to access result | Students need a scratch card PIN to unlock this result (section 9) |
| Result Comments | Automatic comments for this exam |

Only Portal Managers and Software Engineers can change an exam after it is created. Open it from the Examinations list and use its menu: **Edit** (the fields above), plus:
- **Form Teachers** for this exam only;
- **Result Signatory** for this exam only;
- **Classes:** restrict the exam to some classes;
- **Subjects:** the subjects this exam covers.

It also offers **Update Result**, **Broadsheet**, **Results**, **Download Excel** and a **Performance Analysis** of each class.

---

## 8. Attendance settings

**Utilities → Attendance → Settings**:
- **Activate Attendance?**
- **Days-off (weekend):** days with no school, for example Saturday and Sunday.
- **School type:** day or boarding.
- **School timezone:** Africa/Lagos for Nigerian schools.

From the Attendance page also set:
- **Term Duration:** the opening and closing dates. Attendance scores are calculated only within them.
- **Holidays:** a name and date range for each. Holidays don't count as absences.

See the [Security manual](security.md) for clocking in and out.

---

## 9. Scratch cards and ID cards

### Scratch cards (Utilities → SMS & Printing → Scratch Cards)
Scratch cards carry a PIN that unlocks a student's result when the exam uses **Use pin to access result**. Parents can also use an old PIN to open their child's account without a password.

1. Download the backdrop templates from the Scratch Cards page. Design the front with a space for the PIN, sized 3.5 in × 2 in.
2. Upload the front design.
3. **Create new batch (Software Engineer):** the **Number of cards** (1 to 1,600) and the **Cost** of each card.
4. Open a batch to preview it and **Download PDF** for printing. The back design is needed only by the printer.

Each PIN unlocks **one result for one student**. Once used, it stays tied to that student and exam.

### ID cards (Software Engineer)
- **ID Card Backdrop:**
  - Download the front and back SVG templates.
  - Design around the marked zones, which are filled in automatically for each person.
  - Export PNGs of 638 × 1013 px (2.125 in × 3.375 in at 300 dpi).
  - Upload them, and choose the text colours.
  - Tick *My front design already includes the school name, address and logo* if it does.
- **ID Cards:** pick the students or staff and print their cards. Each card carries a QR code used at the gate, the canteen and the bookstore.

---

## 10. Software Engineer tools

- **Management → School → Add School:** create a school directly.
- **Management → School → Options:** platform options.
- **Management → School → Google Services:** Google Drive sign-in settings used by Remote Lessons (client ID, secret, redirect address). Teachers then connect their own Drive.
- **Bursary → Fees & Accounts → Options:** payment settings per school:
  - manual payment updates and their journal;
  - wallet use and the wallet journal;
  - currency;
  - virtual accounts (Squad) with the public key, secret key and payment email, whether charges fall on parents, and custom account names.
- **Create Virtual Accounts:** pre-create a number of virtual accounts.
- **Utilities → SMS & Printing → Bulk SMS Options:** enable bulk SMS, and set the sender name and the nigeriabulksms.com username and password.
- **Message Center → Chat panel:** add a support chat panel.
- **Result access API:** a Portal Manager sees the school's open result-access address on the school page, for connecting other systems.
