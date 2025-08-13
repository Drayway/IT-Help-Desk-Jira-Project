# IT Help Desk Ticketing System Project using Jira

### Created by Drayton Rolle

---

## 📝 Project Summary

This project is a hands-on simulation of a corporate IT Help Desk environment built using Jira Service Management. The goal was to gain practical experience in modern IT Service Management (ITSM) by managing the complete lifecycle of common support tickets.

This project demonstrates the ability to effectively use an enterprise-grade ticketing system to track, prioritize, and resolve user-submitted issues, a core requirement for any IT support role. It showcases skills in ticket documentation, workflow management, and building a user-facing knowledge base.

---

## 🚀 Key Skills & Concepts Demonstrated

* **IT Service Management (ITSM):** Utilized a pre-configured ITSM framework to handle service requests and incidents.
* **Ticketing System Management:** Managed the full lifecycle of support tickets, from creation and triage to status changes (Pending, In Progress, Resolved) and closure.
* **Troubleshooting & Documentation:** Documented all troubleshooting steps, user communications, and resolutions within each ticket's activity log.
* **Workflow Management:** Worked with different ticket types (Service Request, Incident) and their corresponding workflows and statuses.
* **Knowledge Base Creation:** Authored and published a knowledge base article to enable user self-service and deflect future tickets.
* **Customer Service:** Practiced writing clear and professional communications to end-users within the ticketing system.

---

## 🛠️ Tools Used

* **Jira Service Management (Cloud):** The platform used to create and manage the entire help desk project.
* **Confluence:** The integrated knowledge base tool used to create help articles.

---

## 📖 Step-by-Step Project Guide

This guide provides a detailed walkthrough for replicating this project.

### Phase 0: Setting Up the Service Desk

1.  **Sign Up for Jira:** Go to the [Jira Service Management Free Plan](https://www.atlassian.com/software/jira/service-management/free) and sign up for an account.
2.  **Create a Site:** Follow the prompts to create a unique site URL (e.g., `yourname-helpdesk.atlassian.net`).
3.  **Create a Project:** When prompted, select the **"IT Service Management"** template and name your project (e.g., `Corporate IT Help Desk`).

### Phase 1: Simulating Help Desk Tickets

For each scenario, first act as the **user** and raise a request through the customer portal. Then, act as the **agent** to process and resolve the ticket in the Jira queues.

1.  **Ticket 1: The Password Reset**
    * **User Action:** From the portal, raise a "Help with my account" request for "John Smith" who is locked out of his laptop.
    * **Agent Action:** Open the ticket. Add an internal note: `Verified user's identity via phone.` Add a public comment: `Hi John, I have sent a password reset link to your recovery email.` Change the status to **Resolved**.

2.  **Ticket 2: The Software Request**
    * **User Action:** From the portal, raise a "Request a new application" for "Jane Doe" who needs Adobe Photoshop.
    * **Agent Action:** Open the ticket. Add an internal note: `Need to get manager approval.` Change the status to **Pending**. Add a second note: `Approval received. Software deployed.` Change the status to **Resolved**.

3.  **Ticket 3: The Hardware Incident**
    * **User Action:** From the portal, "Report broken hardware" for a laptop that is slow and making noise.
    * **Agent Action:** Open the ticket. Add an internal note: `Scheduled pickup for diagnostics and provided a loaner laptop.` Change the status to **Work in Progress**. Add a final note: `Replaced failing hard drive and re-imaged machine. User confirms issue is resolved.` Change the status to **Resolved**.

4.  **Ticket 4: The Network Issue**
    * **User Action:** From the portal, "Get IT help" for a user who cannot connect to the office Wi-Fi.
    * **Agent Action:** Open the ticket. Add a public comment with troubleshooting steps: `Hi, could you please try 'forgetting' the Wi-Fi network and reconnecting?` Change the status to **Waiting for customer**. Add a final note: `User confirmed reconnecting solved the issue.` Change the status to **Resolved**.

5.  **Ticket 5: The "How Do I?" Question**
    * **User Action:** From the portal, raise a general request asking how to set up email on a mobile phone.
    * **Agent Action:** Resolve this ticket by creating and linking a Knowledge Base article (see Phase 2).

### Phase 2: Building the Knowledge Base

1.  **Navigate:** In the left-hand project menu, click on **Knowledge base**.
2.  **Create Article:** Click **Create article**.
3.  **Write Content:**
    * **Title:** `How to Set Up Company Email on a Mobile Phone`
    * **Content:** Write clear, step-by-step instructions.
4.  **Publish:** Publish the article. You can now link this article in tickets to provide instant answers to common questions.

---

## 📸 Portfolio Screenshots

*(Screenshots of the Jira project demonstrating the completed work)*

**1. The Ticket Queue**
*A screenshot of the main "All open" queue showing various tickets with different statuses.*
`![Ticket Queue](images/your-queue-screenshot.png)`

**2. Example of a Resolved Ticket (Hardware Incident)**
*A screenshot showing the full activity log of the hardware ticket, including internal notes, status changes, and final resolution.*
`![Resolved Hardware Ticket](images/resolved-hardware-ticket.png)`

**3. The Knowledge Base Article**
*A screenshot of the published knowledge base article for setting up mobile email.*
`![Knowledge Base Article](images/knowledge-base-article.png)`
