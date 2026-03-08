
**Housing Quality & Safety Certification Program**  
 *A pilot initiative to standardize rental housing safety and transparency for students.*

## *User Stories and Prototyping*

##GitHub: http://github.com/simonaf19/IT-Management-Project/blob/main/docs/UserStoriesAndPrototyping.md

**March 2026**  
**Authors:** Anastasija Simunoska 89231023, Simona Filiposka 89231165, Zhasmin Sarvarova 89231228, Amir Garipov 89231145

# **Persona 1: Antonio Gonzalez (Tenant)**

### **User story 1**

As a tenant, I want to be able to verify that the housing listed is safe and look at recently made inspections and verifications issued, instead of finding out about its problems after signing the contract.

| Test Cases |
| :---- |
| **1\. View risk summary** Steps: Open property profile → click “Safety Overview.” Expected: System shows a summarized risk indicator (low/medium/high) based on inspection results and complaint history. |
| **2\. Property not found in registry** Steps: Search the building address not registered in the system Expected: System displays message “Property not yet verified” and suggests checking certification status or requesting inspection. |
| **3\. Look for reviews and complaints on the property** Steps: On the property record → open “Reviews and Complaints.” Expected: List of complaints and reviews with a timeline step showing when it was issued. |
| **4\. View risk summary** Steps: Open property profile → click “Safety Overview.” Expected: System shows a summarized risk indicator (low/medium/high) based on inspection results and complaint history. |
| **5\. Property not found in registry** Steps: Search the building address not registered in the system Expected: System displays message “Property not yet verified” and suggests checking certification status or requesting inspection. |

### **User story 2**

As a tenant, I want to leave reviews and comments on my experience with the housing to warn new potential tenants and get attention of officials to the problems.

| Test Cases |
| :---- |
| **1\. Edit submitted review** Steps: Open previously submitted review → click “Edit.” Expected: User can update description or rating while keeping the original timestamp history. |
| **2\. Report inappropriate review** Steps: Open review → click “Report.” Expected: System flags review for moderation and sends notification to administrators. |
| **3\. Sort reviews by timeline and relevancy** Steps: Open property profile → Click “Reviews and Complaints” → Click “Sort By” → Select “Relevance.” Expected: User will observe reviews sorted in terms of their current relevance, indicating whenever described pros and cons in the review are still present. |
| **4\. Edit submitted review** Steps: Open previously submitted review → click “Edit.” Expected: User can update description or rating while keeping the original timestamp history. |
| **5\. Report inappropriate review** Steps: Open review → click “Report.” Expected: System flags review for moderation and sends notification to administrators. |

### **User story 3**

As a tenant, I want to check the validity of a property's certification via a public registry and previous tenant reviews so that I can avoid signing a contract for an unverified or risky apartment.

| Test Cases |
| :---- |
| **1\. Check certification validity** Steps: Open property profile → Click “Certifications” → Click “View Certification Details.” Expected: System displays certification validity status (Valid/Expired/Pending Inspection) together with the certification date and expiration date. |
| **2\. Compare certification with complaints** Steps: Open property profile → Click “Certifications” → Click “Related Complaints.” Expected: System displays a list of complaints submitted after the most recent inspection, allowing the user to compare them with the certification results. |
| **3\. Contact officials to ask for clarification of information on housing** Steps: On a housing profile → open “Certifications” section → click on “Contact support” button Expected: Antonio writes a question to the official housing inspector and asks further questions about the inspection and certification results |
| **4\. Check certification validity** Steps: Open property profile → Click “Certifications” → Click “View Certification Details.” Expected: System displays certification validity status (Valid/Expired/Pending Inspection) together with the certification date and expiration date. |
| **5\. Compare certification with complaints** Steps: Open property profile → Click “Certifications” → Click “Related Complaints.” Expected: System displays a list of complaints submitted after the most recent inspection, allowing the user to compare them with the certification results. |

# **Persona 2: Matjaž Horvat (Independent Landlord)**

### **User story 1**

As an independent landlord, I want to obtain an official housing quality and safety certification for my apartment so that I can objectively prove its condition and increase tenant trust before signing a contract.

| Test Cases |
| :---- |
| **1\.  Apply for certification** Steps: Log into landlord account → Select property → Click “Apply for Certification” → Upload required documents → Submit request Expected: System confirms submission, displays application status as “Pending Inspection”, and sends confirmation notification. |
| **2\. Schedule and complete inspection** Steps: Open certification request → Select available inspection date → Confirm appointment Expected: Inspection date is scheduled and visible in the dashboard. After inspection, the system updates its status to “Inspection Completed” and displays the results. |
| **3\. Receive certification and display badge** Steps: After successful inspection → Open property profile → View certification status Expected: System displays “Certified” status, shows certification validity period, inspection summary, and automatically adds certification badge to public property listing. |

### **User story 2**

As an independent landlord, I want to have documented inspection records available in case of disputes or negative reviews so that I can protect my reputation with verifiable evidence.

