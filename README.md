# free
Checklist Pro Pre-Built Solutions (March 31, 2025)
Checklist Pro is a no-code / low-code tool for developers (citizen developers to pro-coders alike) providing
cost-saving options for solving problems on the ServiceNow platform. One of the benefits that Checklist Pro
customers enjoy is access to an ever-growing suite of pre-built solutions to provide immediate value for a
variety of commonly occurring ServiceNow business use cases.

These solutions are available as update sets that can be installed, configured and even modified to suit the
needs of each customer.

Text to Checklist (AI Assist)
You've heard of Text-to-Code? Well now there's a Text-to-Checklist!
Our pre-built Checklist Pro solution provides an "AI Assist" button that integrates seamlessly with AI-in-a-Box,
a private AI solution designed to help you get things done with maximum security and control at a fraction of
the price. Integration with ServiceNow’s Now Assist coming soon!
Simply ask a question on a topic and this integration generates a tailored response that, with one button click,
creates a ready-to-use Checklist directly in Checklist Pro.
The AI prompt returns a Markdown format checklist that is then transformed into a Checklist Pro
checklist at the click of a button.
Video: https://youtu.be/EwhWTRBIqug



Delegated Developer Jump-Start Program
Question: How do you tap the full potential of ServiceNow, bringing to life an endless stream of simple
services and workflows solving your organizational needs with a limited budget and limited development
resources with their own set of priorities?
Answer: Leverage your domain expertise by having them build Service Catalog items.
Problem: How do you govern this activity to ensure platform integrity and consistency with your catalog and
workflows?

Solution: It’s a serious challenge but one that is easily solved with Checklist Pro.
The Checklist Pro Delegated Developer package provides a Catalog Builder template to allow those with no
ServiceNow skills to build a Service Catalog item in seconds and leverages a pre-built simple workflow
providing an optional approval step followed by an optional work-completion step.

Your Delegated Developer community need only know the following things:
• The name of the Catalog Item to be created
• A short description of what the Catalog Item does
• A set of input data to be collected from the service requesters, built in Checklist Pro as a checklist (as easy as building a word document)
• A set of processing instructions also configured in Checklist Pro as a checklist of things to do to have the request completed
• Pick a group for approving (if necessary)
• Pick a group to complete the work (if necessary)

We’ve had customers build interesting services such as Telework Request, setting up Email Relay Servers and others in as little as 10 minutes.
Video: https://youtu.be/_JbQ4gMtNUs



GRC Attestation
Governance Risk and Compliance (GRC) helps organizations automate risk management, compliance
tracking, and policy enforcement to improve security and regulatory adherence.
This comprehensive and full-featured application from ServiceNow can be complex and costly for those in the
organization that review controls to assert (or “attest”) their validity and necessity, especially when those
performing these activities only occur a couple of times per year.
To simplify this step and reduce the costs associated with having users with attestation-performing duties, a
Checklist Pro solution provides a simple to use, cost-saving alternative that inserts directly into the
out-of-the-box (OOB) GRC Attestation process. Simply leave the OOB attestation field on the GRC Control
record blank and a Checklist Approval with GRC Attestation checklist will be sent to the specified reviewers.
Since Checklist Approvals are used vs OOB GRC Attestations, any user in your organization, even those without
ServiceNow roles, can be selected to perform this work. The results of the Checklist Approval are carried back
into the GRC Control record and the normal GRC Attestation process continues, but with a cost-saving and
more simplistic approach applied.



Knowledge Article Checklist Approval
Knowledge Base articles can be a source of truth for policies, procedures and troubleshooting, but to
ensure this, reviews and oversight are often required. ServiceNow provides an option for approvals of
articles before they are published, but these approvals come at the cost of Business Stakeholder licenses.
Checklist Pro provides an alternative to OOB approvals that require users with Business Stakeholder roles
(incurring a paid subscription cost per approver). By utilizing Checklist Approvals, accessible to Requester
users (i.e., unlicensed users), in the Knowledge Article review process, organizations can grow the number of
KB article reviewers without growing their Business Stakeholder subscription costs.
Video: https://youtu.be/Erd8mhwBe24



Fillable PDF to Checklist and Back to Fillable PDF
Fillable PDFs are everywhere, in ServiceNow too, especially prevalent in HRSD, Knowledge Base and
Document Management applications.

It is often necessary to capture information first in ServiceNow, for various business operations and
decision-making workflow activities and then store it in PDFs.

