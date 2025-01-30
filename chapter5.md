# Chapter 5 Project Management
## Index
* [Chapter 5 Project Management](#chapter-5-project-management)
  * [Index](#index)
  * [Initiating the IT Security Project](#initiating-the-it-security-project)
  * [Monitoring and Managing IT Security Project Progress](#monitoring-and-managing-it-security-project-progress)
    * [Notes](#notes)
    * [Does GDPR apply to Malaysian businesses?](#does-gdpr-apply-to-malaysian-businesses)
    * [Law regarding security and privacy in Malaysia](#law-regarding-security-and-privacy-in-malaysia)
      * [PDPA vs GDPR](#pdpa-vs-gdpr)
      * [What is IT Compliance](#what-is-it-compliance)
        * [Security](#security)
        * [Compliance](#compliance)
      * [Benefits of compliance issue](#benefits-of-compliance-issue)
    * [Task Progress](#task-progress)
    * [Project Progress](#project-progress)
    * [Issues Reporting and Resolution](#issues-reporting-and-resolution)
    * [Documentation](#documentation)
      * [Example of Information Security Risk and Compliance Project Manager task](#example-of-information-security-risk-and-compliance-project-manager-task)
      * [Information Security Risk and Compliance Project Manager job](#information-security-risk-and-compliance-project-manager-job)
  * [Managing IT Security Project Risk](#managing-it-security-project-risk)
    * [What is the risk ?](#what-is-the-risk-)
    * [Impact of not handling the risk](#impact-of-not-handling-the-risk)
    * [Assessing the inherent impact of your information security risk](#assessing-the-inherent-impact-of-your-information-security-risk)
    * [How to asses the inherent probability of your information security risk](#how-to-asses-the-inherent-probability-of-your-information-security-risk)
    * [Controls that manage your information security risk](#controls-that-manage-your-information-security-risk)
    * [Monitoring to assess the functionality of the controls](#monitoring-to-assess-the-functionality-of-the-controls)
  * [Managing IT Security Project Change](#managing-it-security-project-change)
    * [Key Stakeholder Change (Ways of handling the change request)](#key-stakeholder-change-ways-of-handling-the-change-request)
    * [Key Staff Change](#key-staff-change)
    * [Key Environmental Change](#key-environmental-change)
  * [Testing IT Security Project Results](#testing-it-security-project-results)

## Initiating the IT Security Project
1. Best place to start your Information Technology (IT) security project is to make sure that all of your prior definition and planning tasks have been completed.
2. At this point, you should have the following:
   - Problem statement
   - Mission statement
   - Selected solution
   - Project constraints and priorities
   - Project requirements (functional, technical, legal)
   - Work breakdown structure (WBS) with all tasks and task details defined
   - Project risks and mitigation strategies
   - Project budget and schedule
   - Required competencies identified
   - Project team formed
   - Project processes defined
3. Do final "scope check" to ensure that the scope of work hans't increased before the project work has begun.
4. Notifies the organization that the project resources are now required for the IT security project.
5. Defined processes and procedures, and addressing issues and changes according to plan parameters is vitally important to a successful project outcome.

## Monitoring and Managing IT Security Project Progress
1. The biggest challenge in an IT security project is managing the compliance issues.
2. You need to establish processes and procedures that ensure that your results are compliant with whatever regulations apply to your firm.
3. Document your documentation.

### Notes
1. HIPAA
   - Health Insurance Portability and Accountability Act
   - fines ranging from $100 to $50,000 per violation
2. PCI-DSS
   - Payment Card Industry Data Security Standard
   - fines between $5,000 and $100,000 per month
3. GDPR
   - General Data Protection Act
   - fines up to 4% of annual global turnover or €20 million euros, whichever is higher

### Does GDPR apply to Malaysian businesses?
- Yes, the GDPR applies if a Malaysian business:
- Offers goods and services to customers or businesses in the EU or
- Monitor the behaviour data subjects in the EU.
- In Malaysia, we do not have a standalone Cyber Security Law, but a number of sporadic laws in this area to counter cybercrimes. These includes:
1. Computer Crimes Act 1997 (similar to UK's Computer Misuse Act 1990)
2. Communications and Multimedia Act 1998
3. Penal Code
4. Copyright Act 1987
5. Personal Data Protection Act 2010
6. Digital Signature Act 1997
7. Strategic Trade Act 2010
8. Sedition Act 1948
9. Case laws
10. Other specific guidelines/policies

### Law regarding security and privacy in Malaysia
1. Additionally, there are several legal compliances to be exercised, some are strict but some merely serves as guidelines:
   - Personal Data Protection Act 2010 (PDPA)
     - Misuse of another person's personal details may also be a criminal offence.
   - Currently, Malaysia does not have a specific law addressing cybersecurity-related offences-National cyber security has to reply on:
     - Communications and Multimedia Act 1998 (CMA)
     - the Defamation Act 1957
     - Sedition Act 1948
   - Digital Signature Act 1997 - Compliance is also strict with all secure electronic transactions service providers.
   - National Cyber Security Policy (NCSP) - this is a national policy devise to ensure compliance with information security standards in respect of information critical to national interests and security and potentially collapse the nation's economy.
   - Credit Reporting Agencies Act 2010 - which came into force on 15 January 2014, now provides for the registration of persons carrying on credit reporting bussinesses under the regulatory oversight of the Registrar Office of Credit Reporting Agencies. (PCI-DSS)

#### PDPA vs GDPR
- There more robust rights granted to data subjects under the GDPR:
  1. Personal data
     - Under Malaysia's PDPA, personal data refers to any information processed in regards to customer-business (commercial) transactions, through which the customer or data subject is identifiable.
     - The GDPR, takes a very similar approach, although it does not have strict rules in place with regards to what classes of information quanlify as *personal data*.
     - Both regulations focus on the data subject's identification potential or 'identifiability' in order to determine whether the information provided would quanlify as personal data.
     - However, in case GDPR, any kind of personal data provided is automatically processed and kept in a filling system. Furthermore, GDPR's applicable laws are not limited to commercial transactions only.
  3. Right to be forgotten
     - Under EU's GDPR, data subjects can exercise their rights to have businesses erase their personal information under specific circumstances - one of them being where they wish to withdraw consent on which the data processing was originally based.
     - Another one being where the business no longer has any legal grounds or justification for processing personal data.
     - With Malaysia PDPA, there is no equivalent provision.
     - Under section 10, businesses can no longer keep their data subjects' data for "longer than necessary". This is in stark contrast with Article 17 of GDPR which states that data subjects can object to the processing of personal data and that the business in question has a maximum of 30 days to respond to such a request.
  4. Right to data portability
     - Under GDPR, there is a *right to data portability*, which allows data subjects to request their personal data in a structured, commonly used and machine-readable format.
     - There is no such provision in Malaysian PDPA laws. Even though data subjects do have a right to access personal data, businesses are required to provide the personal data in documentary form as per the Personal Data Protection Regulations of 2014.
     - If data subjects do not find it practical to view their personal data in documentary form, then businesses must provide it in an alternative form, which is both in an understandable format and acceptable to the business.
     - There is also no explicit right to transfer personal data to another business under PDPA - however, such a right way may not be required as data subjects have the option to voluntarily have their data transferred to other businesses.
  5. Privacy by design
     - Under GDPR laws, data controllers must implement technical and organizational measures in order to uphold data protection principles which include minimal use of personal data on a `need to process` basic only. This needs to be done at the data processing stage and again when the processing method is determined.
     - By default, controllers are only allowed to process personal data for which the purpose has been already established, with all underlying systems handling personal data to be designed with privacy in mind.
     - The Malaysian PDPA laws do not have any such provision in place and neither do they explicitly state that the systems must be built primarily with privacy in mind.
  7. DPOs (Data Protection Officers)
     - Data Protection Officers under GDPR regulation are required to have full knowledge of personal data protection laws.
     - Their contact details need to be given to the appropriate data protection supervisory authority and they must have adequate resources at their disposal to fulfil day-to-day duties and maintain technical knowledge.
     - Furthermore, DPOs are also required to report to the highest management within their respective organizations and perform their tasks in full confidence.
     - While undertaking all such tasks, DPOs cannot engage in any tasks which result in conflicts of interest.
     - In case of Malaysia PDPA, DPOs are not explicitly required to have full knowledge of personal data protection laws, even though some knowledge is required in practice, in order to help them perform their jobs diligently.
     - While the Commission recommends every business to register their DPO, there is no legislation around this.
     - Additionally, there is also no legislation around the DPOs performing their tasks in full confidence, avoiding conflicts of interest or reporting to the highest management, as is the case with GDPR.

#### What is IT Compliance
1. IT Compliance is the process of meeting a third party's requirements for digital security with the aim of enabliing business operations in a particular market or with a particular customer.

##### Security 
1. Is practiced for its own sake, not to satisfy a third party's needs.
2. Is driven by the need to protect against constant threats to an organization's assets
3. Is never truly finished and should be continuously maintained and improved.

##### Compliance
1. Is practiced to satisfy external requirements and facilitate business operations.
2. Is driven by business needs rather than technical needs.
3. Is "done" when the third party is satisfied.

#### Benefits of compliance issue
1. Security Compliance Helps You Avoid Fines and Penalties
2. Security Compliance Protects Your Business Reputation
3. Security Compliance Enhances Your Data Management Capabilities
4. Security Compliance Puts You In Good Company
5. Security Compliance Yields Insights That Promote Operational Benefits
6. Effective Security Compliance Enhances Company Culture
7. Security Compliance Supports Access Controls and Accountability

### Task Progress
1. Your IT security project should be broken down into tasks with very clear, specific deliverables, which should be identified through the use of well-crafted completion criteria.
2. Different compliance requirements will have diverse reporting and documentation requirements, so be sure these are in place prior to initiating security project work.
3. It's much easier to document the work you perform and what is required to maintain the requisite level of security.
4. Completion criteria can help to monitor results.

### Project Progress
1. The more often you step back and take a look at where you are, the more successful your project will be.
2. Milestones in your IT security project plan should include, among others, checkpoints on required activities and documentation related to compliance issues.
3. Any external events or activities - hard deadlines for compliance, timelines for external audits, any change on law & regulation
4. Be sure to keep your project sponsor in the loop using the agreed-upon timelines and deliverables for project status reporting.

### Issues Reporting and Resolution
1. Issues may arise that impact your overall network security, and managing these effectively will be fundamental to delivering a successful project result.
2. The criticality of an issue is an assessment of what impact it will have on the task, the schedule, the budget, or the overall project.
3. Keep an eye on your risks and mitigation strategies.
4. Resolving project issues can be complex in some cases and the resolutions may have unintended effects, especially on the overall security of the network.

### Documentation
1. Your standard issue reporting and resolution processes and procedures will work well for a security project plan with one notable exception: documentation.
2. It provides you with an audit trail so that you can go back and see what's been done.
3. It forms the basic of ongoing security operations procedures.
4. It is typically required for compliance audits.
5. Documentation you generate, including the issue reports, could become legal documents should a security breach occur that results in litigation.

#### Example of Information Security Risk and Compliance Project Manager task
1. will be responsible for full project lifecycle project execution specific focus is on project initiation, assessing project scope conducting root cause assessments, identifying issues uncovering process and technology problems.
2. Overall project management and execution of several small to medium and occasionally large sized technical security sponsored initiatives across both IT and non-IT organizations.
3. As a project management position, this role will also be responsible for managing cross functional initiatives across multiple business areas, project managers and/or technical leads.
4. The end goal for this position is to help define, document and streamline initiatives that address immediate tactical threats.
5. Providing effective and clear communications through both leadership level presentations and technical communications (verbal and written).

#### Information Security Risk and Compliance Project Manager job
1. Manages all facets and provides project level leadership for multiple assigned security projects that when implemented will provide an improved risk posture
2. Ensures that project deliverables are met within schedule, budget and quanlity goals, while working with the Project Sponsors to establish overall project objectives and key metrics that are required to meet project goals.
3. Provides ongoing project management oversight for assigned security project while ensuring that the impacted teams clearly understand the desired security goals and benefits.
4. Coordinates and ensures the appropriate resolution of project issues and manages the cross-functional processes for assigned projects; Risk assessment and developement of risk mitigation plans in conjunction with their supervisor for assigned projects.
5. Provides support across functional and organizational boundaries. Communicates with other project team members to ensure a clear understanding of security objectives, policies and requirements.
6. Work with supervisor and/or peers to manage and track requested budget itmes (e.g. hardware, and software implmentations / purchases) through the financial process to achieve project deliverables.
7. Collaborates and builds relationships with key IT, Security and core business partners (e.g. Security Engineering, Global Clearance PMO, IT Security Risk, Legal, IT CAMs, etc.) to enable continued security education and awareness around assigned initiatives and to improve overall relationships.
8. Tracks and provides regular project level metrics that will enable a clear understanding of the status of assigned projects and escalates to their supervisor and appropriate IT security leadership for guidance when adjustments / issues are encountered that pose risk to defined objectives.
9. Meets regularly with key project stakeholders and teams to provide ongoing project level status reporting as requested for the IT Security and IT technical leadership teams.
10. Collaborate and build relationships with IT colleague score business partners and 3rd party service provider's leadership / account teams to enable continued security education and awareness and improve overall relationships.
11. As needed, build clear documentation outlining processes and guidance related to assigned projects.

## Managing IT Security Project Risk
1. Your planning process should include risk assessment, mitigation strategies, evaluation of the risk of mitigation plans, and triggers.
2. In some IT projects, failure to spot these risks early may be a "non-event", but in a security project they usually have more serious implications.

### What is the risk ?
1. Information securtiy risk is the risk of an event or events occurring which result in a business information being lost, stolen, copied or otherwise compromised (a "breach") with adverse legal, regulatory, financial, reputational and / or other consequences for the business.
2. **Definition :** The potential failure to safeguard the business information from unauthorized access, loss or modification which could result in business interruption, legal action, civil and / or criminal liability, fines and reputational damage.

### Impact of not handling the risk
1. Contractual liability
2. Other legal liability and costs
3. Regulatory liability
4. Losst of Future revenue
5. Business disruption
6. Reputational damage

### Assessing the inherent impact of your information security risk
1. Potential regulatory fines
2. The costs of any regulatory investigations and / or court proceedings
3. Loss of existing customers and contracts
4. Internal management time and spend
5. Reputational damage and loss of share value
6. Costs of repairing and enhancing information security infrastructure

### How to asses the inherent probability of your information security risk
1. The nature of your business
2. The nature of the information you hold and why and for whom you hold it.
3. The location(s) of your facilities.
4. The integrity and competence of the personnel and the information security framework of the third parties with whom you work.
5. The scope and quanlity of your cyber security measures.
6. The scope and quanlity of the physical security measures at your facilities.
7. The volume of personal data, especially any sensitive personal data, you process or you ask third parties to process on your behalf.
8. The volume of any other confidential data you hold, whether on behalf yourselves, your employees, clients, suppliers or any other parties.

### Controls that manage your information security risk
1. Adoption of industry standards
2. Appropriate technical & organizational measures
3. Policies and guidance
4. Training and communication
5. Information governance processes
6. Document retention & destruction
7. Inclusion of clauses in commercial contracts
8. Third party due diligence
9. Risk assessment and risk management
10. Incident reporting & response mechanism
11. Whistleblowing 
12. Self certification

### Monitoring to assess the functionality of the controls
1. Continuous monitoring
2. Regular red flag compliance questionnaire
3. Reporting
4. Information security champions
   - Monitoring and reporting on information security training completion.
   - Monitoring of inclusion of compliance training in induction processes.
   - Carrying out surveys / soft audits and informally reporting up of concerns from personnel at ground level.
5. External cyber risk monitoring
6. Regular review

## Managing IT Security Project Change
1. Key stakeholders making new requests (demands) of the project, key staff not being available, new corporate plans that were under wraps are suddenly unveiled - these are the kinds of changes that happen to all projects, including IT security projects.
2. Project change:
   - Key stakeholder
   - Key staff
   - Key environmental

### Key Stakeholder Change (Ways of handling the change request)
1. Standard change management should be employed consistently throughout the project lifecycle.
2. These procedures should include evaluating the requested change, assigning it a level of criticality, and assessing what actions might be taken to address the change.
3. Once it's decided that a change is desirable or acceptable, it must go through the risk evaluation process.
4. You should view all major change as a risk and evaluate it using the same methodologies you use to evaluate other kinds of risk.
5. Think through theses situations very carefully to determine if these changes will support, enhance, or erode security. If thery will not support or enhance security, they should probably not be implemented.
6. Use your functional and technical requirements documents to address major stakeholder change requests.
7. Look over the original specifications and determine whether the stakeholder's change request:
   - Falls under the original specifications
   - Falls outside of the original specifications, but is a desirable modification that will support or enhance security
   - Falls outside of the original specifications, is a reasonable modification, but does not support or enhance security.
   - Falls outside the original specifications, is not a reasonable modification, and may or may not support security.
8. Clearly, having had key stakeholder input from the start of the project should reduce these kinds of change requests, but change always pops up in one form or anohter.

### Key Staff Change
1. Key staff are critical to project success
2. Lack of Availability should haven been identified as a project risk and mitigation strategies should have been identified at the outset of the project.
3. Indentifying your second and third choices for the work
4. Sending someone through training to be the backup.
5. It may also mean that you've identified an outside contractor who could fill that role, if needed.
6. In rare cases, you may have to put that aspect of project work on hold until key person becomes available.

### Key Environmental Change
1. There are times when upper management have plans they're working on that they cannot divulge to anyone, even though they will impact other organizational plans and projects.
2. Another example of an environmental change that could impact your project is if laws or regulations regarding data security in your industry or segment change.
3. Most IT professionals keep an eye these proposed changes but proceed with their project planning work anyway.

## Testing IT Security Project Results
1. Performed some level of testing as part of your assessment and audit process before launching into this project
2. May choose to re-use those testing procedures to test project result
3. Important to remember that regardless of the type of IT security project you're working on, you need to look across all boundaries.
4. Each Individual Security Analysis Programs (ISAPs) results should be tested to ensure that your wireless network or server infrastructure (or whetever you defined as an ISAP) is secured as expected via the security project plan.
5. Through your risk assessment and planning processes, you may have identified some especially high-risk areas that deserve special attention.
6. Testing should encompass many different elements.
7. May also be appropriate to create a separate security project plan devoted solely to testing
8. Testing require an active "push" against security areas to ensure they don't collapse.
9. A thorough testing plan is critical to solid results.

[Back to Top](#chapter-5-project-management)

[Next Chapter](chapter6.md)
[Back to README](README.md)

