# Automated-Employee-Onboarding-Offboarding
# Employee Lifecycle Management - ServiceNow

## Project Overview

The Employee Lifecycle Management application is built on ServiceNow to automate employee onboarding and offboarding processes.

The application manages employee lifecycle requests, manager approvals, status updates, and departmental task creation.

## Features

- Employee Onboarding and Offboarding request through Service Catalog
- Employee Lifecycle record creation
- Manager approval process
- Automatic status updates
- HR task creation
- IT task creation
- Facilities task creation
- Security task creation
- Rejection handling

## Technologies Used

- ServiceNow
- App Engine Studio
- Service Catalog
- Flow Designer
- Custom Tables
- Approval Management
- Task Management

## Workflow

1. User submits an Onboard / Offboard Employee request.
2. The Service Catalog triggers the Employee Lifecycle Request Flow.
3. Catalog variables are retrieved.
4. An Employee Lifecycle record is created.
5. Manager approval is requested.
6. If approved:
   - Manager Approval Status becomes Approved.
   - Status becomes In Progress.
   - HR task is created.
   - IT task is created.
   - Facilities task is created.
   - Security task is created.
7. If rejected:
   - Manager Approval Status becomes Rejected.
   - Status becomes Rejected.
   - Departmental tasks are not created.

## Demo Video

[Watch the Project Demo](PASTE-YOUR-GOOGLE-DRIVE-LINK-HERE)

## Project File

The ServiceNow Update Set XML file is included in this repository.

## Author

Nikhil Isukapatla
