# Penetration Testing Pre Engagement Planning and Regulatory Framework Notes (yes i ran my notes thru chat gpt stfu bitch)

## MITRE ATT&CK Framework

The MITRE ATT&CK framework (https://attack.mitre.org) is an extensive knowledge base used to understand adversary tactics, techniques, and procedures (TTPs). It is widely used by penetration testers, red teamers, bug bounty hunters, incident responders, and threat hunting teams.

The framework is structured as multiple matrices, including:
- Enterprise ATT&CK Matrix  
- Network Matrix  
- Cloud Matrix  
- ICS Matrix  
- Mobile Matrix  

These matrices describe how adversaries:
- Conduct reconnaissance and OSINT gathering
- Exploit systems
- Maintain persistence
- Perform post exploitation activities

It is a foundational reference for mapping real world attacker behavior.

---

## OWASP Web Security Testing Guide (WSTG)

The OWASP Web Security Testing Guide (WSTG) (https://owasp.org/www-project-web-security-testing-guide/) is a comprehensive methodology for web application security testing.

It includes:
- Structured testing phases
- Attack vectors for common vulnerabilities such as:
  - Cross Site Scripting (XSS)
  - XML External Entity (XXE)
  - Cross Site Request Forgery (CSRF)
  - SQL Injection
- Prevention and mitigation guidance

It is considered one of the most detailed web application security testing references available.

---

## NIST SP 800-115

NIST Special Publication 800-115 (https://csrc.nist.gov/publications/detail/sp/800-115/final) provides guidelines for:
- Planning security testing
- Conducting technical security assessments
- Reporting and documenting findings

It replaced NIST SP 800-42 and is widely recognized as an industry standard for penetration testing methodologies.

---

## OSSTMM (Open Source Security Testing Methodology Manual)

The OSSTMM (https://www.isecom.org) is a structured security testing methodology created by ISECOM.

Key sections include:
- Operational Security Metrics
- Trust Analysis
- Workflow processes
- Human Security Testing
- Physical Security Testing
- Wireless Security Testing
- Telecommunications Security Testing
- Data Network Security Testing
- Compliance Regulations
- STAR (Security Test Audit Report)

It focuses on repeatable, measurable security testing.

---

## PTES (Penetration Testing Execution Standard)

The PTES framework (http://www.pentest-standard.org) defines a structured penetration testing lifecycle:

1. Pre engagement interactions  
2. Intelligence gathering  
3. Threat modeling  
4. Vulnerability analysis  
5. Exploitation  
6. Post exploitation  
7. Reporting  

It provides a complete end to end testing structure.

---

## ISSAF (Information Systems Security Assessment Framework)

ISSAF is another structured penetration testing methodology that includes:

- Information gathering  
- Network mapping  
- Vulnerability identification  
- Penetration testing  
- Privilege escalation  
- Enumeration  
- Maintaining access  
- Covering tracks  

It is more granular in attack progression than some other frameworks.

---

## Penetration Testing Lab Environment Concept

A common testing setup includes:
- A Kali Linux or Parrot OS virtual machine
- A vulnerable Windows or Linux target machine
- A virtual switch or host only network

This setup allows:
- Safe exploitation practice
- Packet-level attack simulation
- Isolation from real production networks

---

## Cybersecurity Lab Resources

Omar Santos maintains a cybersecurity resource repository:
- https://h4cker.org/github  
- https://github.com/The-Art-of-Hacking/h4cker/tree/master/build_your_own_lab  

This includes:
- Lab building guides
- Vulnerable applications
- Practice environments
- Security training resources

---

## Importance of Planning and Scoping

Proper planning is critical in penetration testing. Failure to scope correctly can lead to:
- Legal consequences
- Client disputes
- Project failure
- Scope creep

Key planning considerations include:
- Rules of engagement
- Communication paths
- Budget and resources
- Technical constraints
- Legal disclaimers
- Scope definition

---

## Key Planning Elements

A penetration testing engagement must define:

- Target audience
- Rules of engagement
- Communication escalation paths
- Available resources
- Budget
- Disclaimers
- Technical constraints
- Tester resources

---

## Regulatory Compliance Considerations

Penetration testing is often required for compliance with industry regulations.

### PCI DSS
Payment Card Industry Data Security Standard  
https://www.pcisecuritystandards.org  

Focuses on:
- Securing cardholder data
- Mandatory security testing
- Network segmentation
- Encryption requirements

---

### HIPAA
Health Insurance Portability and Accountability Act  
https://www.cdc.gov/phlp/publications/topic/hipaa.html  

Focuses on:
- Protection of electronic health records
- Privacy and security of medical data
- Administrative, physical, and technical safeguards

---

### FedRAMP
Federal Risk and Authorization Management Program  
https://www.fedramp.gov  

Focuses on:
- Cloud service security authorization for U.S. government systems

---

### GDPR
General Data Protection Regulation  
https://gdpr-info.eu  

Focuses on:
- Data privacy rights in the European Union
- Control over personal data
- Data processing transparency

---

### Financial Regulations

Includes:
- Gramm Leach Bliley Act (GLBA)
- FDIC Safeguards Act
- NY DFS Cybersecurity Regulation (23 NYCRR Part 500)
- FFIEC guidelines

These require:
- Periodic penetration testing
- Risk-based security programs
- Protection of customer financial data

---

## Healthcare Security Regulations

Healthcare regulations include:
- HIPAA Security Rule
- HITECH Act
- Breach Notification Rule
- HIPAA Omnibus Rule

These focus on:
- ePHI protection
- Incident response
- Security controls for healthcare systems

---

## PCI DSS Key Concepts

Important PCI DSS definitions:

- Acquirer: Bank handling merchant transactions  
- ASV: Approved scanning vendor  
- Merchant: Entity accepting card payments  
- PAN: Primary account number (credit card number)  
- Payment Brand: Visa, Mastercard, etc.  
- PFI: PCI forensic investigator  
- QSA: Qualified security assessor  
- Service Provider: Entity handling card data  

---

## Technical Security Requirements in Regulations

### Data Isolation
- Network segmentation
- Isolation of cardholder data environments

### Password Management
- No default credentials
- Strong authentication requirements
- MFA enforcement

### Key Management
Based on NIST SP 800-57:
https://csrc.nist.gov/projects/key-management/key-management-guidelines  

Key principles:
- Secure key generation
- Secure storage
- Secure distribution
- Secure destruction
- Protection from unauthorized access

---

## Legal and Local Restrictions

Penetration testers must consider:
- Country-specific laws
- Export controls (Wassenaar Arrangement)
- Computer misuse laws
- Client authorization requirements

Failure to comply can result in:
- Criminal liability
- Civil lawsuits
- Contract termination

---

## Contractual Agreements in Penetration Testing

### Service Level Agreement (SLA)
Defines:
- Performance expectations
- Timeline constraints
- Quality requirements

---

### Statement of Work (SOW)
Defines:
- Scope of testing
- Timeline
- Deliverables
- Payment structure
- Location of work

---

### Master Service Agreement (MSA)
- Long-term contract structure
- Used for repeated engagements
- Reduces renegotiation overhead

---

### Non Disclosure Agreement (NDA)

Types:
- Unilateral NDA
- Bilateral NDA
- Multilateral NDA  

Ensures confidentiality of:
- Findings
- Client data
- Security weaknesses

---

### Contracts

A penetration testing contract defines:
- Scope of work
- Payment terms
- Legal responsibilities
- Authorization for testing

Must be signed by authorized personnel.

---

## Disclaimers in Penetration Testing

Common disclaimers include:
- Testing reflects a point in time
- No guarantee of full security
- Client responsible for remediation
- No warranties or guarantees provided
- Results may not reflect future state

---

## Scope Creep

Scope creep occurs when project scope expands uncontrolled due to:
- Poor change management
- Poor communication
- Poor requirement definition

It can lead to:
- Budget overruns
- Project failure
- Legal disputes

---

## Known vs Unknown Environment Testing

### Unknown Environment (Black Box)
- Limited information provided
- Usually only IPs and domains
- Simulates real attacker behavior

---

### Known Environment (White Box)
- Full access to:
  - Network diagrams
  - Credentials
  - Source code
- Used for deep internal security assessment

---

## Reporting and Communication Considerations

Key questions include:
- Who is the report for?
- What decisions will they make?
- What authority do they have?
- Who receives access?

Communication planning includes:
- Secure file transfer methods (SCP, SFTP)
- Encrypted email (PGP, S/MIME)
- Defined escalation contacts

---

## Budget and ROI Considerations

Clients and testers must consider:
- Cost justification
- Return on investment
- Security value over time
- Compliance requirements

Penetration testing is a point-in-time assessment and does not guarantee permanent security.

---

## Time Management in Penetration Testing

Effective time management improves:
- Productivity
- Coverage of systems
- Vulnerability discovery rate

---

## Additional Security Testing Tools and Documentation

Important resources include:
- SOAP API documentation: https://www.w3.org/TR/soap  
- Swagger/OpenAPI: https://swagger.io  
- OpenAPI Spec: https://github.com/OAI/OpenAPI-Specification  
- WSDL: https://www.w3.org/TR/wsdl20-primer  
- GraphQL: https://graphql.org/learn  
- WADL: https://www.w3.org/Submission/wadl  

---

## SDKs and Tools

SDKs (Software Development Kits) are used to:
- Interact with APIs
- Understand application behavior
- Test system integrations
- Support penetration testing analysis

---

## Scope Definition and Allow/Deny Lists

- Allow list: systems in scope for testing  
- Deny list: systems excluded from testing  

Strict adherence is required to avoid unauthorized access.

---

## Cloud and Third Party Considerations

Penetration testers must consider:
- AWS, Azure, GCP environments
- Hybrid cloud infrastructure
- Third party hosting limitations
- Shared responsibility models

---

## Final Key Principle

Successful penetration testing requires:
- Clear scope definition
- Legal authorization
- Strong communication
- Controlled testing behavior
- Proper reporting and remediation planning
- Compliance with applicable regulations

## 2.2.2 Rules of Engagement

The rules of engagement document specifies the conditions under which the security penetration testing engagement will be conducted. You need to document and agree upon these rule of engagement conditions with the client or an appropriate stakeholder. Table 2-3 lists a few examples of the elements that are typically included in a rules of engagement document.

Table 2-3 - Sample Elements of a Rules of Engagement Document

Gantt charts and work breakdown structures (WBS) can be used as tools to demonstrate and document the timeline. Figure 2-1 shows an example of a basic Gantt chart.

Simple Object Access Protocol (SOAP) project files: SOAP is an API standard that relies on XML and related schemas. XML-based specifications are governed by XML Schema Definition (XSD) documents. Having a good reference of what a specific API supports can be very beneficial for a penetration tester and will accelerate the testing. The SOAP specification can be accessed at https://www.w3.org/TR/soap.

Swagger (OpenAPI) documentation is a modern framework of API documentation and development that is now the basis of the OpenAPI Specification (OAS). These documents are used in representational state transfer (REST) APIs. REST is a software architectural style designed to guide development of the architecture for web services (including APIs). REST, or “RESTful,” APIs are the most common types of APIs used today. Swagger documents can be extremely beneficial when testing APIs. Additional information about Swagger can be obtained at https://swagger.io. The OAS is available at https://github.com/OAI/OpenAPI-Specification.

Web Services Description Language (WSDL) is an XML-based language that is used to document the functionality of a web service. The WSDL specification can be accessed at https://www.w3.org/TR/wsdl20-primer.

GraphQL is a query language for APIs. It is also a server-side runtime for executing queries using a type system you define for your data. Additional technical information about GraphQL can be accessed at https://graphql.org/learn.

Web Application Description Language (WADL) is an XML-based language for describing web applications. The WADL specification can be obtained from https://www.w3.org/Submission/wadl.

An SDK, or devkit, is a collection of software development tools that can be used to interact and deploy a software framework, an operating system, or a hardware platform. SDKs can also help pen testers understand certain specialized applications and hardware platforms within the organization being tested.

Some organizations may allow you to obtain access to the source code of applications to be tested.

In most cases, you will be able to reveal context by using web application testing tools such as proxies like the Burp Suite and the OWASP Zed Attack Proxy (ZAP). You will learn more about these tools in Module 6, “Exploiting Application-Based Vulnerabilities,” and Module 10, “Tools and Code Analysis.”

These documents can be very beneficial for penetration testers, and they can be used to document and define what systems are in scope during the testing.

It is very important to document the physical location where the penetration testing will be done, as well as the Domain Name System (DNS) fully qualified domain names (FQDNs) of the applications and assets that are allowed (including any subdomains). You must also agree and understand if you will be allowed to demonstrate how an external attacker could compromise your systems or how an insider could compromise internal assets. This external vs. internal target identification and scope should be clearly documented.

In Module 1, you learned that there are several environmental considerations, such as applications hosted in a public cloud. Understanding the concept of first-party vs. third-party hosted applications is very important. Applications today can not only be hosted in one public cloud (such as AWS, GCP, or Azure) but also in private and hybrid clouds. As a penetration tester, you must become familiar with any restrictions and limitations dictated by any third-party hosting or cloud providers.

Scope creep is a project management term that refers to the uncontrolled growth of a project’s scope. It is also often referred to as kitchen sink syndrome, requirement creep, and function creep. Scope creep can put you out of business. Many security firms suffer from scope creep and are unsuccessful because they have no idea how to identify when the problem starts or how to react to it.

Forms of scope creep are:
- When there is poor change management in the penetration testing engagement.
- When there is ineffective identification of what technical and nontechnical elements will be required for the penetration test.
- When there is poor communication among stakeholders, including your client and your own team.

Scope creep does not always start as a bad situation. For example, a client that is satisfied with the work you are doing in your engagement might ask you to perform additional testing or technical work. Change management and clear communication are crucial to avoid a very uncomfortable and bad situation.

If you initially engaged with your client after a request for proposal (RFP), and additional work is needed that was not part of the RFP or your initial SOW, you should ask for a new SOW to be signed and agreed upon.

API documentation, wireless SSIDs, and system architecture and network topology documents are among the in-scope, or out-of-scope, technical assets that should be noted and documented.

TIP Time management is very important in a penetration testing engagement. Time management is the process of planning and organizing how you divide and allocate your time to complete different tasks during the penetration testing engagement. Failing to manage your time and learn how to prioritize important tasks may damage your effectiveness and cause unnecessary stress. The benefits of time management during a penetration test are enormous and include greater productivity and increased opportunity to find additional vulnerabilities in targeted systems.

Module 9, “Reporting and Communication,” covers penetration testing reports in detail; here we present a few general key points that you need to take into consideration during the preparation phase of your engagement.

Answering the following questions will help discover different characteristics of your target audience:

- What is the entity’s or individual’s need for the report?
- What is the position of the individual who will be the primary recipient of the report within the organization?
- What is the main purpose and goal of the penetration testing engagement and ultimately the purpose of the report?
- What is the individual’s or business unit’s responsibility and authority to make decisions based on your findings?
- Who will the report be addressed to – for example, the information security manager (ISM), chief information security officer (CISO), chief information officer (CIO), chief technical officer (CTO), technical teams, and so on?
- Who will have access to the report, which may contain sensitive information that should be protected, and whether access will be provided on a need-to-know basis?

You should always have good open lines of communication with the clients and the stakeholders that hire you.

You should have proper documentation of answers to the following questions:
- What is the contact information for all relevant stakeholders?
- How will you communicate with the stakeholders?
- How often do you need to interact with the stakeholders?
- Who are the individuals you can contact at any time if an emergency arises?

You should ask for a form of secure bulk data transfer or storage, such as Secure Copy Protocol (SCP) or Secure File Transfer Protocol (SFTP). You should also exchange any Pretty Good Privacy (PGP) keys or Secure/Multipurpose Internet Mail Extensions (S/MIME) keys for encrypted email exchanges.

Questions about budget and return on investment (ROI) may arise from both the client side and the tester sides in penetration testing.

Clients may ask questions like:
- How do I explain the overall cost of penetration testing to my boss?
- Why do we need penetration testing if we have all these security technical and nontechnical controls in place?
- How do I build in penetration testing as a success factor?
- Can I do it myself?
- How do I calculate the ROI for the penetration testing engagement?

At the same time, the tester needs to answer questions like:
- How do I account for all items of the penetration testing engagement to avoid going over budget?
- How do I do pricing?
- How can I clearly show ROI to my client?

The answers to these questions depend on how effective you are at scoping and clearly communicating and understanding all the elements of the penetration testing engagement. Another factor is understanding that penetration testing is a point-in-time assessment. Consider, for example, the timeline illustrated in Figure 2-3.

Figure 2-3 - Point-in-Time Assessment

Time → Now → 1 Year → 2 Years

Pen Test 1:
- 1000 systems
- Vulnerabilities found: 5 Critical, 11 High, 32 Medium, 45 Low

Pen Test 2:
- 1100 systems
- Vulnerabilities found: 3 Critical, 31 High, 10 Medium, 7 Low

Pen Test 3:
- 2200 systems
- Vulnerabilities found: 15 Critical, 22 High, 8 Medium, 15 Low

In this example, three penetration testing engagements occurred over two years at the same company. Each test shows different vulnerability counts even as systems change over time.

This demonstrates that penetration testing alone cannot guarantee long-term security. Clear mitigation strategies, impact analysis, and remediation timelines must be discussed with stakeholders.

When discussing penetration testing strategies, two key terms are used:

## Unknown-Environment Testing
(Black-box testing)

The tester is given very limited information, usually only domain names and IP addresses. The tester behaves like an external attacker with no prior knowledge of the target. Sometimes internal teams are not informed of the exact timing to simulate real-world attacks.

## Known-Environment Testing
(White-box testing)

The tester is given extensive information such as:
- Network diagrams
- IP addresses
- Configurations
- User credentials
- Sometimes source code

This allows deeper and more complete vulnerability discovery.

Time and cost often determine which approach is used. Known-environment testing is more thorough, while unknown-environment testing is more realistic from an attacker perspective.

---

## Create a Pentesting Agreement

### Objectives
In this lab, you will create your own pentesting agreement.

### Background / Scenario
A penetration testing agreement is a legally binding contract between a client and a penetration tester. It defines all terms and conditions of the engagement, including scope, timelines, service level agreements, completion dates, and pricing.

In real-world situations, legal counsel is often involved to ensure proper contract structure.

### Required Resources
- PC or mobile device with internet access

---

## Instructions

### Part 1: Complete a Simple Pentesting Agreement

#### Step 1: Research pentesting agreements and contracts
Search for penetration testing contracts, statements of work, and agreements. Review their structure and sections.

---

#### Step 2: Develop the pentesting agreement

Create your own penetration testing agreement including:

### a. Parties to the agreement
Include:
- Name of client company
- Address of client company
- Contact information of client company
- Name of penetration testing company
- Address of penetration testing company
- Contact information of penetration testing company

---

### b. Scope of work

#### The penetration tester agrees to:
Define responsibilities such as:
- Types of tests to be performed
- Actions taken when vulnerabilities are discovered
- Reporting requirements and deliverables provided to the client

#### The client agrees to:
Define responsibilities such as:
- Providing consent and authorization
- Ensuring backups of critical data
- Providing access and necessary accommodations

---

### c. Timeframe
Define:
- Project start and end dates
- Milestones such as planning, execution, analysis, and reporting phases
- Deadlines for each phase of the engagement

---

### d. Fees, billing, and payment details
Define:
- Payment structure (lump sum or installment-based)
- Payment schedule
- Handling of tools, equipment, and related expenses

---

### e. Termination of contract
Define:
- Conditions for early termination
- Reasons such as non-payment or breach of contract
- Procedures for termination and handling of partial work completed

---

### Step 3: Bonus – Additional Agreement Sections
List additional common clauses such as:
- Warranty
- Disclaimer
- Limitation of liability
- Dispute resolution

---

## Additional Notes

Penetration testing agreements typically include scope, timeline, and payment terms. Personnel names are usually not included, but authorized signatories from management are required. Vulnerabilities are not reported until testing is completed.

Clients may require background checks on testers depending on sensitivity of the environment.

Proper scoping is critical. In acquisition scenarios, penetration testing may be required as part of due diligence. A scope “allow list” defines what is in scope, while a deny list defines what is out of scope. These must always be followed.

If a real attacker is discovered during testing, it must be reported immediately.

Some tools may be restricted due to legal or operational risk.

After scope agreement, testers perform reconnaissance and vulnerability identification. Testing must remain within agreed limits.

All data and reports must be kept confidential.

Failure to follow best practices can result in legal consequences or financial penalties. Many firms carry liability insurance for protection.

---

## Cybersecurity Governance and Risk

A cybersecurity governance program aligns organizational operations with industry frameworks and legal requirements.

Risk tolerance defines how much risk an organization is willing to accept.

Risk management includes:
- Risk assessment
- Risk acceptance
- Risk mitigation
- Continuous monitoring

Risk-taking can be beneficial but must be controlled and aligned with organizational objectives.

---

## Disclaimers

Penetration testing reports typically include disclaimers stating:
- Testing reflects systems at a specific point in time
- New vulnerabilities may exist after testing
- No system is completely secure
- Reports are for informational purposes only
- Clients are responsible for remediation decisions
- No warranties or guarantees are provided
- Systems may not be fully compliant or free of defects
