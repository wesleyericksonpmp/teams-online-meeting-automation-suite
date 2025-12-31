# Power Automate Flow & Connector Usage Guide

This document provides step-by-step instructions for using the Power Automate custom connector and flows for Microsoft Teams Online Meetings.

## Contents
- Azure AD App Registration
- Custom Connector Setup
- Power Automate Solution Import
- Usage Examples
- Troubleshooting

## 1. Azure AD App Registration
(Include your app registration steps here or refer to the implementation guide.)

## 2. Importing the Custom Connector
- Go to Power Automate > Data > Custom connectors > Import an OpenAPI file
- Select the Swagger file from the `../swagger/` folder
- Complete the authentication setup as described

## 3. Importing the Power Automate Solution
- Go to Power Automate > Solutions > Import
- Select the exported solution from the `../exported-solution/` folder
- Rebind connections as needed

## 4. Using the Flow
- Trigger the flow manually or as configured
- Provide required parameters (meeting join URL, etc.)
- Review outputs and results

## 5. Troubleshooting
- See the implementation guide for common issues

## 6. Screenshots
Refer to the `../screenshots/` folder for visual setup and usage steps.

---
