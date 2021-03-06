**General Services Administration**

Federal Acquisition Service<br>
Technology Transformation Services<br>
18F and Office of Acquisitions<br>
1800 F St. NW \| Washington, DC \| 20405

**Assisted Acquisition on Behalf of the Office of Family Assistance**

TANF Data Reporting System (TDRS) Software Development Services

# Request for Quote

**From:** Brian Burns, Contracting Officer (CO), General Services
Administration (GSA), Central Office, Office of Acquisitions<br>
**Issued for:** GSA, FAS, Technology Transformation Services (TTS),
18F<br>
**Subject:** Request for Quotation (RFQ)<br>
**Date:** February 5, 2020<br>
**Set-aside:** Total Small Business<br>
**Contract vehicles:** GSA Schedule Schedule IT 70; SINs 132 51
(information technology professional services) and 132 34 (software
maintenance services).

All clauses, terms and conditions of the schedule holder's contract
apply / flow down to this solicitation and resultant task order
contract. In the event of a conflict between the schedule contract and
an order, the terms and conditions of the schedule contract prevail.

## Deadlines and response formats

Item                          | Date responses due                | Format
------------------------------|-----------------------------------|-------
**RFQ Questions and Answers** | MONTH DD, 2020 at noon, eastern   | Google Form (see section X for details)
**Technical Volume**          | MONTH DD, 2020 at noon, eastern   | Google Form and Google Document (see section X for details)
**Pricing Sheet**             | MONTH DD, 2020 at noon, eastern   | Excel Spreadsheet (see section X for details)

Government Point of Contact |
----------------------------|----------------------
Contracting Officer         | *Brian Burns*
Contracting Office          | *General Services Administration, Federal Acquisition Service, Technology Transformation Services, Office of Acquisition*
Email                       | *brian.burns\@gsa.gov*
Correspondence              | *Any emails related to this RFQ shall use the email subject heading "RFQ12345 - \[Vendor's Name\]"*

Important Dates, Times, and Posting Information | 
------------------------------------------------|---------------------
RFQ Posting Date                                | *TBD*
RFQ Closing Date                                | *TBD*
RFQ Posting Location                            | *TBD*
Questions Due:                                  | *TBD*
How to Submit Questions                         | *Email to the Contracting Officer*
Response to Questions Est. Return Date          | *TBD*
Posting Location for Answers                    | *TBD*     
Communications During RFQ Posting               | *The only method by which any terms and conditions of this RFQ may be changed is by a formal amendment generated by the CO. No other communication made whether oral or in writing will modify or supersede the terms of the RFQ. All communication related to the RFQ shall be directed to the Contracting Officer via email.*


# Contract Place of Performance and Contract Type

Any work done, whether onsite or offsite, must be covered by the rate
agreed upon between the government and contractor. The contractor will
generally be expected to be available during core working hours from
10:00am to 3:00pm eastern standard time Monday through Friday.
Contractors are not expected to work Federal Holidays or other occasions
when the government is closed.

