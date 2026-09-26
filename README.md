# eedu.ng User Manual

eedu.ng is a school management system for Nigerian schools. It covers students and staff, examinations and report cards, school fees and accounts, attendance at the gate, timetables, computer-based tests, remote lessons, a cashless canteen, a bookstore, pastoral care, bulk SMS and ID and scratch cards.

Everyone signs in at the same address. Each person then lands on the **portal** for their role, and sees only the menus and screens that role is allowed to use.

## Which manual do I need?

| If you are… | Your role in eedu.ng | Manual |
|---|---|---|
| New to eedu.ng, any role | – | [Getting started and everyday tasks](getting-started.md) |
| The person who set the school up, or runs its eedu.ng account | Portal Manager | [Portal Manager and eEdu Administrator](portal-manager.md) |
| eedu.ng support staff | Software Engineer | [Portal Manager and eEdu Administrator](portal-manager.md) |
| The principal, proprietor or head of administration | School Admin | [School Admin](school-admin.md) |
| The Dean of Studies or Vice Principal (Academics) | Dean | [Dean of Studies](dean.md) |
| A Head of Department (tertiary institutions) | HOD | [Head of Department](hod.md) |
| A class or subject teacher | Teacher, Form Teacher | [Teacher and Form Teacher](teacher.md) |
| A lecturer (tertiary institutions) | Lecturer | [Teacher and Form Teacher](teacher.md#lecturers) |
| The bursar or accounts officer | Bursar | [Bursar](bursar.md) |
| A gate or security officer | Security | [Security](security.md) |
| Canteen or tuck-shop staff | Canteen | [Canteen](canteen.md) |
| A student, or a parent of a student | Student | [Students and Parents](student-and-parent.md) |
| A counsellor, welfare officer, house master or hostel master | (any staff role, plus a pastoral duty) | [Pastoral Team](pastoral-team.md) |

For the yearly routine (opening and closing a term, results season, a new session), see the [Term calendar](term-calendar.md).

## How roles and permissions work

- **Every account has one role.** The role decides which portal you land on and what you can do. A school admin sets a staff member's role when adding them, and can change it later.
- **Some features are switched on per school.** Timetable, CBT, Remote Lessons, Bookstore and Pastoral Care are off until the school's Portal Manager (or eedu.ng support) switches them on from the dashboard. Until then, their screens say the feature is "not activated for this school" and their dashboard cards stay hidden.
- **Pastoral duties sit on top of a role.** Counsellor, welfare officer, house master and hostel master are not roles. A manager gives these duties to staff inside Pastoral Care, and they add to what that person can already do.
- **Staff can belong to several schools.** If you work in more than one school on eedu.ng, the school name at the top of the sidebar is a switch. Choose the school you want to work on.

## Words the system uses

eedu.ng adapts its wording to the type of school.

| | Nursery and primary / Secondary | Tertiary institution |
|---|---|---|
| Academic year | **Section**, for example 2025/2026 | **Year** |
| Part of the year | **Term** (First, Second, Third) | **Semester** (First, Second) |
| Group of students | **Class**, for example JSS 1 | **Level**, for example Level 100 |
| Subdivision of a class | **Stream**, for example Gold | **Department** |

This manual says *session*, *term*, *class* and *stream*. Read them as your school's own words.

Other words you will meet:

- **Passcode:** each student's and staff member's unique login ID, for example `E4646561737`. It is printed on ID cards.
- **Active session:** the session and term the school is currently in. Most screens work on the active term.
- **Marking scheme:** how a subject's 100 marks are split, for example CA 1 (20), CA 2 (20) and Exam (60).
- **Publishing:** results that have been entered are only visible to students and parents after they are published from the broadsheet.
- **Scratch card PIN:** a code sold by the school that unlocks a student's result when the school requires PINs.
- **Journal:** an accounting entry. Every fee, payment, wallet top-up, canteen sale and book sale is posted to the school's accounts automatically.
- **Wallet:** a student's prepaid balance, used in the canteen and bookstore.

## Getting help

- Inside eedu.ng, use **Message Center** to message colleagues at your school.
- For problems with your school's account (SMS set-up, online payment set-up, a forgotten Portal Manager password), contact eedu.ng support using the details on the eedu.ng home page.

## Known limitations

These are current gaps in the product. Where a workaround exists, it is described in the relevant manual.

- **Lecturers:** the Lecturer role's portal (`/eedu/lecturer/`) has not been built yet. Lecturers cannot use eedu.ng after signing in until it is.
- **Bursars and Bulk SMS:** the Bursar sidebar shows **SMS & Printing**, but those screens are not part of the Bursar portal and open a "not found" page. Ask a School Admin to send bulk SMS.
- **Student permissions (exeat):** permissions can be granted from a staff member's profile. There is no button on a student's profile to grant a student permission.
- **School Admins and new exams:** only Deans, HODs and Portal Managers see the **Create Exam** button. A School Admin should ask one of them to create the term's exams.
- **Quick Portal Access "Login" tab** on the home page is empty. Students sign in from the **Login** page instead.
