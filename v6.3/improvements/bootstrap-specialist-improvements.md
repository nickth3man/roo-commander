# Bootstrap Specialist Mode - Improvement Suggestions

## Current Role
- Specializes in building responsive websites using Bootstrap.
- Covers grid system, components, utilities, Sass customization, and JS components.

## Recommended Improvements

### 1. Add Metadata Tags
- `"bootstrap"`, `"css"`, `"frontend"`, `"responsive-design"`, `"ui-framework"`

### 2. Escalation & Delegation
- Should be **automatically invoked** when discovery detects Bootstrap usage (CSS classes, JS imports, `package.json`).
- Should escalate:
  - **Complex JavaScript interactions** beyond Bootstrap components to Frontend Developer or JS specialists.
  - **Accessibility issues** to Accessibility Specialist.
  - **Performance bottlenecks** to Performance Optimizer.
  - **Build process issues** (Sass compilation) to relevant build tool specialists (e.g., Vite, Webpack).
- Should accept escalations from **project onboarding**, **UI Designer**, or general frontend modes.

### 3. Collaboration
- Work closely with:
  - **UI Designer** (implementing designs with Bootstrap)
  - **Frontend Developer** (integrating Bootstrap with other JS)
  - **Accessibility Specialist**
  - **Performance Optimizer**

### 4. Role Clarification
- Emphasize:
  - **Grid system** mastery (`.container`, `.row`, `.col-*`).
  - Correct usage of **core components** (Navbar, Modal, Card, Forms, etc.).
  - Effective use of **utility classes**.
  - **Responsiveness** implementation.
  - **Customization** via Sass variables or CSS variables.
  - Handling **Bootstrap JS components** and dependencies (Popper.js).

### 5. Additional Capabilities
- Support different **Bootstrap versions** (v4, v5).
- Provide guidance on **theming** and **custom builds**.
- Maintain a **knowledge base** of Bootstrap patterns and common issues.
- Advise on **migrating** between Bootstrap versions.

---

*Generated by Roo Commander, 2025-09-04*