| Test Cases |
| :---- |
| **1\. View inspection history** Steps: Open landlord dashboard → Select property → Open “Inspection Records.” Expected: System displays a timeline of all inspections, including dates, inspectors, results, and identified issues. |
| **2\. Reference the inspection record in dispute** Steps: Open negative review → Click “Reference inspection record” → Select inspection Expected: Inspection summary appears attached to the response, showing verified inspection results. |
| **3\. Download official documentation** Steps: Open property profile → Open “Inspection Records” → Click “Download Report.” Expected: System downloads a PDF report containing inspection results, certification status, and inspector comments.  |

### 

### **User story 3**

As an independent landlord, I want a standardized move-in condition report that both the tenant and I can confirm before signing the contract so that we clearly agree on the apartment’s condition and responsibilities.

| Test Cases |
| :---- |
| **1\.  Generate move-in report** Steps: Open landlord dashboard → Select property → Click “Generate Move-In Report.” Expected: System creates a standardized checklist including apartment condition, appliances, and potential damages. |
| **2\.  Tenant confirmation** Steps: Send report to tenant → Tenant opens report → Click “Confirm condition.” Expected: System records tenant confirmation and timestamps the agreement. |
| **3\. Attach photos to the report** Steps: Open move-in report → Upload photos of apartment condition Expected: Photos are stored in the report and visible to both landlord and tenant.  |
| **4\. Export signed report** Steps: Open finalized report → Click “Export.”  Expected: System generates a signed PDF copy accessible to both parties.  |

# **Persona 3: Nina Kovač (Municipal Housing Officer)**

### **User story 1**

As a municipal housing officer, I want to see a centralized view of properties with recurring issues and inspection history, so I can monitor risk patterns proactively instead of reacting to complaints.

| Test Cases |
| :---- |
| **1\. Search by building and view history** Steps: Enter building address → open “History.” Expected: Shows past inspections, outcomes, issues, and certification changes over time. |
| **2\. Flag recurring issues** Steps: Property has the same issue (e.g., humidity) across ≥2 inspections Expected: System highlights “Recurring issue” badge and counts occurrences. |
| **3\. Complaint-to-property linking** Steps: Open a complaint → link to property record Expected: Complaint attaches to the correct property; appears in timeline. |
| **4\. Risk dashboard filters** Steps: Filter dashboard by “High severity”, “Expired certifications”, “Multiple complaints.” Expected: Result list updates correctly; counts match the filtered dataset. |
| **5\. No centralized data case** Steps: Search for a non-registered property Expected: Shows “Not registered” and prompts: “Recommend certification/schedule inspection”. |
| **6\. Role-based access** Steps: Nina views administrative details Expected: She sees additional fields (internal notes, enforcement status) not visible to the public. |

### 

### 

### **User story 2**

As a municipal housing officer, I want to generate a housing quality trends report with measurable indicators, so I can provide evidence-based updates to my supervisor.

| Test Cases |
| :---- |
| **1\. Report by date range:** Steps: Select the last 12 months → generate report Expected: Includes totals: \#inspections, \#certified, \#expired, \#failed, common issue categories. |
| **2\. Trend chart data consistency:** Steps: Generate a monthly trend for “humidity-related findings.” Expected: Values equal the underlying inspection records for each month. |
| **3\. Export formats** Steps: Export report as PDF and CSV Expected: Both exports succeed; CSV contains raw numbers; PDF contains charts \+ summary text.  |
| **4\. Comparability across properties** Steps: Run “compare neighborhoods” or areas Expected: Metrics normalized (e.g., per 100 properties) or clearly labeled as raw counts. |
| **5\. Missing data handling** Steps: Include properties with incomplete inspection fields Expected: Report labels them as “Unknown/Incomplete” and does not crash. |
| **6\. Supervisor-ready summary** Steps: Open the generated report cover page Expected: Contains 3–5 key findings (e.g., top recurring risks, compliance rate, areas with most expirations). |

### 

### 

### **User story 3**

As a municipal housing officer, I want to get alerts for high-risk situations (e.g., repeated complaints, expired certification, failed inspection), so I can prioritize actions and reduce administrative workload.

| Test Cases |
| :---- |
| **1\. Alert on expired certification** Steps: Certification passes expiry date Expected: Alert created with property ID, expiry date, and recommended next step (re-inspection). |
| **2\. Alert on failed inspection** Steps: Inspector marks “Fail.” Expected: Nina receives an alert immediately; the property is marked “Not compliant” internally. |
| **3\. Alert threshold for repeated complaints** Steps: Log 3 complaints in 30 days for the same property Expected: “High complaint volume” alert triggers with complaint list attached. |
| **4\. Alert deduplication** Steps: Same condition persists across days Expected: System does not spam duplicates; updates existing alert with new events.  |
| **5\.  Priority ranking** Steps: View the alert dashboard Expected: Alerts sorted by severity/urgency (Fail \> Expired \> repeated complaints). |
| **6\. Close/resolve alert workflow** Steps: Nina marks alert “Resolved” after inspection/fix verified Expected: Alert status changes; resolution note required; audit trail saved. |


