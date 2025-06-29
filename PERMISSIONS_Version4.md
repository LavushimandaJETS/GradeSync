# GradeSync User Permissions Matrix

| Feature                                         | Subject Teacher            | Class/Grade Teacher         | Administrator/Deputy Head    |
|-------------------------------------------------|:-------------------------:|:---------------------------:|:----------------------------:|
| Create own account (registration)               | ✔️ (if enabled)\*          | ✔️ (if enabled)\*           | ✔️ (for others)              |
| Approve account requests                        | ❌                         | ❌                          | ✔️                           |
| Login                                           | ✔️                         | ✔️                          | ✔️                           |
| See assigned learners (for their subject)       | ✔️                         | ✔️ (all in class/grade)     | ✔️ (all learners)            |
| Enter grades (subject only)                     | ✔️                         | (if also a subject)         | ✔️ (all, if needed)          |
| Enter grades (all subjects)                     | ❌                         | (if also a subject)         | ✔️                           |
| Print subject analysis (quality/quantity/sex)   | ✔️ (only their subject)    | ✔️ (whole class/grade)      | ✔️ (any class/grade)         |
| Print mark schedule (subject learners/results)  | ✔️ (only their subject)    | ✔️ (all subjects in class)  | ✔️ (all classes/subjects)    |
| Print full report cards (all subjects)          | ❌                         | ✔️ (own class/grade)        | ✔️ (all classes)             |
| Generate results analysis (by grade, all subs)  | ❌                         | ✔️                          | ✔️                           |
| Track subject teacher grading progress          | ❌                         | ✔️ (in their class/grade)   | ✔️ (all teachers)            |
| Set portal deadlines/lock results portal        | ❌                         | ❌                          | ✔️                           |
| Manage teacher accounts/assignments             | ❌                         | ❌                          | ✔️                           |
| Export reports/analysis (PDF/Excel)             | ✔️ (their subject)         | ✔️ (their grade)            | ✔️ (all)                     |
| Bulk upload learners (CSV)                      | ✔️                         | ✔️                          | ✔️                           |
| Access audit logs                               | ❌                         | ❌                          | ✔️                           |
| Password reset (self-service)                   | ✔️                         | ✔️                          | ✔️                           |
| Mobile-friendly access                          | ✔️                         | ✔️                          | ✔️                           |
| Role-based dashboard                            | ✔️                         | ✔️                          | ✔️                           |
| Receive notifications (deadlines, reminders)    | ✔️                         | ✔️                          | ✔️                           |
| Access help/support resources                   | ✔️                         | ✔️                          | ✔️                           |

### Legend:
- ✔️ = Allowed
- ❌ = Not Allowed
- \* = Only if self-registration is enabled in system settings (otherwise, admin creates all accounts)

---

**Notes & Recommendations:**
- **Bulk upload by all:** All roles can upload learners via CSV, but consider audit logs and duplicate/conflict checks for data integrity.
- **Account creation:** For most secure operation, recommend admin creates all accounts; self-registration can be enabled for flexibility.
- **Export, mobile, notifications, and help:** Ensure user experience and accessibility.
- **Audit logs:** Only available to admin for tracking critical actions (grade changes, data uploads, etc).

This matrix covers all discussed and recommended permissions and features for GradeSync.