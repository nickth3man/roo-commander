# One Shot Web Designer Mode - Improvement Suggestions

## Current Role
- Creates beautiful, creative web page designs (HTML/CSS/minimal JS) in a single session.
- Focuses on aesthetic impact, visual thinking, and incorporating inspiration.
- Organizes designs into folders.

## Recommended Improvements

### 1. Add Metadata Tags
- `"web-design"`, `"ui-design"`, `"visual-design"`, `"html"`, `"css"`, `"frontend"`, `"prototyping"`, `"creative"`

### 2. Escalation & Delegation
- Should be **invoked by Commander or potentially UI Designer** when a quick, high-fidelity visual draft is needed, especially based on inspiration.
- Should escalate:
  - **Need for complex interactivity or framework integration** to Frontend Developer or specific Framework Specialists after the initial design is complete.
  - **Accessibility implementation** beyond basic semantics to Accessibility Specialist.
  - **Performance optimization** of the generated code to Performance Optimizer.
- Should **not typically delegate** during its "one-shot" creation process, but its output serves as input for other modes.

### 3. Collaboration
- Primarily serves as an **initial design generator**.
- Collaborates closely with **UI Designer** (if refining concepts) or **Frontend Developer** / **Framework Specialists** (who will build upon the generated design).
- May interact with **Technical Writer** if design rationale needs formal documentation.

### 4. Role Clarification
- Emphasize the **"one-shot" creative burst** nature – focus is on delivering a complete visual draft quickly.
- Highlight the focus on **aesthetics and visual impact** over complex functionality or deep framework integration.
- Clarify the output: **Self-contained HTML/CSS/JS files** representing the design.
- Reinforce the use of **modern CSS techniques**.
- Position the output as a **high-quality starting point** for further development.

### 5. Additional Capabilities
- Support different **CSS methodologies** (e.g., BEM, utility-first if requested, though less common for pure design focus).
- Integrate basic **CSS preprocessors** (like Sass) if needed via `execute_command`.
- Offer different **levels of fidelity** or complexity based on user request.
- Generate **style guides** based on the created design (colors, typography).
- Maintain a **portfolio** or examples of generated design styles.

---

*Generated by Roo Commander, 2025-09-04*