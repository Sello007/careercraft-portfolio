[# 🚀 CareerCraft E-Portfolio |
> **Platform URL:** [careercraft-sa.netlify.app](https://careercraft-sa.netlify.app)  
> **Author / Product Owner:** Makuks (Cape Peninsula University of Technology - DPICTA / PRP370S)  
> **Execution Period:** July 2026 – October 2026

---

## 🌟 Executive Summary & Introduction
Welcome to the official digital e-portfolio for **CareerCraft South Africa**, an all-in-one digital career engineering portal designed specifically to bridge the gap between education and employment for South African students and graduates. This repository documents our complete project lifecycle, adhering strictly to Agile methodologies, rigorous software engineering practices, and CPUT assessment standards.

---

## 📑 Table of Contents
1. [Agile Team Charter](#1-agile-team-charter)
2. [User Stories and Tasks](#2-user-stories-and-tasks)
3. [Product Backlog](#3-product-backlog)
4. [Sprint Backlog](#4-sprint-backlog)
5. [Agile Logbook (July – October 2026 Chronological Record)](#5-agile-logbook-july--october-2026-chronological-record)

---

## 1. 🤝 Agile Team Charter

### 🎯 Project Overview & Vision
* **Vision Statement:** To bridge the gap between education and employment by empowering South African students and graduates with an all-in-one digital career engineering portal for profile creation, career navigation, and professional storytelling.
* **Mission Statement:** Deliver a robust, mobile-optimized, and secure web platform that simplifies career development, provides transparent pricing tiers, and equips users with precision tools to showcase their professional competencies.

### ⚖️ Core Team Operating Norms & Values
1. **Radical Transparency:** All project artifacts, code versions, and documentation are shared openly. "No surprises"—blockers or technical bottlenecks are flagged immediately during stand-ups.
2. **Synchronous Prioritization:** Daily stand-up synchronization focuses strictly on three pillars: What was completed yesterday, what is planned for today, and what impediments exist.
3. **Sustainable Pace:** Maintaining a disciplined workflow to balance rigorous third-year ICT coursework and exam schedules with high technical output.
4. **Iterative Learning:** Every sprint concludes with a retrospective to analyze successes, bottlenecks, and areas for continuous improvement.

### 👥 Personnel Roles & RACI Matrix
| Project Task | Product Owner (Makuks) | Lead Frontend Dev | UI/UX & Branding | QA & Community Liaison |
| :--- | :--- | :--- | :--- | :--- |
| **Project Plan & Charter** | A / R | C | C | I |
| **UI Layouts & Netlify Deployment** | A | R | C | I |
| **User Profile & Authentication** | A | R | I | C |
| **Investor Pitch & Deliverables** | A / R | C | R | C |
| **MVP Student Testing & Validation** | A | I | I | R |

*(Role Legend: A = Accountable, R = Responsible, C = Consulted, I = Informed)*

### 🔍 Critical Reflection on Team Charter
Establishing this charter early in the semester provided essential structure for our team. Balancing third-year ICT coursework and exam schedules with active development required strict adherence to our sustainable pace norm. When communication bottlenecks arose during pitch week preparations in July, our commitment to radical transparency allowed us to quickly reassign speaking roles and leverage peer support effectively.

> **[📸 Insert Screenshot Here: Team Trello Board or Collaboration Setup]**  
> *Figure 1.1: Snapshot of our Agile team collaboration channels and task boards.*

---

## 2. 📝 User Stories and Tasks

### 📋 Epic 1: Core Portal Architecture & Hosting Setup
* **User Story 1.1:** As a site visitor, I want to land on a fast, responsive, and professionally branded homepage so that I immediately understand CareerCraft's value proposition.
  * **Acceptance Criteria:** Landing page loads in under 2 seconds; clear call-to-action buttons for signing up and comparing pricing.
  * **Tasks:**
    * Develop semantic HTML5 / CSS layout with Tailwind styling.
    * Configure continuous deployment pipeline targeting Netlify (`careercraft-sa.netlify.app`).
    * Implement clean product logo and responsive navigation menus.

* **User Story 1.2:** As a new user, I want to sign up securely with my credentials so that I can establish a private workspace.
  * **Acceptance Criteria:** Email format and password strength validation; secure token storage.
  * **Tasks:**
    * Build frontend forms for `/signup` and `/login` routes.
    * Establish backend authentication endpoints and database linkages.

### 📋 Epic 2: Profile Management & Membership Tiers
* **User Story 2.1:** As a registered user, I want to edit my professional profile (`/profile`) so that my career goals, education history, and core skills are accurately stored.
  * **Acceptance Criteria:** Form inputs retain state across sessions; successful save confirmation message displayed to the user.
  * **Tasks:**
    * Design `/profile` form UI supporting rich text entries.
    * Implement data persistence routines to connect form inputs to cloud storage.
    * Handle edge cases for incomplete profile fields.

* **User Story 2.2:** As a student user, I want to compare membership options (Free, Starter, Pro) so that I can select the appropriate level of career support.
  * **Acceptance Criteria:** Pricing page (`/pricing`) clearly outlines features, limitations, and upgrade paths.
  * **Tasks:**
    * Code responsive pricing tier comparison cards.
    * Link tier selection buttons directly to user upgrade onboarding workflows.

### 🔍 Critical Reflection on User Stories
Decomposing the platform into precise user stories with testable acceptance criteria kept development focused. Rather than attempting to build all features simultaneously, prioritizing core authentication and profile persistence first ensured our MVP remained stable and functional before moving on to advanced modules.

> **[📸 Insert Screenshot Here: Live Netlify Web App Interface - careercraft-sa.netlify.app]**  
> *Figure 2.1: The deployed CareerCraft landing page showing responsive design and navigation.*

---

## 3. 📊 Product Backlog (July – October 2026)

| Backlog ID | Feature / Epic Description | Priority | Current Status | Story Points | Target Milestone |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **PB-01** | Landing page responsive design & Netlify deployment | High | Completed | 5 | July 2026 |
| **PB-02** | Investor-style pitch deck preparation & delivery | High | Completed | 5 | Mid-July 2026 |
| **PB-03** | User Sign-Up & Login authentication flows (`/signup`, `/login`) | High | Completed | 8 | Late-July 2026 |
| **PB-04** | Pricing page & membership tier comparison (`/pricing`) | Medium | Completed | 3 | August 2026 |
| **PB-05** | User Profile data persistence & form state handling (`/profile`) | High | In Progress | 8 | August-September 2026 |
| **PB-06** | MVP validation testing with real student cohorts | Medium | In Progress | 8 | September 2026 |
| **PB-07** | Advanced CV template builder & export module | High | To Do | 13 | October 2026 |
| **PB-08** | Institutional partner dashboard integration | Low | To Do | 8 | Post-October 2026 |

### 🔍 Critical Reflection on Product Backlog
Managing the backlog as a living document allowed us to adapt effectively to changing academic requirements and user feedback. For instance, prioritizing MVP validation testing (PB-06) after the July pitch enabled us to gather real-world student insights that directly shaped our October CV builder roadmap.

> **[📸 Insert Screenshot Here: Product Backlog View in Trello or GitHub Projects]**  
> *Figure 3.1: Overview of our master backlog tracking and item estimations.*

---

## 4. 🏃‍♂️ Active Sprint Backlog & Iteration Planning

* **Sprint Focus:** Profile state persistence refinement, MVP feedback incorporation, and preparation for advanced CV template integration.
* **Sprint Duration:** 2 Weeks (Mid-October 2026 Cycle)

| Task ID | Task Description | Assignee | Status | Effort Estimate |
| :--- | :--- | :--- | :--- | :--- |
| **T-201** | Refine `/profile` form input state handling and error alerts | Frontend Team | In Progress | 3 pts |
| **T-202** | Conduct session persistence tests across multiple browser instances | QA / Testing | To Do | 2 pts |
| **T-203** | Aggregate student feedback from September MVP testing sessions | Community Liaison | Completed | 5 pts |
| **T-204** | Audit Netlify deployment headers and security configurations | DevOps | Completed | 1 pt |
| **T-205** | Outline database schema requirements for the CV builder module | Backend Dev | To Do | 5 pts |

### 🔍 Critical Reflection on Sprint Backlog
Time-boxing our work into two-week iterations maintained continuous momentum. Breaking large epic features into manageable 1-to-5-point tasks ensured clear accountability and allowed us to track velocity accurately across busy university semesters.

> **[📸 Insert Screenshot Here: Active Sprint Board / Kanban Board]**  
> *Figure 4.1: Active sprint task board showing items in progress and completed.*

---

## 5. 📖 Agile Logbook (July – October 2026 Chronological Record)

### 🗓️ Phase 1: Pitch Week & Initial Deliverable Push (Mid-July 2026)
* **Date: 14 July 2026 (Tuesday)**
  * **Completed:** Facilitated sprint planning for pitch week; reviewed the 16-slide investor deck structure (problem, market, business model, financials) with Livhuwani; confirmed team speaking roles.
  * **Plan:** Draft speaker notes and talking points for personal presentation sections; finalize rehearsal schedules.
  * **Impediments & Resolution:** Initial lack of advanced design tools for a polished PowerPoint aesthetic; resolved by consulting a senior 4th-year IT student for slide design tips.

* **Date: 15 July 2026 (Wednesday)**
  * **Completed:** Successfully delivered the CareerCraft investor-style pitch to the assessment panel (presented by Lwandile at 14:30) with full team backing on timing cues and slide checks.
  * **Plan:** Analyze panel feedback to identify gaps in Deliverable 2; initiate secondary competitor validation research.
  * **Impediments & Resolution:** Home network instability during the online presentation session; mitigated by relocating to the campus IT lab for a reliable connection.

* **Date: 16 July 2026 (Thursday)**
  * **Completed:** Reviewed formal panel feedback; initiated deep-dive research into South African youth unemployment statistics and competing career-guidance platforms.
  * **Plan:** Verify market opportunity statistics; benchmark CareerCraft against existing solutions to strengthen the business plan revision.
  * **Impediments & Resolution:** Encountered paywalls and outdated datasets when searching for specific employment figures, requiring extra verification steps.

* **Date: 17 July 2026 (Friday)**
  * **Completed:** Consolidated weekly research findings into formal notes for the Deliverable 2 revision; hosted a team retrospective to analyze pitch strengths and areas for workflow refinement.
  * **Plan:** Update the product backlog with follow-up MVP validation testing items; await official grading feedback from the lecture panel.
  * **Impediments & Resolution:** None pending official assessment scores.

### 🗓️ Phase 2: MVP Validation & Feature Expansion (August – September 2026)
* **Sprint Review & Retrospective Highlights:**
  * Focused heavily on bridging frontend views (`/pricing`, `/profile`) with backend user state persistence. Coordinated with university career centres and student volunteers to run pilot testing on core portal navigation. Addressed minor state-management bottlenecks in profile editing forms, ensuring smoother data entry for student users. Conducted extensive performance benchmarks on database response times during peak authentication loads.

### 🗓️ Phase 3: Final Polish & Portfolio Consolidation (October 2026)
* **Status Review & Semester Completion:**
  * Netlify deployment operating stably at `careercraft-sa.netlify.app`. Core navigation, pricing comparisons, and login/signup flows fully operational. Finalized documentation and structured markdown files for GitHub Pages submission to meet CPUT PRP370S requirements. Performed final security audits and code refactoring to prepare for institutional handover.

### 🔍 Overall Logbook Reflection
Maintaining this chronological logbook transformed daily challenges—such as connectivity glitches during online presentations, research paywalls, and scope adjustments—into valuable learning opportunities. Documenting our retrospectives ensured that our team continuously adapted its processes, resulting in a robust, production-ready portfolio.

> **[📸 Insert Screenshot Here: GitHub Pages Live Portfolio Rendering]**  
> *Figure 5.1: Final published GitHub Pages documentation site view.*

---
*© 2026 CareerCraft South Africa & Cape Peninsula University of Technology (CPUT). Professional Academic Portfolio.*
](https://canva.link/m7q8jknwttzfiiu)
