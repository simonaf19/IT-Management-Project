**Housing Quality & Safety Certification Program**  
 *A pilot initiative to standardize rental housing safety and transparency for students.*

## *Scrum Basics*

**March 2026**  
**Authors:** Anastasija Simunoska 89231023, Simona Filiposka 89231165, Zhasmin Sarvarova 89231228, Amir Garipov 89231145

## **1\. Sprint 0 – Planned Implementation**

### **1.1 Project Overview**

The purpose of this project is to improve the usability of the Housing Quality & Safety Certification Platform. Previous usability testing showed that users struggled to understand certification and inspection data and preferred simple, clear indicators over complex technical information.

Therefore, the solution focuses on simplifying safety-related information and presenting it in a more intuitive and user-friendly way for different user groups, such as parents, students, and young professionals.

### **1.2 Objectives**

The main objectives of the implementation are:

* Simplify certification and inspection data  
* Introduce clear safety indicators (e.g., color-coded badges)  
* Clearly distinguish between reviews and complaints  
* Provide a summarized overview of risks  
* Improve overall usability and user experience

### **1.3 Tools and Technologies** 

The following tools will be used to support project development:

#### **Project Management Tools**

* Trello – task organization and sprint tracking  
* Jira – backlog and issue management  
* OpenProject – scheduling and collaboration

#### **Documentation Tool**

* Obsidian – project documentation and notes

#### **Design Tool**

* Figma (or similar) – for UI design and prototyping

### **1.4 Product Backlog (Prioritized)**

The initial backlog is based on usability testing insights:

**High Priority:**

1. Design a safety indicator system  
2. Simplify certification display  
3. Improve inspection data readability

**Medium Priority:**  
 4\. Separate reviews and complaints  
 5\. Add risk summary section

**Low Priority:**  
 6\. General UI improvements
 
# **Sprints and To-dos** 

### **Sprint 0: Planning & Infrastructure**

*Focus: Setting the technical and visual foundation for the team.*

| Task ID | Task & Elaboration | Subtasks | Complexity |
| :---- | :---- | :---- | :---- |
| **0.1** | **Environment Setup:** Configure the workspace for Anastasija, Simona, Zhasmin, and Amir. | • Create **Jira** project & workflow. • Create a shared notebook in Notion for shared documentation. • Set up **Trello** for high-level visual progress tracking. | 1 SP |
| **0.2** | **Design System (Figma):** Establish the "Safety Visual Language" to replace technical jargon. | • Define color palette for application. • Create a library of reusable "Safety Icons." • Draft mobile-first typography for readability. | 3 SP |
| **0.3** | **Persona Requirements:** Define what "Safety" means to each user segment. | • List "Parent" priorities (e.g., Fire/Electrical). • List "Student" priorities (e.g., Security/Reviews). • Map data points to specific user needs. | 2 SP |

### **Sprint 1: Core Safety Visualization**

*Focus: High-priority simplification of complex inspection data.*

| Task ID | Task & Elaboration | Subtasks | Complexity |
| :---- | :---- | :---- | :---- |
| **1.1** | **Safety Indicator System:** The logic behind the color-coded certification badges. | • Define scoring for Gold/Silver/Bronze safety tiers. • Design "Info Tooltips" to explain badge meaning. • Build the logic for automated badge assignment. | 5 SP |
| **1.2** | **Certification Simplification:** Transforming dense text into a visual dashboard. | • Replace legal jargon with "Pass/Fail" indicators. • Add a "Last Verified" date stamp for clarity. | 3 SP |
| **1.3** | **Inspection Readability:** Making raw data scannable at a glance. | • Create a "Top 3 Takeaways" section per report. • Design a checklist UI for pending inspections. • Build a "Property Comparison" safety view. | 3 SP |

### **Sprint 2: Risk & Feedback Management**

*Focus: Medium-priority categorization and "Red Flag" identification.*

| Task ID | Task & Elaboration | Subtasks | Complexity |
| :---- | :---- | :---- | :---- |
| **2.1** | **Feedback Categorization:** Separating lifestyle reviews from safety complaints. | • Implement a "Safety vs. Lifestyle" tab system. • Design a "Report Urgent Concern" button. • Create a "Landlord Resolution" status tag. | 3 SP |
| **2.2** | **Risk Summary Section:** A high-level overview of potential property hazards. | • Categorize "Critical Failures" (e.g., Mold/Locks). • Design a "Warning Box" for failed safety metrics. • Implement a "Risk Level Meter" on property cards. | 5 SP |
| **2.3** | **Data Mapping:** Connecting back-end inspection points to the UI summary. | • Link specific raw data to the Risk Summary UI. • Ensure data refreshes when new reports are uploaded. | 3 SP |

### **Sprint 3: Polishing & Finalization**

*Focus: Low-priority refinements and project hand-off.*

| Task ID | Task & Elaboration | Subtasks | Complexity |
| :---- | :---- | :---- | :---- |
| **3.1** | **General UI Improvements:** Fine-tuning the interface based on pilot feedback. | • Optimize mobile responsiveness for students. • Improve loading states for data-heavy tables. • Conduct a final "UX Walk-through" for flow. | 3 SP |
| **3.2** | **Project Documentation:** Finalizing the records for the March 2026 deadline. | • Finalize "Scrum Basics" report in Notion. • Clean up Figma files for developer hand-off. • Archive completed Jira tasks and Sprint logs. | 1 SP |

 # **Sprint Implementation (Current Progress)**

At this stage, the team has implemented a **high-fidelity interactive prototype in Figma**, which represents the core functionality and user experience of the platform.

https://bunch-above-23171971.figma.site/

The prototype focuses on solving the main usability issues identified during testing: **complex safety data, lack of clarity, and low trust in housing information**.

## **Implemented Features (Based on Prototype)**

### **1\. Dashboard – Simplified Safety Overview**

The main dashboard provides users with an immediate understanding of the system status through visual cards:

* Certified Properties (Green) → clearly indicates safe housing  
* In Review (Orange) → shows pending approvals  
* Active Complaints (Red) → highlights risks  
* Scheduled Inspections (Blue) → upcoming actions

### **2\. Property Inspection View (Safety Breakdown)**

Each property includes a structured inspection panel:

* Categories:  
  * Mold Assessment  
  * Ventilation  
  * Electrical  
  * Structural  
* Each category shows:  
  * Pass / Fail status (visual badges)  
* Additional elements:  
  * Humidity level (with thresholds: optimal / warning / critical)  
  * Inspector notes (human-readable summary)

### **3\. Complaints System (Separate & Structured)**

A dedicated page for managing housing complaints has been designed.

**Filters include:**

* Status (Open / Investigating / Resolved / Closed)  
* Category

**Each complaint includes:**

* Description of the issue  
* Date of submission  
* Category (e.g., mold)  
* Status and priority level

### **4\. Clear Navigation Structure**

The platform uses a simple and intuitive top navigation menu:

* Dashboard  
* Properties  
* Inspections  
* Complaints  
* Reports  
* Register Property
