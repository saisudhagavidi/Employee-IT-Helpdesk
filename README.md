# Employee IT Helpdesk & Service Request Portal

A ServiceNow-based Employee IT Helpdesk and Service Request Management application designed to streamline IT incident reporting, service requests, approvals, assignment, SLA tracking, notifications, and reporting.

## Project Overview

The Employee IT Helpdesk & Service Request Portal provides employees with a centralized platform to report IT issues and request IT services.

The application automates the complete process from issue/request submission to assignment, approval, fulfillment, resolution, and notification.

## Problem Statement

In many organizations, employees depend on emails, phone calls, or manual communication to report IT problems and request services. This can result in delayed responses, incorrect assignment, poor tracking, and lack of visibility into IT support performance.

This project provides a centralized ServiceNow-based solution for managing employee IT incidents and service requests with automated workflows and SLA monitoring.

## Objectives

* Provide a centralized IT helpdesk for employees
* Automate incident assignment
* Provide an IT Service Catalog
* Automate request approval workflows
* Track SLA performance
* Notify employees about request and incident updates
* Provide role-based access and security
* Provide reports and dashboards for IT management
* Improve IT support efficiency and visibility

## Technology Stack

* ServiceNow
* ITSM
* Service Catalog
* Flow Designer
* Business Rules
* Client Scripts
* UI Policies
* GlideRecord
* ACLs
* SLA
* Employee Center
* Reports & Dashboards

## Main Features

### Incident Management

Employees can report IT issues such as:

* Hardware problems
* Software problems
* Network issues
* Security issues
* Application issues

Incidents are automatically prioritized and assigned to the appropriate IT support group.

### Service Catalog

Employees can request IT services through the Service Catalog.

Planned catalog items include:

* Laptop Request
* Software Installation
* Application Access

### Automated Approvals

Requests can be routed for approval based on the requested service.

Examples:

* Laptop Request → Manager Approval
* Software Installation → Manager Approval
* Application Access → Manager Approval → Application Owner Approval

### Assignment Automation

Incidents and requests are routed to appropriate support teams.

| Category    | Assignment Group    |
| ----------- | ------------------- |
| Hardware    | Hardware Support    |
| Software    | Software Support    |
| Network     | Network Support     |
| Security    | Security Support    |
| Application | Application Support |
| Other       | IT Helpdesk         |

### SLA Management

SLAs will be configured to monitor incident resolution and identify SLA breaches.

### Notifications

The system will provide notifications for important events such as:

* Incident creation
* Incident assignment
* Incident updates
* Incident resolution
* Request submission
* Approval requests
* Approval decisions
* Request completion

### Security

Role-based access and ACLs will be used to control access to application data and functionality.

## Application Roles

* Employee
* IT Agent
* IT Manager
* Helpdesk Admin

## Assignment Groups

* IT Helpdesk
* Network Support
* Hardware Support
* Software Support
* Security Support
* Application Support

## Project Architecture

```text
Employee
    |
    v
Employee Center
    |
    +--------------------+
    |                    |
    v                    v
Report an Issue     Browse Services
    |                    |
    v                    v
Incident              Request
    |                    |
    v                    v
Priority            Approval
    |                    |
    v                    v
Assignment          Fulfillment
    |                    |
    +---------+----------+
              |
              v
             SLA
              |
              v
         Resolution
              |
              v
        Notification
```

## Project Structure

```text
Employee-IT-Helpdesk/
│
├── README.md
│
├── Documentation/
│
├── Screenshots/
│
├── Configuration/
│
├── Scripts/
│
└── Testing/
```

## Development Progress

| Phase                        | Status         |
| ---------------------------- | -------------- |
| Application Foundation       | ✅ Completed    |
| Users, Roles & Groups        | 🔄 In Progress |
| Incident Management          | ⏳ Pending      |
| UI Policies & Client Scripts | ⏳ Pending      |
| Priority Automation          | ⏳ Pending      |
| Assignment Automation        | ⏳ Pending      |
| Service Catalog              | ⏳ Pen          |
