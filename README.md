# Smart Lead Management System (Salesforce Project)

## Project Overview
The **Smart Lead Management System** is a Salesforce-based solution that automates the process of capturing, managing, scoring, and analyzing leads for better decision-making.  
It integrates a **Web-to-Lead form**, intelligent **email alerts**, and **visual dashboards**, providing sales teams with real-time insights and improved customer engagement.

---

## Objectives
- Automate the lead collection process through a web interface.  
- Categorize and score leads dynamically for prioritization.  
- Provide instant alerts for “Hot Leads”.  
- Enable managers to visualize key performance data using reports and dashboards.  
- Streamline workflows through queues, assignments, and automation.

---

## Technologies Used
- **Salesforce Lightning Experience**
- **Salesforce Flow Builder**
- **Web-to-Lead Integration**
- **Email Alerts & Templates**
- **Reports & Dashboards**
- **HTML, CSS (for external form)**
- **GitHub Pages (for live form hosting)**

---

## Project Implementation Phases

### **Phase 1: Problem Understanding & Industry Analysis**
- Studied challenges faced in manual lead tracking and follow-ups.  
- Researched existing CRM tools (e.g., Zoho, HubSpot, Salesforce).  
- Identified Salesforce as the ideal solution for automation and scalability.  
- **Deliverable:** A comparative study of 3 CRM systems and identified problem scope.

---

### **Phase 2: System Design & Requirement Analysis**
- Defined required Salesforce objects (Lead, Account, Contact).  
- Outlined automation rules for lead scoring and assignment.  
- Designed the data flow from Web Form → Salesforce → Dashboard.  
- **Deliverable:** Use Case Diagram & Requirement Specification Document.

---

### **Phase 3: Lead Management Setup**
- Created custom fields such as:
  - **Lead Score**
  - **Product Interest**
  - **Lead Source**
- Modified picklist values under *Lead Status* (`Hot`, `Cold`, `Working – Contacted`).
- **Deliverable:** Configured Lead Object and validated data input fields.

---

### **Phase 4: Automation & Flow Configuration**
- Designed a **Flow** to:
  - Assign leads automatically to “Lead Queue”.
  - Trigger Email Alerts for “Hot Leads”.
- **Deliverable:** Working Flow and Queue Assignment Automation.

---

### **Phase 5: Email Templates & Notifications**
- Created **Classic Email Template** for hot lead alerts.  
- Configured **Email Alert** action inside Flow to notify sales managers.  
- **Deliverable:** Automated Email Notification System.

---

### **Phase 6: Report Creation**
- Developed reports such as:
  - *New Leads Report*
  - *Leads by Source*
  - *Leads by Lead Score*
- **Deliverable:** Filtered and grouped reports showing lead trends.

---

### **Phase 7: Dashboard Integration**
- Created **Smart Lead Management Dashboard** using:
  - Funnel Chart for *Hot vs Cold Leads*
  - Donut Chart for *Leads by Score*
- Added widgets and configured component visibility.  
- **Deliverable:** Interactive Dashboard for visual analytics.

---

### **Phase 8: Integration & External Access**
- Implemented **Web-to-Lead** form integration using HTML.  
- Connected form submission to Salesforce via org ID and API fields.  
- Deployed on GitHub Pages for public access.  
- **Deliverable:** Live Web Form linked with Salesforce CRM.

---

### **Phase 9: Testing & Validation**
- Tested:
  - Lead creation from web form.
  - Automated email notifications.
  - Dashboard data accuracy.
- Validated form data consistency and field mapping in Salesforce.  
- **Deliverable:** Final Tested Workflow with successful lead tracking.

---

### **Phase 10: Documentation & Deployment**
- Prepared detailed project documentation including:
  - Abstract
  - System Design
  - Workflow Diagrams
  - Test Cases
  - Conclusion & Quality Assurance
- Uploaded final version to **GitHub** with live demo link.  
- **Deliverable:** Final documentation and project repository.

---

## 🌐 Live Demo
🔗 [Click here to open the live Smart Lead Form](https://vinaysingu88.github.io/Smart-Lead-Management-System-using-Salesforce/)

---

## 📄 Documentation
The full project report is available in:
