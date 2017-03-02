# POC Agenda
*Updated 2017, March 1 by Matthew Ward*

## Summary
The Mid-Market Specialist SA team is skilled in but not equipped, staffing wise, to handle a steady stream of POCs. Free POC should be used tactically and as a tool for particularly large deals. The purpose of the POC is to prove that our technology can do what's advertised in their own environment. In most cases the customer is better served with a customized demo showing the particular feature demonstrated by the customer.

## Restrictions
* This POC will not be conducted on a production environment.
* Upon completion of the POC testing phase, the customer will remove the POC environment.  
* All POC must be approved by the regional Mid-Market Sales Specialist and the Mid-Market Specialist Solution Architect.
* Customer and Red Hat Specialist team must agree to POC Scope or Work and adhere to those guidelines. When the CloudForms Specialist SA leaves, there will be no on-going support for the POC environment.
* POC must be performed using the customer 'Supported Evaluation Subscription'.

## Requirements
This section must be completed by the customer or partner before the Red Hat Cloud Specialist resource comes on site. This is to help maximize the time for meeting POC expectations along with required troubleshooting. 


## Basic POC
Purpose of this section is it outline what will be done in a POC. This POC is designed to be 1 day worth of effort. For multiple day POC, day 1 will be the Basic Setup and the remaining days will be Advanced Setup.

* Basic Configuration
   * Configure Appliance
      * Configure Networking
      * Configure Database Appliance
      * Configure Compute Appliance
   * Connect Provider
      * Connect up to 2 Infrastructure providers (VMWare, Red Hat Virutalization or Red Hat OpenStack)
      * Validate the VMs from the Virtual Environment are discovered in CloudForms.
* CloudForms Configuration
   * Settings
      * Set 'Basic' information
      * Set 'Server Roles'
      * Set Additional information
         * NTP and outgoing SMTP Server
   * Tenants and Projects
      * Implement pre-agreed on Tenants and Projects
      * Set Quota for Projects or Tenants
   * User, Groups and Roles
      * Implement pre-agreed on Users and Groups.
      * Assign groups to Pre-made Roles.
   * Tags and C & U
      * Implement pre-agreed on Tags
      * Turn on Collection and Utilization
* Cloud Intel Configuration
   * Chargeback Reporting
      * Create one (1) Custom Chargeback report.
      * Help customer create an Assignment Policy for the Chargeback reports.
   * Reports
      * Create one (1) Custom Report.
      * Create a schedule for the Custom Report to run.
      * Queue report, if customer desires.
* Compute
   * Tour the user interface.
   * Provision an Instance for a customer. (If Desired)
   * Set a 'Retirement' date on the provision system (If Desired)
   * Start a 'SmartState Analysis' on selected VMs.
* Policy Management
   * Implement pre-agreed upon Compliance or Control Policy.
   * Test policy against agreed upon VM.
   * Apply policy against agreed upon VM.

## Advanced POC
