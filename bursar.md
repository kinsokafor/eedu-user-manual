# Bursar

Portal: `/eedu/bursar/`

The Bursar manages the school's money:
- fees and payments;
- exemptions and debtor reminders;
- the school's accounts (double-entry journals);
- student wallets and the canteen's accounts;
- the bookstore.

School Admins and Portal Managers can do everything in this manual too.

Read [Getting started](getting-started.md) first.

---

## Your sidebar

| Section | Items |
|---|---|
| **Bursary** | Fees & Accounts · Canteen & Bookstore |
| **Management** | School · Students · Staff |
| **Utilities** | Attendance |

> The **SMS & Printing** item also appears in your sidebar, but those screens aren't part of the Bursar portal and open a "not found" page. To send debtor reminders, use the **SMS debtors** button on a fee (below). For other bulk SMS, ask a School Admin.

Your dashboard shows the school counters, a fee collection summary, and the Canteen and Bookstore cards.

---

## Before you start: accounts

Every fee, payment, top-up and sale is posted to the school's accounts automatically. Set these up first.

### Chart of accounts
**Fees & Accounts → Accounts → Add Account Item**
- Enter the **Item** name, for example *School Fees Income*, *Zenith Bank*, *Student Wallets* or *Canteen Income*.
- Choose its **Category**: *Asset*, *Liability*, *Income*, *Expense* or *Equity*.

A typical set:

| Account | Category | Used for |
|---|---|---|
| School Fees Income (one per fee type if you like) | Income | The **Journal** of each fee |
| Your bank account(s) | Asset | Bank transfers received |
| Office Receipts / Cash | Asset | Cash received at the bursary |
| Student Wallets | Liability | Money held in students' wallets |
| Canteen Income | Income | Canteen sales |
| Bookstore Income | Income | Book sales and book packs |

**All Accounts** lists every account with its total debits, total credits and balance. Filter by category, and print. Click an account to open its **ledger**: every entry for a fiscal year with its date, debit, credit, running balance and description.

### Fee payment options (set by eedu.ng support)
Payment settings are managed by eedu.ng support (**Fees & Accounts → Options**):
- **Update payment manually?** Lets the bursary record payments by hand.
- **Journal for manual payment updates:** the Office Receipts account.
- **Use wallet?** and **Wallet Journal.**
- **Currency.**
- **Activate virtual account?** Parents pay into a one-time bank account.
- **Charge on parents?** Whether transfer charges are added to what parents pay.

Ask support to switch on what your school needs.

---

## Fees

### Creating a fee
**Fees & Accounts → Add New**
1. **Journal:** the income account this fee is credited to.
2. **Name of Fee**, for example *School Fees* or *Development Levy*.
3. **Amount.**
4. **Period:** the **Term** and **Section** (session).
5. **Class:** one or more. **Stream:** one or more.
6. Save. A fee is created for each class and stream combination, and the page lists this term's fees.

> **One fee per class and stream per term.** If a class and stream already has a fee this term, a second one isn't created. To charge more, **Edit** the existing fee's amount, or create the extra fee for the next term. Book packs from the bookstore are separate and don't count against this.

### Managing fees
**Fees & Accounts → Manage Fees.** Choose the **Section** and **Term**. Each fee shows:
- its class and stream, and the amount;
- the **expected amount** (amount × students) and the **recovered amount**, with a progress bar;
- the **total debt**;
- the number of students who have **Paid**, **Partly paid**, **Not paid** or been **Exempted**.

Open a fee to see its dashboard.

### A fee's dashboard
**Students** tab: a card for each student in the class, with their balance and status. From a card:
- **Reports:** the student's clearance bill (see below).
- **Add payment:** record a payment received at the bursary. Enter the **Amount** and a **Reference** (receipt or teller number). Only available when manual payment updates are on.
- **Exempt:** remove the student from this fee, for example on a scholarship. **Re-include** reverses it.
- **Generate Virtual Account:** create a one-time bank account for the parent to pay into (see below).

