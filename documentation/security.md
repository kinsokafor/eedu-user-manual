---
description: >-
  Clocking students and staff in and out at the gate, and recording gate incidents.
icon: shield-halved
---

# Security (Gate)

Portal: `/eedu/security/`

Security officers record everyone entering and leaving the school by scanning ID cards. They see at a glance who is inside, who has left, and who is on permission. They can also record gate incidents such as lateness.

Read [Getting started](getting-started.md) first. The best device is a phone or tablet with a working camera, kept at the gate and signed in.

---

## Your sidebar

| Section | Items |
|---|---|
| (top) | Dashboard · Message Center |
| **Utilities** | Attendance (Clock In, Clock Out) · Gate Incident |

---

## The gate dashboard

At the top: today's date, the school and the active term, and two large buttons: **Clock In** and **Clock Out**.

Below them:
- **Notices:**
  - "Attendance is not activated for this school": clock-ins still work, but ask the school office to have eedu.ng support switch attendance on.
  - "Today is a holiday" or "Today is one of the school's days off".
- **Counts** for **Students** and **Staff**:
  - **Arrived:** clocked in at least once today;
  - **Inside:** in the school now;
  - **Left:** clocked out;
  - **Permission:** on approved permission today.
- **Who is where:** tabs listing the people **Inside**, those who have **Left**, and those **On permission** (allowed to be away today). Each entry shows the time in and time out. Search by name or class.
  - **Refresh** updates the lists. The time of the last update is shown.

---

## Clocking people in and out

1. Tap **Clock In** (arriving) or **Clock Out** (leaving).
2. The first time, allow the browser to use the camera.
3. Hold the student's or staff member's **ID card** up to the camera. The QR code is read automatically.
4. eedu.ng shows the person's photo and name, the **Date**, the **Check in time** and the **Check out time**.
5. The screen resets itself after a few seconds, ready for the next person.

Rules:
- A person must **clock out before they can clock in again** the same day. "User already checked in for the current date" means they are already inside.
- "User is not checked in for the current date" means they never clocked in. Clock them in first if they are arriving, or report it.
- People can go in and out more than once a day: each in-and-out is recorded.
- Times use the school's time zone.

{% hint style="warning" %}
**No card?** The gate only reads ID cards. There is no passcode entry at the gate. Send the person to the school office to have their card replaced (see the [Portal Manager manual](portal-manager.md#id-cards-software-engineer)).
{% endhint %}

### Why it matters
- Each person's **attendance score** (days present ÷ school days in the term) comes from these records. Holidays, days off and approved permissions don't count as absences.
- Administrators and parents can see a student's clock-in history in their attendance report.

---

## Recording a gate incident

**Utilities → Gate Incident**, or **Record a gate incident** on the dashboard (when Pastoral Care is on).

1. Find the student by name or passcode.
2. Choose the concern **Category**, for example *Lateness* or *Uniform*. Security staff record concerns only, not commendations.
3. Enter **When** and **What happened**, and optionally **Where**. The location is recorded as *Gate*.
4. **Record.**

The entry goes to the student's form teacher and the school's managers, who follow it up. You can see the incidents you've recorded, below the form.

---

## Messages

Use **Message Center** to message the school office, for example about an unknown visitor or a student leaving without permission.
