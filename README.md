# 📋 Probation Assessment Dashboard — NALCO

A responsive, multi-panel interactive web dashboard developed during a summer internship at **National Aluminium Company Limited (NALCO), Bhubaneswar**. The dashboard digitizes the **employee probation assessment and approval workflow** across multiple departments using a Bootstrap accordion layout.

---

## 📌 Project Info

| Field | Details |
|---|---|
| Organization | National Aluminium Company Limited (NALCO) |
| Department | Corporate Systems Department |
| Duration | May 2025 – June 2025 |
| Developer | Priyanshu Jena, NFSU Delhi |

---

## 🚀 Features

- **Multi-Panel Accordion Layout** — 10+ collapsible panels, each representing a department's role in the probation assessment workflow:
  - Employee Details
  - Assessment by Reporting Officer
  - Remark of Reviewing Officer
  - HOD Approving
  - Disciplinary Cell Approving
  - Unit Vigilance Cell
  - Corporate Vigilance Cell
  - Vigilance HOD
  - CVO (Chief Vigilance Officer)
  - Corporate HRD Department

- **Radio-Based Assessment Inputs** — Each panel includes radio buttons for performance criteria (Satisfactory / Unsatisfactory) across categories like Performance, Job Knowledge, Conduct & Discipline, and Attendance.

- **Conditional Reason Box** — Selecting "Unsatisfactory" in any assessment section automatically reveals a reason/justification textarea, ensuring structured feedback.

- **Recommendation Section** — Supports three recommendation outcomes:
  - Probation closed (confirmed) — reveals confirmation date field
  - Probation extended by 3 months — reveals extension reason field
  - Services terminated — reveals termination reason field

- **Disciplinary Cell Panel** — Captures suspension status, chargesheet details, investigation proceedings, and applicable rules/provisions with conditional field display.

- **Unit Vigilance Cell Panel** — Captures officer details, service history, and pending action flags with conditional Yes/No logic.

- **Forward Button Workflow** — Each panel includes a "Forward" button to simulate real-world departmental approval routing.

- **Accordion Icon Toggle** — Panel headers display `+` / `–` icons that update dynamically on expand/collapse using jQuery.

- **Responsive Design** — Built with Bootstrap grid and CSS Flexbox for consistent rendering across desktop and tablet devices.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Semantic structure and form elements |
| CSS3 | Custom styling, layout, and responsive design |
| Bootstrap 3.4.1 | Accordion panels, grid system, button styles |
| JavaScript | Conditional logic, field toggling, dynamic UI |
| jQuery 3.2.1 | DOM manipulation, accordion icon switching |

---

## 📁 Project Structure

```
probation-assessment-dashboard/
│
├── probation.html      # Main dashboard file
└── README.md           # Project documentation
```

> Note: All CSS and JavaScript is embedded within `probation.html` for standalone use.

---

## 🖥️ Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/probation-assessment-dashboard.git
   ```
2. Open `probation.html` in any modern browser — no server or build tools required.
3. Click on any accordion panel header to expand it and interact with the assessment form.

---

## 🔄 Workflow Overview

```
Employee Details
      ↓
Reporting Officer Assessment
      ↓
Reviewing Officer Remarks
      ↓
HOD Approval
      ↓
Disciplinary Cell
      ↓
Unit Vigilance Cell
      ↓
Corporate Vigilance Cell
      ↓
Vigilance HOD
      ↓
CVO
      ↓
Corporate HRD Department
```

Each stage uses a **Forward** button to simulate passing the assessment to the next department.

---

## 📸 Preview

> The dashboard opens with all panels collapsed, showing department names with `+` icons. Expanding a panel reveals its assessment form with role-specific inputs, radio buttons, textareas, and action buttons.

---

## 📄 License

This project was developed as part of an internship at NALCO. For educational and demonstration purposes only.