**Payments** tab: every payment for this fee, with the student, amount, date, reference and who captured it.

### Debtor reminders by SMS
On a fee's dashboard, **SMS reminder to debtors → SMS debtors (N)**:
1. Edit the **Message**. You can use these placeholders:
   - `{name}`: the student;
   - `{fee}`;
   - `{balance}`;
   - `{school}`.
2. Check the preview:
   - the first recipient's message;
   - the number of phone numbers;
   - the SMS pages per message.
   - Siblings who share a phone number get one combined message listing each child and the total.
   - Debtors without a valid phone number are listed as skipped.
3. Choose **Send**. If reminders were sent recently, you're warned before sending again.

Bulk SMS must be enabled for your school.

### A student's clearance bill
From a student card choose **Reports**, or open a student's profile → **Financial Reports**. It shows:
- the **Termly Clearance Bill** for the fee;
- the student's **Payment records** (date, amount, reference, who approved it);
- their **Debt profile** across all terms (fee, period, amount, paid, balance);
- the **Total debt** and **Clearance Status**: *Cleared* or *Not cleared*.

Print it for the parent.

### Online payment by virtual account
When virtual accounts are active, a parent pays like this:
1. They open the student's portal → **School fees** and choose **Pay** on a fee. The bursar can also **Generate Virtual Account** from the student's card.
2. eedu.ng shows a bank **Account number**, **Bank** and **Account name**, the exact **amount due**, and an expiry countdown.
3. The parent transfers **the exact amount** before it expires, then chooses **I have made this payment**.
4. The payment is recorded against the fee and posted to the accounts automatically.

Anything paid above the balance goes into the student's wallet.

### Payment report
**Fees & Accounts → Payments.** Choose a **Start date** and **End date** to list every payment received: purpose, amount and date.

---

## Journals

### Posting a journal entry
**Fees & Accounts → Create Entry**
1. Enter the **Date**, the **Voucher Number/Doc**, and the **Particulars/Description**.
2. Under **Credit account** and **Debit account**, add one or more lines. Each line has an **Account**, an **Amount** and an optional **Sub note**, which shows in the account's ledger.
3. The **Total Credit** and **Total Debit** boxes turn blue when they match. They must be equal, and the same account can't appear on both sides.
4. Save.

Use journals for anything eedu.ng doesn't post automatically: expenses, bank charges, opening balances, transfers between accounts.

### Trial balance
**Fees & Accounts → Trial Balance**
- **As of:** the date to report up to. Tick **Limit to a start date** to report a period only.
- The **trial balance** lists each account's total debit, credit and balance (Dr − Cr), and shows *Balanced* or *Not balanced by …*.
- The **account summary** groups accounts by category for the period.
- Print both for the school's records.

---

## Wallets and the canteen

### Canteen and wallet settings
**Canteen & Bookstore → Canteen Settings.** The canteen can't sell and top-ups are refused until these are set.
- **Wallet account:** a *liability* account holding money in student wallets.
- **Office receipts account:** debited for cash wallet top-ups and manual fee payments.
- **Canteen income account.**
- **Daily spending limit per student:** 0 or empty means no limit.

How postings work:
- a cash top-up is *Dr office receipts / Cr wallet*;
- a transfer top-up debits the bank account you choose;
- a canteen sale is *Dr wallet / Cr canteen income*.

The wallet and office receipts accounts are the same settings as "Wallet Journal" and "Journal for manual payment updates" in the fee options. Changing one changes the other.

### Topping up a wallet
**Canteen & Bookstore → Wallet Top-up**
1. Find the student by scanning their ID card or searching by name or passcode.
2. Enter the **Amount** and choose the **Method**:
   - **Cash:** a reference is optional.
   - **Bank transfer:** the **Reference** is required, and choose the bank account it was **Paid into**.
