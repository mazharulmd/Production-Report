# Natural Denims Limited — NDL Unit-02 RMG Multi-Department Production ERP

Interactive Role-Based Production & WIP ERP web application for Natural Denims Limited (Tongabari, Ashulia, Savar, Dhaka) Unit-02.

## Role-Based Access & Default Credentials
- **Administrator**: `admin@ndlunit02.com` / `Admin@123` (Full access: Dashboard, Master Unit-02 Report, all 4 Departments, Submissions Review, User Management & Settings, Bonus Policy)
- **Cutting Department**: `cutting@ndlunit02.com` / `Cut@123`
- **Sewing Department**: `sewing@ndlunit02.com` / `Sew@123`
- **Wash Department**: `wash@ndlunit02.com` / `Wash@123`
- **Finishing Department**: `finishing@ndlunit02.com` / `Fin@123`

## Features
- **Separate Department Workspaces**: Cutting, Sewing, Wash, and Finishing modules with exact Excel formulas, inline editing, CSV/JSON upload, and CSV export.
- **Submission & Approval Workflow**: Department users submit daily reports to the Administrator for review, approval, editing, or revision feedback.
- **User Management & Settings**: Admin can create, edit, reset passwords, or disable department user accounts.
- **Master Unit-02 Consolidated Report**: Automatic PO & Style aggregation across all 4 departments.

## Deploy to GitHub (`mazharulmd/Production-Report`)
```bash
git init
git add index.html README.md
git commit -m "Upgrade NDL Unit-02 ERP with Multi-Department RBAC & Login"
git remote add origin https://github.com/mazharulmd/Production-Report.git
git branch -M main
git push -u origin main
```
