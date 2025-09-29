# Streamlining-Ticket-Assignment-for-Efficient-Support-Operations
A streamlined ticket management system designed to enhance support operations by improving issue tracking, prioritization, and resolution efficiency.This project delivers an **automated ticket assignment solution** built on the **ServiceNow platform** to streamline IT support operations. By configuring users, groups, roles, ACLs, and automation flows, the system intelligently routes tickets to the correct support teams. The result is **faster resolution times, improved team efficiency, and enhanced customer satisfaction**.

## 🎯 Objective

To design and implement a **smart ticket routing mechanism** that eliminates manual assignment, reduces delays, and enforces secure, role-based access in IT support workflows.

## 🧑‍💻 Skills Applied

* User & Group Management
* Role Management & Permissions
* Custom Table Design
* Access Control Lists (ACLs)
* Flow Designer for Automation

## ⚙️ Modules Implemented

### 1. User & Group Management

* Created users to represent IT support members.
* User1: Manne Niranjan
* user2: Katherine pierce
* Formed groups (*Certificate Group* & *Platform Group*) for task categorization.
* Mapped users to relevant groups for structured collaboration.

### 2. Role Creation & Assignment

* Designed custom roles for controlled access.
* Role1: Certification_role
* Role2: Platform_role
* Assigned roles to:

  * Users
  * Groups
  * Operations Related Table
* Ensured each team could only access relevant tickets.

### 3. Custom Table Creation

* Built a dedicated **Operations Related Table** to store ticket details (ID, description, category, priority, assigned group).
* Applied ACLs for role-based restrictions:
  * u_operations_related.u_priority
  * u_operations_related.u_ticket_raised_date
  * u_operations_related.u_name
  * u_operations_related.u_issue
  * u_operations_related.u_service_request_no  

### 4. Assigning Roles to Users & Groups

* Linked roles to individuals and groups for clear access control.
* Certificate Group → certificate-related tickets
* Platform Group → platform-related tickets
* Extended role permissions to the ticket table.

### 5. Access Control Lists (ACLs)

* Enforced table- and field-level security.
* Restricted sensitive fields to admin-level users only.
* Controlled **read, write, create, delete** permissions.

### 6. Flow Designer – Automated Assignment

* Developed automation flows for seamless routing:

  * **Flow 1:** Assigns Certificate Issue tickets → Certificate Group
  * **Flow 2:** Assigns Platform Issue tickets → Platform Group
* Triggered automatically on new ticket creation, reducing manual effort and errors.

## 📊 Outcomes

* ✅ Eliminated manual ticket assignment
* ✅ Faster routing → quicker resolution times
* ✅ Improved team productivity & customer satisfaction
* ✅ Stronger security with role-based ACLs
* ✅ Hands-on experience in ServiceNow ITSM automation

## 🏁 Conclusion

The project highlights how **ServiceNow’s low-code capabilities** can **automate IT support workflows**, improve operational efficiency, and enforce structured access. By leveraging automation, IT teams can focus on resolving issues instead of managing assignments, resulting in a more streamlined and effective support process.


