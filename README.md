# 🚀 CareerCraft E-Portfolio | Professional Agile Project Record
> **Platform URL:** [careercraft-sa.netlify.app](https://careercraft-sa.netlify.app)[cite: 2]  
> **Author / Product Owner:** Makuks (Cape Peninsula University of Technology - DPICTA / PRP370S)[cite: 1, 3]  
> **Execution Period:** July 2026 – October 2026[cite: 2]

---

## 🌟 Executive Summary & Introduction
Welcome to the official digital e-portfolio for **CareerCraft South Africa**, an all-in-one digital career engineering portal designed specifically to bridge the gap between education and employment for South African students and graduates[cite: 2]. This repository documents our complete project lifecycle, adhering strictly to Agile methodologies, rigorous software engineering practices, and CPUT assessment standards[cite: 3, 4].

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
* **Vision Statement:** To empower South African students and young professionals by providing an all-in-one digital career engineering portal that builds professional profiles, tracks career progress, and connects users with tailored opportunities[cite: 2].
* **Mission Statement:** Simplify career development, bridge the gap between education and employment, and give every South African job seeker the precision tools needed to present their professional story with confidence[cite: 2].

### ⚖️ Core Team Operating Norms & Values
1. **Radical Transparency:** All project artifacts, code versions, and documentation are shared openly. "No surprises"—blockers or technical bottlenecks are flagged immediately during stand-ups.
2. **Synchronous Prioritization:** Daily stand-up synchronization focuses strictly on three pillars: What was completed yesterday, what is planned for today, and what impediments exist.
3. **Sustainable Pace:** Maintaining a disciplined workflow to balance rigorous third-year ICT coursework and exam schedules with high technical output.
4. **Iterative Learning:** Every sprint concludes with a retrospective to analyze successes, bottlenecks, and areas for continuous improvement.

### 👥 Personnel Roles & RACI Matrix
| Project Task | Product Owner (Makuks) | Lead Frontend Dev | UI/UX & Branding | QA & Community Liaison |
| :--- | :--- | :--- | :--- | :--- |
| **Project Plan & Charter** | A / R[cite: 1, 2] | C[cite: 1, 2] | C[cite: 1, 2] | I[cite: 1, 2] |
| **UI Layouts & Netlify Deployment** | A[cite: 2] | R[cite: 2] | C[cite: 2] | I[cite: 2] |
| **User Profile & Authentication** | A[cite: 2] | R[cite: 2] | I[cite: 2] | C[cite: 2] |
| **Investor Pitch & Deliverables** | A / R[cite: 2] | C[cite: 2] | R[cite: 2] | C[cite: 2] |
| **MVP Student Testing & Validation** | A[cite: 2] | I[cite: 2] | I[cite: 2] | R[cite: 2] |

*(Role Legend: A = Accountable, R = Responsible, C = Consulted, I = Informed)*

### 🔍 Critical Reflection on Team Charter
Establishing this charter early in the semester provided essential structure for our team. Balancing third-year ICT coursework and exam schedules with active development required strict adherence to our sustainable pace norm. When communication bottlenecks arose during pitch week preparations in July, our commitment to radical transparency allowed us to quickly reassign speaking roles and leverage peer support effectively.

> **[📸 Insert Screenshot Here: Team Trello Board or Collaboration Setup]**  
> *Figure 1.1: Snapshot of our Agile team collaboration channels and task boards.*

---

## 2. 📝 User Stories and Tasks

### 📋 Epic 1: Core Portal Architecture & Hosting Setup
* **User Story 1.1:** As a site visitor, I want to land on a fast, responsive, and professionally branded homepage so that I immediately understand CareerCraft's value proposition[cite: 2].
  * **Acceptance Criteria:** Landing page loads in under 2 seconds; clear call-to-action buttons for signing up and comparing pricing[cite: 2].
  * **Tasks:**
    * Develop semantic HTML5 / CSS layout with Tailwind styling[cite: 2].
    * Configure continuous deployment pipeline targeting Netlify (`careercraft-sa.netlify.app`)[cite: 2].
    * Implement clean product logo and responsive navigation menus[cite: 2].

* **User Story 1.2:** As a new user, I want to sign up securely with my credentials so that I can establish a private workspace[cite: 2].
  * **Acceptance Criteria:** Email format and password strength validation; secure token storage[cite: 2].
  * **Tasks:**
    * Build frontend forms for `/signup` and `/login` routes[cite: 2].
    * Establish backend authentication endpoints and database linkages[cite: 2].

### 📋 Epic 2: Profile Management & Membership Tiers
* **User Story 2.1:** As a registered user, I want to edit my professional profile (`/profile`) so that my career goals, education history, and core skills are accurately stored[cite: 2].
  * **Acceptance Criteria:** Form inputs retain state across sessions; successful save confirmation message displayed to the user[cite: 2].
  * **Tasks:**
    * Design `/profile` form UI supporting rich text entries[cite: 2].
    * Implement data persistence routines to connect form inputs to cloud storage[cite: 2].
    * Handle edge cases for incomplete profile fields[cite: 2].

* **User Story 2.2:** As a student user, I want to compare membership options (Free, Starter, Pro) so that I can select the appropriate level of career support[cite: 2].
  * **Acceptance Criteria:** Pricing page (`/pricing`) clearly outlines features, limitations, and upgrade paths[cite: 2].
  * **Tasks:**
    * Code responsive pricing tier comparison cards[cite: 2].
    * Link tier selection buttons directly to user upgrade onboarding workflows[cite: 2].

### 🔍 Critical Reflection on User Stories
Decomposing the platform into precise user stories with testable acceptance criteria kept development focused. Rather than attempting to build all features simultaneously, prioritizing core authentication and profile persistence first ensured our MVP remained stable and functional before moving on to advanced modules.

> **[📸 Insert Screenshot Here: Live Netlify Web App Interface - careercraft-sa.netlify.app]**  
> *Figure 2.1: The deployed CareerCraft landing page showing responsive design and navigation.*

---

## 3. 📊 Product Backlog (July – October 2026)

| Backlog ID | Feature / Epic Description | Priority | Current Status | Story Points | Target Milestone |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **PB-01** | Landing page responsive design & Netlify deployment[cite: 2] | High[cite: 2] | Completed[cite: 2] | 5[cite: 2] | July 2026[cite: 2] |
| **PB-02** | Investor-style pitch deck preparation & delivery[cite: 2] | High[cite: 2] | Completed[cite: 2] | 5[cite: 2] | Mid-July 2026[cite: 2] |
| **PB-03** | User Sign-Up & Login authentication flows (`/signup`, `/login`)[cite: 2] | High[cite: 2] | Completed[cite: 2] | 8[cite: 2] | Late-July 2026[cite: 2] |
| **PB-04** | Pricing page & membership tier comparison (`/pricing`)[cite: 2] | Medium[cite: 2] | Completed[cite: 2] | 3[cite: 2] | August 2026[cite: 2] |
| **PB-05** | User Profile data persistence & form state handling (`/profile`)[cite: 2] | High[cite: 2] | In Progress[cite: 2] | 8[cite: 2] | August-September 2026[cite: 2] |
| **PB-06** | MVP validation testing with real student cohorts[cite: 2] | Medium[cite: 2] | In Progress[cite: 2] | 8[cite: 2] | September 2026[cite: 2] |
| **PB-07** | Advanced CV template builder & export module[cite: 2] | High[cite: 2] | To Do[cite: 2] | 13[cite: 2] | October 2026[cite: 2] |
| **PB-08** | Institutional partner dashboard integration[cite: 2] | Low[cite: 2] | To Do[cite: 2] | 8[cite: 2] | Post-October 2026[cite: 2] |

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
| **T-201** | Refine `/profile` form input state handling and error alerts[cite: 2] | Frontend Team[cite: 2] | In Progress[cite: 2] | 3 pts[cite: 2] |
| **T-202** | Conduct session persistence tests across multiple browser instances[cite: 2] | QA / Testing[cite: 2] | To Do[cite: 2] | 2 pts[cite: 2] |
| **T-203** | Aggregate student feedback from September MVP testing sessions[cite: 2] | Community Liaison[cite: 2] | Completed[cite: 2] | 5 pts[cite: 2] |
| **T-204** | Audit Netlify deployment headers and security configurations[cite: 2] | DevOps[cite: 2] | Completed[cite: 2] | 1 pt[cite: 2] |
| **T-205** | Outline database schema requirements for the CV builder module[cite: 2] | Backend Dev[cite: 2] | To Do[cite: 2] | 5 pts[cite: 2] |

### 🔍 Critical Reflection on Sprint Backlog
Time-boxing our work into two-week iterations maintained continuous momentum. Breaking large epic features into manageable 1-to-5-point tasks ensured clear accountability and allowed us to track velocity accurately across busy university semesters.

> **[📸 Insert Screenshot Here: Active Sprint Board / Kanban Board]**  
> *Figure 4.1: Active sprint task board showing items in progress and completed.*

---

## 5. 📖 Agile Logbook (July – October 2026 Chronological Record)

### 🗓️ Phase 1: Pitch Week & Initial Deliverable Push (Mid-July 2026)
* **Date: 14 July 2026 (Tuesday)**
  * **Completed:** Facilitated sprint planning for pitch week; reviewed the 16-slide investor deck structure (problem, market, business model, financials) with Livhuwani; confirmed team speaking roles[cite: 2].
  * **Plan:** Draft speaker notes and talking points for personal presentation sections; finalize rehearsal schedules[cite: 2].
  * **Impediments & Resolution:** Initial lack of advanced design tools for a polished PowerPoint aesthetic; resolved by consulting a senior 4th-year IT student for slide design tips[cite: 2].

* **Date: 15 July 2026 (Wednesday)**
  * **Completed:** Successfully delivered the CareerCraft investor-style pitch to the assessment panel (presented by Lwandile at 14:30) with full team backing on timing cues and slide checks[cite: 2].
  * **Plan:** Analyze panel feedback to identify gaps in Deliverable 2; initiate secondary competitor validation research[cite: 2].
  * **Impediments & Resolution:** Home network instability during the online presentation session; mitigated by relocating to the campus IT lab for a reliable connection[cite: 2].

* **Date: 16 July 2026 (Thursday)**
  * **Completed:** Reviewed formal panel feedback; initiated deep-dive research into South African youth unemployment statistics and competing career-guidance platforms[cite: 2].
  * **Plan:** Verify market opportunity statistics; benchmark CareerCraft against existing solutions to strengthen the business plan revision[cite: 2].
  * **Impediments & Resolution:** Encountered paywalls and outdated datasets when searching for specific employment figures, requiring extra verification steps[cite: 2].

* **Date: 17 July 2026 (Friday)**
  * **Completed:** Consolidated weekly research findings into formal notes for the Deliverable 2 revision; hosted a team retrospective to analyze pitch strengths and areas for workflow refinement[cite: 2].
  * **Plan:** Update the product backlog with follow-up MVP validation testing items; await official grading feedback from the lecture panel[cite: 2].
  * **Impediments & Resolution:** None pending official assessment scores[cite: 2].

### 🗓️ Phase 2: MVP Validation & Feature Expansion (August – September 2026)
* **Sprint Review & Retrospective Highlights:**
  * Focused on connecting frontend views (`/pricing`, `/profile`) with backend user state persistence.
  * Partnered with student volunteers to conduct usability testing on portal navigation.
  * Addressed minor state-management issues in profile editing forms, significantly improving user data entry flow.

### 🗓️ Phase 3: Final Polish & Portfolio Consolidation (October 2026)
* **Status Review:**
  * Netlify deployment operating stably at `careercraft-sa.netlify.app`[cite: 2].
  * Core navigation, pricing comparisons, and authentication workflows fully operational.
  * Finalized documentation and structured markdown files for GitHub Pages submission to meet CPUT PRP370S requirements[cite: 3].

### 🔍 Overall Logbook Reflection
Maintaining this chronological logbook transformed daily challenges—such as connectivity glitches during online presentations or research paywalls—into valuable learning opportunities. Documenting our retrospectives ensured that our team continuously adapted its processes, resulting in a robust, production-ready portfolio.

> **[📸 Insert Screenshot Here: GitHub Pages Live Portfolio Rendering]**  
> *Figure 5.1: Final published GitHub Pages documentation site view.*

---
*© 2026 CareerCraft South Africa & Cape Peninsula University of Technology (CPUT). Professional Academic Portfolio.*
