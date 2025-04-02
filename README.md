<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle</h1>
This tutorial outlines the life cycle of the open-source help desk ticketing system osTicket.<br />


<h2>osTicket Website</h2>

- ### [osTicket Installation Files](https://docs.osticket.com/en/latest/Getting%20Started/Installation.html)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket 

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Creating tickets as end-users
- Observing ticket properties as help desk professionals
- Managing department structures
- Working tickets to completion


<h2>Basic Steps</h2>


![Screenshot 2025-04-02 003557](https://github.com/user-attachments/assets/8dd1c6a9-4ec7-4ea5-9cf3-b3e2007c6b5e)

<p>
Create ticket with description: "entire mobile/online banking system is down"
</p>
<br />


![Screenshot 2025-04-02 004336](https://github.com/user-attachments/assets/a4a10dad-0123-4129-be92-da24519f1645)

<p>
As a help desk agent let's observe ticket properties like Priority, Deparments, SLA, and Assigned to. We will set this ticket's properties to Sev-A (1-hour, 24/7) and set Department to Online Banking. We will attempt to observe ticket as agent John & Marc.
<br />


![Screenshot 2025-04-02 010729](https://github.com/user-attachments/assets/7cbdb7b4-2fea-41f6-80eb-b4d7019757b9)

<p>
Set initial properties: (a) banking system to Sev-A (1 hour, 24/7), Online Banking Department; (b) adobe upgrade to Sev-B (4 hours, 24/7), Support; (c) CFO laptop to Sev-B (4 hours, 24/7), Support. Will show Sev-A as example.
</p>
<br />


![Screenshot 2025-04-02 010804](https://github.com/user-attachments/assets/2ef7a708-a013-4bd1-a699-4777af9f1c3c)

<p>
Let's re-observe the banking system ticket and note if you can still view or change it after setting properties. As you can see the propreties changed.
</p> 
<br />


image

<p>
Work tickets to completion: (a) Jane resolves the banking system ticket, (b) John resolves the adobe upgrade ticket, (c) John resolves the CFO laptop ticket—document steps and close each.
</p>


![Screenshot 2025-04-02 013605](https://github.com/user-attachments/assets/fb192cb9-a849-4c68-9bcf-2f75d80c178e)

<p>
plain text 
</p>
<br />


![Screenshot 2025-04-02 013626](https://github.com/user-attachments/assets/bb1eda8c-03e2-4fef-b81e-50aacf376177)

<p>
plain text
</p> 
<br />


image

<p>
plain text 
</p>


image

<p>
plain text 
</p>
<br />


image

<p>
plain text
</p> 
<br />


image

<p>
plain text 
</p>

# Help Desk Ticketing System Overview

## Objective
In this lab, we'll simulate a help desk ticketing system workflow by:
- Creating tickets as end-users
- Observing ticket properties as help desk professionals
- Managing department structures
- Working tickets to completion

## Initial Setup
1. Change the SysAdmins Department to a Top Level Department
2. DELETE the Maintenance Department (do not archive)

## Ticket 1: Online Banking System Down
### End-User Steps
1. Create ticket with description: "entire mobile/online banking system is down"

### Help Desk Agent (John) Steps
1. Observe ticket properties:
   - Priority
   - Department
   - SLA
   - Assigned To
2. Set ticket properties:
   - Priority: Sev-A (1 hour, 24/7)
   - Department: Online Banking Department
3. Attempt to observe ticket again as John
   - Note if you can view or change the ticket

### Help Desk Agent (Jane) Steps
1. Work ticket to completion
   - Document resolution steps
   - Close ticket

## Ticket 2: Adobe Upgrade Request
### End-User Steps
1. Create ticket with description: "accounting department needs adobe upgrade, broken"

### Help Desk Agent (John) Steps
1. Observe ticket properties:
   - Priority
   - Department
   - SLA
   - Assigned To
2. Set ticket properties:
   - Priority: Sev-B (4 hours, 24/7)
   - Department: Support
3. Work ticket to completion
   - Document resolution steps
   - Close ticket

## Ticket 3: CFO Laptop Failure
### End-User Steps
1. Create ticket with description: "CFO’s laptop will no longer turn on"

### Help Desk Agent (John) Steps
1. Observe ticket properties:
   - Priority
   - Department
   - SLA
   - Assigned To
2. Set ticket properties:
   - Priority: Sev-B (4 hours, 24/7)
   - Department: Support
3. Work ticket to completion
   - Document resolution steps
   - Close ticket

## Escalation Exercise
1. Set all tickets to SEV-A priority with SysAdmins department (do this last)
2. Observe that tickets become inaccessible
3. Switch to admin panel
   - Assign yourself View-access to SysAdmins department
4. Switch to agent panel
   - Observe the escalated ticket
   - Note that you can no longer make changes
5. Solve all tickets
   - Document resolution steps
   - Close tickets

## Email Functionality
Most ticketing systems include email capabilities:
- Each ticket update sends a copy to the user
- Users can respond directly via email
- Responses are automatically attached to the ticket

## Real-World Ticket Intake
Tickets can be created through various channels:
- Phone calls
- Chat applications
- Email submissions
- Web forms
- In-person requests (hallway conversations or desk visits)

Best Practices:
- Some users may pressure for immediate fixes
- It's acceptable to fix issues on the spot
- ALWAYS create tickets for ALL work performed
- Metrics tracking is crucial for:
  - Performance evaluation
  - Resource allocation
  - Process improvement

## Finishing Up & Additional Practice
### Next Steps
- This lab covers basic functionality only
- Explore the email feature in depth
- Repeat this lab multiple times until comfortable with:
  - Ticket creation
  - Property management
  - Department handling
  - Resolution workflow

### Technical Skill Development
- Practice builds intuition
- Reinforces technical ability
- Recommend completing lab 3-5 times
- Use this checklist as a reference

### Simple Checklist
1. Create ticket as end-user
2. Observe properties as agent
3. Set appropriate properties
4. Work ticket to completion
5. Verify email notifications
6. Document resolution