3. **Record top-up** and confirm. The new balance and voucher number are shown.

Students and parents see every movement in the student portal's **Wallet statement**.

### Canteen items
**Canteen & Bookstore → Canteen Items**
- Add items with a **Name**, **Price** and **Status** (*Active* or *Inactive*).
- Price changes apply to new sales only.
- Items that have been sold can be made inactive, but not deleted.

### Canteen sales report
**Canteen & Bookstore → Canteen Sales**
- Choose a date range. The report shows the total, the number of transactions, voided sales, sales by item, and each sale (student, items, total, seller).
- **Void** a sale (for example, one charged in error) with a reason. The money goes back to the student's wallet and the accounts are reversed.

Canteen staff sell at the counter; see the [Canteen manual](canteen.md).

---

## Bookstore

**Canteen & Bookstore** (when the Bookstore is on)

### Settings first
**Bookstore Settings:** choose the **Bookstore income account**. The page shows whether the income, wallet and cash receipts accounts are set. Book sales are refused until they are.

### Books and stock
**Books & Stock**
- **Add book:**
  - title, author, publisher, subject, edition, and ISBN (optional);
  - **Selling price** and **Cost price**;
  - **Reorder at**: the stock level that counts as low.
- **Receive:** copies delivered by a supplier, with an optional cost per copy and a supplier or invoice reference.
- **Adjust:** correct the stock after a count, a damage or a loss. Use a minus sign to remove copies. A **Reason** is required.
- **History:** every stock movement for a book.
- **Edit**, **Archive** or **Restore** a book.
- Search, or tick **Low stock only**.

Stock only changes through receiving, sales and adjustments, so it always matches the history.

### Selling books
**Sell Books**
1. For a student: scan their ID card or search, then **Add** *class*'**s required books** to fill the cart from the class list.
2. For someone else, such as a parent buying for a sibling, choose **Someone else** and type the buyer's name.
3. Tap books to add them, and change the copies if needed.
4. Choose how they pay:
   - **Wallet** (students only; the balance must cover it);
   - **Cash**;
   - **Bank transfer**, choosing the account it was **Paid into**.
5. **Sell.** A receipt appears. **Print** it.

### Class book lists
**Class Lists & Packs**
1. Choose the **Term** and **Class**.
2. **Add a book…** to the list, set it as *Required* or *Recommended*, and the **Copies**. **Save list.**
3. **Copy all classes from another term…** copies every class's list into this term.

Students see their class's list in their portal (**My Books**).

### Book packs paid through fees
On the same page, under **Book pack**:
1. **Make a pack from the required books.**
2. **Publish as a fee.** This creates an ordinary fee called "Books – *class* – *term*", so parents pay it the usual way (virtual account or bursary payment).
3. Once parents start paying, the pack's books and price can't change.
4. **Collection:** see who has paid (*Paid*, *Part-paid*, *Unpaid*, *Exempt*). Tick the books each student is collecting and **Hand over**. Only paid or exempt students can collect; a School Admin can override this with a reason.
5. **Close pack** when collection is over.

### Bookstore reports
**Reports**
- **Sales:** for a date range, the total, sales by payment method, voided sales, sales by book, and each sale. Open a **Receipt** to reprint or **Void** it. Voiding restocks the books, refunds a wallet, and reverses the accounts.
- **Stock:** copies and titles held, value at cost and at selling price, and books low on stock.

---

## Students and staff

- **Management → Students:** view students, add or import students, manage the class list, and print class lists. See the [School Admin manual](school-admin.md#students).
- **Management → Staff:** the staff list, staff profiles and attendance reports.
- A student's profile has **Financial Reports**: their clearance bill and debt profile.

## Attendance

**Utilities → Attendance:**
- the attendance calendar;
- **Term Duration** (opening and closing dates);
- **Holidays**.

See the [School Admin manual](school-admin.md#attendance).