The contractor may choose the location(s) from which to perform the
required software development services. The contractor will not be
required to work at a government facility, however occasional travel to
government facilities may be required. Actual travel costs to government
facilities will be reimbursed in accordance with [federal travel
regulation](https://www.gsa.gov/policy-regulations/regulations/federal-travel-regulation-ftr)).


# Operating Constraints (Non-functional Requirements)

## Environment

### System Requirements

The System must incorporate an intuitive web-based interface that is accessible from both internal and external platforms, including desktops, laptops, tablets, thin/zero clients, and mobile devices. The System architecture must incorporate Application Programming Interfaces (APIs) to intermediate major components. The System must not have a single point of failure. The System will use elastic, dynamically-allocated computing resources that accommodate changing demand in real time. The System must include Login.gov user authentication and authorization functionality and use open source encryption protocols. 

At some point in the future, the system may migrate to an ACF cloud environment. The type of environment is unknown at this time, so the application should be written to be as operationally portable as possible.


### Software Requirements

The software architecture must be extensible to allow for future development. The code base must incorporate analytics, monitoring, continuous integration, and measurement tools. Application design and development must use [plain language](https://content-guide.18f.gov/plain-language/) to the extent practical.

### Design Requirements

Any website that is developed or otherwise delivered as a result of this contract shall be in compliance with the website standards of the Technology Transformation Services of the General Services Administration.
The U.S. Web Design System (USWDS) shall be adopted incrementally over the life of the requirement and the contractor shall prioritize implementation to align with the priorities identified within the SOO. 

### Environments

The System will be hosted on Cloud.gov (a FedRAMP-certified internet-connected Platform as a Service). OFA will own and manage the Cloud.gov account and create development, staging, and production environments for this project within that account. The Contractor will have access to the development environment and will be responsible for maintaining that environment. The Contractor must post all developed code to a public source repository (such as GitHub) designated by OFA. OFA will be responsible for creating and managing this repository. OFA will be responsible for setting up and maintaining a Continuous Integration/Continuous Deployment system to automate the deployment of the code in GitHub. OFA will be responsible for creating, maintaining, and managing the Login.gov integrations.

### System Access

All contractor personnel working under the resulting contract will need to obtain a Homeland Security Presidential Directive 12 [HSPD-12](https://www.dhs.gov/homeland-security-presidential-directive-12) low risk security clearance (or moderate risk security clearance if handling PII) and may need to obtain a personal identity verification (PIV) card in order to perform legacy system integration work. See section 9.9 for additional details.

Contractor personnel that are required to obtain a PIV card will be issued a government-furnished laptop from OFA. Any work that requires access to and handling of PII must be performed on the OFA government-furnished laptop. Contractor personnel that are not required to obtain a PIV card can use contractor-furnished equipment to perform work.

Contractors may have to establish multi-factor authentication (MFA) to access systems which would require government laptops with PIV cards or only MFA through various applications. 

### Additional info that will be provided TBD

## Personnel Skills and Knowledge

### Key Personnel

The contractor must designate a Facilitator,
Technical Lead, and Design Lead as Key Personnel for this project.

- The Facilitator will be a direct liaison to the government product team, and will be responsible for the supervision and management of all of the contractor’s personnel. The Facilitator does not need to be a separate individual and may be a role also fulfilled by any of the Key Personnel proposed. This person should have a background as a scrum master, product manager, agile coach, or a similar type of role.
- The Technical Lead must have a full understanding of the technical approach to be used by the contractor’s development team and will be responsible for ensuring that the contractor’s development team follows that approach. This person should have a background as an engineer.
- The Design Lead must have a full understanding of the research approach and design patterns to be used by the contractor’s development team and will be responsible for ensuring that the contractor’s development team follows that approach. This person should have a background as an user experience researcher or designer.

### Key Personnel Substitution

Key Personnel substitutions must be
submitted to the CO in writing, and will only be justified in the event
of sudden illness, death, change of employment, or termination of
employment for cause. Contractor requests for a substitution of Key
Personnel must include a detailed explanation of the justifying
circumstances, and a complete résumé for the proposed substitute or
addition, including skills, experience, training, and security clearance
level (if applicable). The CO's failure to approve a proposed
substitution will not constitute grounds for non-performance by the
contractor, or form a valid basis for any claim for money or any
equitable adjustment.

### Skills

The contractor must provide a cross functional team that is
experienced in working in an Agile process. They must be comfortable
delivering value iteratively and able to pivot quickly based on a
continuous learning environment. The contractor team will use prototypes
and working software as tools to test hypotheses and validate
assumptions. The team should be expected to deliver working software
early in the post-award period, and to iteratively improve the software
through ongoing development sprints (2 week intervals).

The relevant skills for this project *may* include---
-   Product management
-   Back-end engineering
-   Front-end engineering
-   DevSecOps engineering
-   User research
-   Content design
-   Visual design
-   User support, training, and onboarding

# Special Clauses

Contractor Team Arrangements (CTA) are permitted.

Note - FAR 9.6, Contractor Team Arrangements, does not apply to GSA
Schedules teaming. Under GSA Schedules, Teaming allows contractors to
use their individual GSA Schedules to develop a solution for the
government.

*If the vendor intends to team, a CTA is required by the closing date
and time of the RFQ. However, a fully executed CTA will be formalized at
time of award. CTAs shall utilize and submit this [Contract Team Agreement](https://docs.google.com/document/d/1oA7Ln2tGusmaO1oj6Lpg6xUqpVgmZWwzva9WDQZZcYg/edit#)
when a CTA is applicable.*

CTAs will not be evaluated, but will be reviewed to:
-   Gain an understanding of how the arrangement will work
-   Identify any areas of responsibility that may require clarification
-   Identify deficiencies in the CTA in order to understand the
    probability of successful performance
-   Verify proposed prices/rates against MAS contract awarded
    prices/rates.
