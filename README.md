# TAC-Interaction---SMS-Webex-Team-Automation-Workflow
TAC Interaction - SMS &amp; Webex Team Automation Workflow

Purpose of the Automation Workflow:

The objective of the automation workflow is to notify proactively the Customer by SMS and through a Public WebEx Teams Space about any P1 and P2 TAC Cases. With this the Customer’s L3 Support Teams will have full visibility of the most important incidents. This WebEx Teams space will be managed by the HTOM.

Using the Public Space, the customer can request the following info:
      Status of the Case
      Description of the Case
      Rise Severity of the Case
      Who is the owner of the Case
      Last updated date.
      Escalation of the Case
      Ask if there is any Bug
      Ask for the status of a RMA
      Get a link of the case

How this works?
    New TAC Case P1/P2 Opened by the Customer.
    Cisco Foosball Notification by e-mail.
    Triger event for Workflow.
    Notification on the Public WebEx Teams Space about the new Case (Case # embedded on the Notification).
    Send SMS to an specific Mobile #
    HTOM or SE participating on that public Space uses a WebEx Teams TAC Bot to request more info regarding the TAC Case (14 commands available).
    The TAC Case info requested automatically appears on the Public WebEx Teams Space and is sent using SMS Integration to an specific Mobile #
    The Customer doesn’t need to contact the TAC Front Line to check the Status of the case. The customer just need to post a message on the WebEx Teams Public Space to get:
    Status of the case, bug & RMA
    Provides contact details of case owner
    Connects the user with case owner after getting engineer’s consent
    Assists with basic transactions such as change
    severity, requeue and escalate

Automation Tools Used:
  Workflow Built using Built.io.
  REST API Webex Team App Integration
  REST API Twilio AppIntegration
  Webex TEams TAC Connected Bot
