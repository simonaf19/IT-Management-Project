
**Housing Quality & Safety Certification Program**  
 *A pilot initiative to standardize rental housing safety and transparency for students.*

## *User Stories and Prototyping*

**March 2026**  
**Authors:** Anastasija Simunoska 89231023, Simona Filiposka 89231165, Zhasmin Sarvarova 89231228, Amir Garipov 89231145

# **Persona 1: Antonio Gonzalez (Tenant)**

### **User story 1**

| Test Cases |
| :---- |
| **4\. View risk summary** Steps: Open property profile → click “Safety Overview.” Expected: System shows a summarized risk indicator (low/medium/high) based on inspection results and complaint history. |
| **5\. Property not found in registry** Steps: Search the building address not registered in the system Expected: System displays message “Property not yet verified” and suggests checking certification status or requesting inspection. |

### **User story 2**

| Test Cases |
| :---- |
| **4\. Edit submitted review** Steps: Open previously submitted review → click “Edit.” Expected: User can update description or rating while keeping the original timestamp history. |
| **5\. Report inappropriate review** Steps: Open review → click “Report.” Expected: System flags review for moderation and sends notification to administrators. |

### **User story 3**
| Test Cases |
| :---- |
| **4\. Check certification validity** Steps: Open property profile → Click “Certifications” → Click “View Certification Details.” Expected: System displays certification validity status (Valid/Expired/Pending Inspection) together with the certification date and expiration date. |
| **5\. Compare certification with complaints** Steps: Open property profile → Click “Certifications” → Click “Related Complaints.” Expected: System displays a list of complaints submitted after the most recent inspection, allowing the user to compare them with the certification results. |

# **Persona 2: Matjaž Horvat (Independent Landlord)**


### **User story 2**

| Test Cases |
| :---- |
| **1\. View inspection history** Steps: Open landlord dashboard → Select property → Open “Inspection Records.” Expected: System displays a timeline of all inspections, including dates, inspectors, results, and identified issues. |
| **2\. Reference the inspection record in dispute** Steps: Open negative review → Click “Reference inspection record” → Select inspection Expected: Inspection summary appears attached to the response, showing verified inspection results. |
| **3\. Download official documentation** Steps: Open property profile → Open “Inspection Records” → Click “Download Report.” Expected: System downloads a PDF report containing inspection results, certification status, and inspector comments.  |

### 

### **User story 3**

| Test Cases |
| :---- |
| **1\.  Generate move-in report** Steps: Open landlord dashboard → Select property → Click “Generate Move-In Report.” Expected: System creates a standardized checklist including apartment condition, appliances, and potential damages. |
| **2\.  Tenant confirmation** Steps: Send report to tenant → Tenant opens report → Click “Confirm condition.” Expected: System records tenant confirmation and timestamps the agreement. |
| **3\. Attach photos to the report** Steps: Open move-in report → Upload photos of apartment condition Expected: Photos are stored in the report and visible to both landlord and tenant.  |
| **4\. Export signed report** Steps: Open finalized report → Click “Export.”  Expected: System generates a signed PDF copy accessible to both parties.  |

# **Persona 3: Nina Kovač (Municipal Housing Officer)**

