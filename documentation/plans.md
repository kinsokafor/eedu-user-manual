---
description: >-
  Your school's plan: what each plan includes, the trial after signing up, renewal, invoices, and what you see when
  something isn't in your plan.
icon: layer-group
---

# Plans and subscriptions

Every school on eedu.ng is on a **plan**. The plan decides which parts of eedu.ng your school can use. Your school never loses access to eedu.ng itself: when something isn't in your plan, only that part is unavailable, and everything you entered is kept.

## The plans

eedu.ng support decides exactly what each plan includes and can change it. By default:

| | Free | Basic | Standard | Complete |
|---|:-:|:-:|:-:|:-:|
| Students, staff, classes, messages | ✓ | ✓ | ✓ | ✓ |
| Entering and updating scores, broadsheets | ✓ | ✓ | ✓ | ✓ |
| Canteen and wallets | ✓ | ✓ | ✓ | ✓ |
| Publishing results | | ✓ | ✓ | ✓ |
| Printing results and broadsheets | | ✓ | ✓ | ✓ |
| Bursary: fees, payments, debtors, online payment | | ✓ | ✓ | ✓ |
| Journals and accounts | | ✓ | ✓ | ✓ |
| Bulk SMS | | ✓ | ✓ | ✓ |
| Timetables | | | ✓ | ✓ |
| Pastoral care | | | ✓ | ✓ |
| Attendance (clocking in and out at the gate) | | | ✓ | ✓ |
| Computer-based tests (CBT) | | | | ✓ |
| Remote lessons | | | | ✓ |
| Bookstore | | | | ✓ |

The current list and prices are on the **Pricing** page of the eedu.ng home page. Plans are priced **per child per term**.

## Your plan on the dashboard

Portal Managers and School Admins see a **plan banner** at the top of the eEdu Admin dashboard:

- ***Plan name* · renews automatically on *date*:** your plan is active.
- **Trial of the *plan name* · ends *date*:** your school is on its trial (see below).
- **You're on the Free plan:** scores can be entered, but the paid parts are off.
- **Plan balance outstanding:** any plan invoice that hasn't been fully paid yet.

## When something isn't in your plan

- **Whole screens** (the bursary, journals and accounts, bulk SMS, and the gate's Clock In and Clock Out) show a **🔒 … is locked** notice instead of the screen. The notice says which plan includes it when you're allowed to see your school's plan.
- **Buttons** that aren't in your plan are removed and replaced by a notice. On broadsheets, the annual broadsheet and report cards, **Print** and **Publish** disappear and a notice says *"Printing results and Publishing results are not included in this school's plan."* Scores can still be entered and the broadsheet can still be viewed.
- **Dashboard cards** for Timetable, CBT, Remote Lessons, Bookstore and Pastoral Care are hidden. Where a card shows, it may say *"Comes with the Standard Plan. Contact eedu.ng to upgrade."*
- **Nothing is deleted.** When the plan changes, everything comes back as it was.

## Signing up: the 30-day trial

When a school signs up from the **Pricing** page it chooses a plan:

1. The school starts a **30-day trial** of that plan straight away, with all the plan's features on.
2. During the trial, eedu.ng support contacts the school to agree the plan and its price. When agreed, support **confirms** the plan.
3. **If the plan is confirmed,** it carries on and renews every term.
4. **If it isn't confirmed by the end of the trial,** the school moves to the **Free plan** and the plan's features switch off. Nothing is lost; contact eedu.ng support to choose a plan.

Signing up for the **Free plan** starts no trial.

## Renewal and paying

- **Plans renew automatically every term.** Nobody has to renew them.
- **Schools pay after the term.** At the end of each term eedu.ng sends an invoice worked out from your number of active students, or from the price agreed with your school.
- **An unpaid invoice never locks your school out.** It shows as a balance on the dashboard banner.
- **Changing plan:** contact eedu.ng support. A new plan's features switch on straight away.
- **Leaving a plan:** when eedu.ng support stops your plan, your school moves to the Free plan straight away.

## (Software Engineer) Managing plans

These screens are in the **School** menu of the eEdu Admin portal. Check the school name in the sidebar first: Plan & Billing works on the school currently selected.

- **Plan & Billing**
  - **Plan:** assign or change the school's plan. A plan you assign renews every term. The switch *renews automatically every term* is on; switching it off cancels the plan immediately and moves the school to Free.
  - **Trials:** a school on trial shows **Confirm plan** and **End trial now**.
  - **Negotiated pricing:** plan price per child, a negotiated price per child, or a flat amount per term. It applies to every future invoice and updates draft invoices; issued invoices keep their price.
  - **Invoices:** preview and create the term's draft invoice, correct the student count or price, **Issue** it, and record payments (bank transfer, cash, cheque, POS). Void an invoice only while nothing has been paid on it.
- **Plan Invoices:** every school's invoices, the total outstanding, **Trials awaiting confirmation**, and **Bill the term**, which creates draft invoices for every school on a paid plan.
- **Plan Features:** which features each plan includes, including the Free plan.
  - A feature with a **key** switches that part of eEdu on or off with the plan. Pick a key from the suggestions, or from **Keys not used yet**.
  - Changes apply to a school when it next moves onto a plan. **Apply to all schools now** applies them straight away, and replaces any feature switches set by hand.
- **Feature switches** on the eEdu Admin dashboard still turn a single feature on or off for one school. The school's plan sets them again when the school moves to another plan.
