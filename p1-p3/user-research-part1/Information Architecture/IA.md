# Information Architecture

## 1 Site Map (Hierarchy)

### Before Login
- **Home / Landing Page**
- **About FUSS (Pre-login Information)**
- **Register**
- **Login**
- **Contact / Help (Pre-login)**

### After Login
- **Student Area (After Login)**
- **Profile**
- **Registration**
- **Search Courses**
- **Schedule**
- **View and Confirm**
- **Skills and Exchange**
- **Browse/Search Skills**
- **Request Services + Messages**
- **Credits and Evaluations**
- **Canvas**
- **Announcements**
- **Courses and Assignments**
- **Submit Assignments (Receipt)**
- **Help and Contact**
- **FAQ**
- **Contact the Teaching Team**
- **Report Issues/Tickets**
- **Administrator Area**
- **Administrator Dashboard**
- **Manage Users**
- **Manage Courses and Schedules**
- **Announcement Manager**
- **Ticket Queue and Service Level Agreement (SLA)**
- **Messages and Broadcasts**
- **Reports and Audit Logs**

Cross-links:
- Dashboard “Next Class” card → Schedule → Course Details.
- Assignment List → Submit Assignment (Receipt) → History.
- Announcement Details → Contact Teaching Team → Report Issues/Submit Ticket.

---
### F1 — Registration
1. Log in → **Student Area** → **Registration**
2. **Search for courses** → View **timetables** marked with **conflicts/prerequisites**.
3. If **Approved** is displayed → **Review and confirm** → Dashboard card is updated.
4. If **Not Approved** is displayed → Return to **Search Courses** and suggest at least **2 alternative options**.

**Confirmation:** The schedule displays *specific* conflict/prerequisite reasons; the confirmation page lists fees/impacts; success prompt + email notification.

---

### F2 — Submit Assignment (with Receipt)
1. Log in → **Courses and Assignments** → **Submit Assignment**.
2. Pre-check: **Type/size/version** of the file is displayed next to the control bar.
3. Upload → **Progress + Continue/Retry** → **Receipt saved (receipt ID + timestamp)**.
4. Provide **Copy ID / Download PDF / Send Copy to Email**.

**Acceptance conditions:** Display allowed types/sizes before upload; one-time success or actionable inline errors; receipt ID can be copied.

---

### F3 — Skills and Exchange
1. Log in → **Skills and Exchange** → **Browse/Search Skills**.
2. Select provider/time slot → **Request Service + Message** (thread).
3. After completion → **Points and Evaluation** (rating, points consumed/earned).

**Acceptance:** Request with timestamp; message history retained; comments available after service completion.

---

### F4 — Announcements → Contact/Tickets
1. Log in → **Announcements** (check unread first + search).
2. Open the entry → **Contact the teaching team**.
3. If escalation is needed → **Report an issue/ticket** → **Ticket confirmation (ticket number + SLA)**.

**Acceptance conditions:** List supports unread/pinned/keywords; after confirmation, return ticket number and response time limit (e.g., 24 hours).

---

### F5 — Administrator (example)
- Log in → **Administrator Area** → **Announcement Manager** → **Messages and Broadcasts** (post).
- Log in → **Administrator Area** → **Ticket Queue and SLA** → **Reporting and Audit Log** (export weekly).

**Accept:** Operations are audited; each ticket displays an SLA timer.


