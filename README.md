# osTicket Ticket Lifecycle Examples

![osTicket Ticket Lifecycle Examples](images/ticket-lifecycle-header.png)

## Project Summary

This project demonstrates ticket lifecycle examples within the osTicket help desk system. After completing the osTicket installation and post-installation configuration labs, I created support tickets as end users, reviewed and updated ticket properties as help desk agents, assigned tickets to the correct departments, applied SLA plans, and worked tickets through completion.

The purpose of this project was to gain hands-on experience with ticket intake, ticket triage, priority assignment, department routing, SLA management, agent permissions, and ticket resolution workflows in a help desk environment.

## Related osTicket Projects

- [osTicket: Prerequisites and Installation](https://github.com/CameronJohnson-IT/osticket-prereqs)
- [osTicket: Post-Installation Configuration](https://github.com/CameronJohnson-IT/post-install-config)
- [osTicket: Ticket Lifecycle Examples](https://github.com/CameronJohnson-IT/ticket-lifecycle)

## Technologies Used

- osTicket
- Microsoft Azure
- Azure Virtual Machines
- Remote Desktop Protocol
- Internet Information Services (IIS)
- PHP
- MySQL
- Web-based ticketing system

## Languages / Components Used

- PHP
- SQL / MySQL
- osTicket web application
- IIS web server components
- Web-based admin and agent interfaces

## Environments Used

- Microsoft Azure
- Windows 10 Virtual Machine
- osTicket Admin Panel
- osTicket Agent Panel
- osTicket End-User Portal

## Project Objectives

- Create support tickets as end users
- Observe ticket properties as help desk agents
- Configure ticket priority, department, SLA, and assignment
- Route tickets to the correct departments
- Work tickets through completion
- Understand ticket visibility and access permissions
- Practice real-world help desk ticket handling
- Explain how ticket intake works in a technical support environment

## Implementation Steps

### Step 1: Access the osTicket Admin/Agent Panel

Logged into the osTicket Admin/Agent panel using the agent accounts created during the post-installation configuration lab.

![Admin agent login](images/step-1-admin-agent-login.png)

### Step 2: Access the osTicket End-User Portal

Accessed the osTicket end-user portal to create support tickets from the customer side of the help desk system.

![End user portal](images/step-2-end-user-portal.png)

### Step 3: Prepare Departments for Ticket Routing

Updated the department structure before working ticket examples. The `SysAdmins` department was changed to a top-level department, and the `Maintenance` department was deleted instead of archived.

![Department configuration](images/step-3-department-configuration.png)

### Step 4: Create Ticket 1 - Mobile Banking System Down

Created a ticket as an end user with the issue:

```text
entire mobile/online banking system is down
```

This ticket represents a high-impact service outage that would require urgent attention.

![Create ticket mobile banking](images/step-4-create-ticket-mobile-banking.png)

### Step 5: Observe Ticket 1 as John

Logged in as the help desk agent `John` and observed the ticket properties, including priority, department, SLA, and assignment.

![Observe ticket as John](images/step-5-observe-ticket-john.png)

### Step 6: Set Ticket 1 Properties

Updated the ticket properties for the mobile banking outage.

Configured properties:

- Priority: Emergency
- SLA: Sev-A, 1 hour, 24/7
- Department: Support / SysAdmins
- Help Topic: Business Critical Outage
- Assigned To: `Jane Doe`

![Set ticket 1 properties](images/step-6-set-ticket-1-properties.png)

### Step 7: Test Ticket 1 Visibility

Attempted to observe the ticket again as `John` after it was assigned to the Support / SysAdmins department. This demonstrated how department routing and permissions can affect ticket visibility.

![Ticket visibility test](images/step-7-ticket-visibility-test.png)

### Step 8: Work Ticket 1 to Completion as Jane

Logged in as `Jane` and worked the mobile banking outage ticket through completion.

![Complete ticket 1 as Jane](images/step-8-complete-ticket-1-jane.png)

### Step 9: Create Ticket 2 - Adobe Upgrade Issue

Created a second ticket as an end user with the issue:

```text
accounting department needs adobe upgrade, broken
```

This ticket represents a software/application support issue affecting a business department.

![Create ticket adobe issue](images/step-9-create-ticket-adobe-issue.png)

### Step 10: Observe Ticket 2 as John

Logged in as `John` and observed the ticket properties for the Adobe upgrade issue, including priority, department, SLA, and assignment.

![Observe ticket 2 as John](images/step-10-observe-ticket-2-john.png)

### Step 11: Set Ticket 2 Properties

Updated the ticket properties for the Adobe upgrade issue.

Configured properties:

- Priority: High
- SLA: Sev-B, 4 hours, 24/7
- Department: Support
- Help Topic: Personal Computer Issues
- Assigned To: `John Doe`

![Set ticket 2 properties](images/step-11-set-ticket-2-properties.png)

### Step 12: Work Ticket 2 to Completion as John

Worked the Adobe upgrade ticket through completion as `John`.

![Complete ticket 2 as John](images/step-12-complete-ticket-2-john.png)

### Step 13: Create Ticket 3 - Marketing Laptop Display Issue

Created a third ticket as an end user with the issue:

```text
Sarah's comptuer keeps freezing and flickering
```

This ticket represents a hardware or endpoint support issue affecting a business user.

![Create ticket - Laptop Display Issue](images/step-13-create-ticket-cfo-laptop.png)

### Step 14: Observe Ticket 3 as John

Logged in as `John` and observed the ticket properties for the CFO laptop issue, including priority, department, SLA, and assignment.

![Observe ticket 3 as John](images/step-14-observe-ticket-3-john.png)

### Step 15: Set Ticket 3 Properties

Updated the ticket properties for the CFO laptop issue.

Configured properties:

- Priority: High
- SLA: Sev-B, 4 hours, 24/7
- Department: Support
- Help Topic: Personal Computer Issues
- Assigned To: `John Doe`

![Set ticket 3 properties](images/step-15-set-ticket-3-properties.png)

### Step 16: Work Ticket 3 to Completion as John

Worked the CFO laptop ticket through completion as `John`.

![Complete ticket 3 as John](images/step-16-complete-ticket-3-john.png)


## Demonstration

This project demonstrates how tickets move through a help desk system from creation to resolution. Tickets were created through the end-user portal, reviewed from the agent side, assigned ticket properties, routed to the correct departments, and worked through completion.

The lab also demonstrated how departments, agent permissions, SLA plans, and ticket assignments affect visibility and responsibility inside osTicket.

![Ticket lifecycle demonstration](images/demonstration-ticket-lifecycle.png)

## Ticket Intake Explanation

In real help desk environments, tickets can be created through several intake channels, including email, phone, chat, web forms, or direct interaction with a user. Even when an issue is fixed immediately, creating a ticket is still important because it documents the work performed, tracks recurring problems, helps measure support workload, and creates a record for future troubleshooting.

Ticketing systems help support teams organize requests, prioritize urgent issues, assign work to the right people, and maintain accountability throughout the support process.

## Skills Demonstrated

- Help desk ticket intake
- Ticket triage and prioritization
- SLA assignment
- Department routing
- Agent ticket management
- Ticket visibility and permission testing
- End-user support workflow
- Ticket resolution documentation
- Help desk operations
- Technical documentation

## Key Takeaways

This project helped me understand the full lifecycle of a support ticket, from user submission to agent review, triage, routing, escalation, and resolution. I learned how ticket properties such as priority, department, SLA, and assignment affect how work is handled inside a help desk system.

It also reinforced the importance of documenting support work in a ticketing system, even when an issue is resolved quickly. Tickets provide visibility, accountability, metrics, and a reliable history of technical support activity.
