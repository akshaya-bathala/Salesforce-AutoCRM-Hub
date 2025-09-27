# Salesforce-AutoCRM-Hub
AutoCRM Hub is a Salesforce-based application designed for car companies to streamline the vehicle ordering process. It prevents out-of-stock orders with Apex validation, auto-assigns customers to nearby dealers, and uses workflows and scheduled jobs to send real-time updates and reminders.

# Project Phases & Achievements
## Phase 1: Problem Understanding & Industry Analysis

Studied challenges in vehicle ordering, dealer assignment, and stock management.

Identified key objectives: prevent out-of-stock orders, assign nearest dealers automatically, and enhance customer engagement.

## Phase 2: Org Setup & Configuration

Configured Salesforce Developer Org for development and testing.

Enabled required features, created sample users, profiles, and roles.

## Phase 3: Data Modeling & Relationships

Created custom objects: Vehicle__c, Vehicle_Dealer__c, Vehicle_Customer__c, Vehicle_Order__c, Vehicle_Test_Drive__c, Vehicle_Service_Request__c.

Defined fields, lookups, and picklists to model customer-dealer-vehicle relationships.

## Phase 4: Process Automation (Admin)

Built Flows to auto-assign nearest dealers to customers on order creation.

Created Validation Rules to prevent orders for out-of-stock vehicles.

Implemented workflow rules and email alerts for test drives and service requests.

## Phase 5: Apex Programming (Developer)

Developed Triggers and Trigger Handlers for Vehicle_Order__c to manage stock and prevent invalid orders.

Implemented Batch Apex to process pending orders in bulk.

Scheduled batch jobs using Schedulable Apex for automated order confirmation and stock updates.

## Phase 6: User Interface Development

Created Lightning Record Pages for Vehicles, Dealers, Customers, and Orders.

Built Lightning Web Components (LWC) to display customer and dealer info dynamically.

Integrated LWC with Apex for real-time updates and dealer assignment logic.

## Phase 7: Integration & External Access

Exposed APIs for integration with POS systems.

Enabled Experience Cloud portal for customers to track orders and test drives.

## Phase 8: Data Management & Deployment

Used Data Loader and Data Import Wizard for initial datasets.

Deployed changes using Change Sets and Salesforce CLI (where applicable).

Maintained proper versioning and backup for all configurations.

## Phase 9: Reporting, Dashboards & Security Review

Created reports: Top dealers, order status, popular vehicles, test drive stats.

Built dashboards for managers to monitor orders, stock levels, and customer activity.

Configured profiles, roles, and sharing rules for secure data access.