Since Checklist Pro checklists are a natural way to capture user input, we provide a “Generate Checklist from
PDF” option that will scan a fillable PDF attached to a Checklist Pro Configuration file and you instantly have a
checklist that represents the fillable fields from that PDF and then another button to “Save as PDF” to store
those checklist items back into the Fillable PDF.
Video: https://youtu.be/qw9l31VLpqo



Data Stewardship Solutions
There’s core (critical) data in every ServiceNow instance: users, groups, departments. Everyone has them
and almost certainly everyone has experienced cases where this data becomes incorrect:
• Users in the wrong groups
• Users reporting to the wrong managers
• Users in the wrong departments

If this information is incorrect, it can cause problems:
• Improper work assignments or approval requests
• Access to information that should not be permitted
• Subscription cost impacts for users with premium roles that are not appropriate

Customers with Checklist Pro can get access to our “Data Stewardship” solutions that prevent this from
happening:
• Group Member Management
   o Checklist Approval sent to Group Manager to review the list of employees in the group(s) they manage.
   o The manager can uncheck the member that should be removed or (using a person picker), add people that should be in the group.
   o Once changes are made (if any are required), the manager clicks approve and the group is updated. If Active Directory needs to be updated, an Integration Hub call can be added.
   o Video: https://youtu.be/FyRbismEwUE

This same Checklist Pro approach (method as described above) also applies to these use-cases:
• Manager / Employee Relationship Management
• Department Member Management
• Business Unit Management

The added benefit of this solution is Checklist Approvals are leveraged (vs OOB Approvals or Task – both of
which require paid subscribers). Checklist Approvals are available to free requester users and thus the
governance / oversight of this functionality does not come with subscription cost penalties.



CMDB Server Assessment
In your CMDB, certain things may not be discoverable, such as who is responsible for managing a Server.
Nevertheless, knowing who is responsible for managing each Server is important and having a means to
oversee and govern such activities is very important.

This is why we have built the CMDB Server Assessment solution. With this solution, a scheduled job reviews
the Server CIs, creating a Checklist Assignment record for each unique person responsible for managing a
Server. Each Server listed as being managed by that person is listed as a checklist item in the Checklist
Assignment record for that Server manager.

Since Checklist Assignments can be assigned and completed by any user, even those without roles, they can
easily review the checklist of hardware items listed as being assigned to them. Any Servers still managed by
the assigned manager they leave checked. Servers they no longer manage should be unchecked. If they need
to add Servers not listed, the simply use the Server picker at the bottom of the checklist and click the “Add”
button to add it to the list of Servers that they manage.

Once finished, the click the “Complete” button to show the Checklist Assignment has completed.
We’ve built a CMDB Server dashboard to highlight a variety of key findings such as:
• Total number of Servers being managed
• # In-progress Server assessments
• # completed Server assessments
• # cancelled (incomplete) Server assessments
• # Server assessments needing review – these would be cases where the Servers were added or removed by the Server manager completing the assessment (this can help create a double check review by the organization to ensure accuracy)
• # In-progress Server assessments with updates - though the Server manager hasn’t completed their assessment, they’ve already made some changes so this can give a “heads up” that additional reviews may be necessary

Using Checklist Pro for solutions such as this can be a valuable supplement to your organization’s CMDB
Server activities by providing a governance / oversight solution to ensure accuracy within your CMDB.
Video: https://youtu.be/BdvTY7k009w



Ready-to-Use Checklists
We have a growing list of checklists, which may be placed on any record (OOB Approval, Change Task, Catalog
Task, you name it). These checklists may be a spot on use, or can be changed to suit your needs, or inspire
ideas for how to build your own.
• Environment, Health & Safety (EHS)
   o Emergency Preparedness Inspections
   o Hazard Material Handling Inspections
   o General Safety Inspections
   o Machine Safety Inspections
   o Fire Safety Inspections
   o Personal Protective Equipment (PPE)
   o Environmental Compliance
   o Chemical Safety Inspections
• North American Electrical Reliability Corporation Critical Infrastructure Protection (NERC-CIP)
• Project Management (SPM)
   o Video: https://youtu.be/J4ACZ8IETXU
• ServiceNow Instance Upgrade
   o Video 1: https://youtu.be/RNRr4yKQDHs
   o Video 2: https://youtu.be/SHWcwAE5Qbc
