# SCC-Work-Experience


### Senior Automated Systems Analyst: February 2022-Present 
Serve as data analyst specialist responsible for automation and information systems work for the Bureau of Insurance (BOI) in support of insurance regulation
* Specialist for advanced data extraction and analysis via SQL, MS Access, Excel, Power BI and SAP Crystal to gather and organize large and complex data sets
* Lead multiple projects involving analytics, new vendor system implementation, several complex information systems, and provide advanced technical assistance

### Insurance Market Examiner (SCC): June 2018-February 2022  
Serve as a Business Systems Analyst Liaison between the Bureau of Insurance (BOI) and Information Technology Division, assisting Automated Systems’ Chief
* Project Analyst Lead for the largest agent licensing project (fingerprinting implementation) the BOI has undertaken in over 30 years. Implemented all physical, technical, and administrative security safeguards to meet the requirements of the Virginia State Police, FBI and the system developer/vendor. Presented 
MS Power BI dashboard, Excel and PowerPoint to Agent Licensing section to show analytics on demographic report of fingerprint vendor research. 
* Administer new System implementation: Facilitate software developers and line of business throughout each project application development cycle such as collect requirements, vendor research/system design, configuration, implementation, quality assurance testing, security roles etc.

### Associate Insurance Market Examiner (SCC): June 2017-June 2018 
Support all computer-based systems and system related projects / processes utilized within the Bureau of Insurance
* Administer, troubleshoot and improve numerous annual & quarterly system related projects and processes with BOI Staff. Create and implement timelines, train employees, streamline workflows, policies, and procedures. 
* Provide helpdesk support for BOI Staff (200+ employees): Maintain expert knowledge of all computer applications / equipment, security access, SharePoint updates, website changes, etc. 

---

Recent projects and Commission involvement include but are not limited to:
* [Agent Licensing Legislation](https://github.com/bryce-bowles/SCC-Work-Experience#agent-licensing-legislation)
* [Advanced Report and Data Extraction](https://github.com/bryce-bowles/SCC-Work-Experience#advanced-report-and-data-extraction)
* [SendGrid System Implementation](https://github.com/bryce-bowles/SCC-Work-Experience#sendgrid-system-implementation)
* Balance Billing Arbitration
* Annual Company Licensing Renewal
* Working Group Meetings

Work involves using a variety of data analysis and organizational tools, supporting several complex automated systems, and providing advanced technical assistance.  Work is performed with latitude for the exercise of independent judgment and decision making. Work is reviewed through conferences and evaluation of results.


---

*Italicized font are comments from Manager*

## Agent Licensing Legislation

*In response to new agent licensing laws, agents currently licensed and those applying for a license are required to be fingerprinted.  In addition, a new renewal process requires agents to renew their licenses based on their birth month/year.  To enable these new laws, Bryce has been working with the Agent Regulation division since 2018 and continues today.  Bryce used Microsoft Power BI to perform an analysis to determine (1) how far agents would need to travel to fingerprint locations (2) whether there would be enough locations in the state to handle fingerprinting and (3) could the locations identified handle a high volume of agents. He presented his analysis to the agent licensing section and the Deputy Commissioner of Agent Regulation. The data was used in the statement of work that was used to obtain a vendor for fingerprinting.  Using Excel, Bryce performed a detail analysis to determine the volume of renewals (30 days versus 90 days).   With his knowledge of the Sircon system and the data elements involved in his analysis, he was able to work with the Bureau’s vendor (Vertafore) to develop SQL to identify agent renewals based on their birth month/year.  This was necessary for Vertafore to develop the communication method in the Sircon system.  Beginning every month starting in January 2022, two communication methods are sent to agents regarding their renewal. One is through e-mail and the other through U.S. postal.  Bryce reviewed and researched areas of the Invitation For Bid (IFB) that helped to determine the vendor used for mailing customized monthly and annual notices.  These new processes have required Bryce to work with the Agent Regulation division, the Deputy Commissioner of that division, the SCC’s Office of the Commission Comptroller, the fingerprint vendor, the state police and the vendor used for paper mailings. The process has required Bryce to be meticulous with his analysis of ensuring the correct data (agent e-mail, birthdate and renewal date) is pulled from Sircon to enable this new renewal process.*

I was the primary analyst lead (specifically for the fingerprinting, analytics and renewal notice processes) of the largest agent licensing project the BOI has undertaken in over 30 years. In 2018 the Bureau introduced legislation to:  eliminate the CPCU/CLU licensing exam waiver/exemption; eliminate the continuing education (CE) waiver/exemption; require birth-month/year renewals; and require fingerprinting for resident applicants. I have been the primary lead for the fingerprinting portion, statistics for birth-month/year renewals and played a large role in setting up communication methods for renewal and termination notices. Legislation changes started in January of 2022, implementation is complete, procedures were created and shared and issues/maintenance are ongoing. 

When the Bureau was selecting a fingerprint vendor, I conducted research on the overall fingerprint process, location, fees/cost, and administrative system for results tracking. To determine if the vendor fulfilled the location requirements, I used Microsoft Power BI to complete a comparison of ArcGIS geospatial analysis to determine if the fingerprint vendors had the capacity to fulfil requirements within the legislation for distance (no more than 50 miles from agents’ home addres to the fingerprint location as well as a comparrison to the distance of the nearest exam test center) and volume (analysis to compare census population and estimated renewals expected/month for locations). I made calculations to determine approximately 8,500-11,000 fingerprints will need to be taken per year. To determine renewal volume, data was extracted (via SQL), preprocessed/sliced/cleaned and visualized (histograms) to compare volume of each 30- and 90-day reminder notices (9,000-12,000 total will be sent per month including termination notices). The SQL script was then used as a dynamic source of data (ad hoc report) to determine shifts in volume as agents renew and is run as needed by the Chief of Agent Regulation. Analysis (MS Power BI dashboard analysis, Excel and PowerPoint) was presented to the Agent Licensing section and Deputy Commissioner of Agent Regulation to show analytics on demographic report of fingerprint vendor research. The SOW (statement of work) included this effort which ultimately led to vendor selection. Being the liaison, I implemented all physical, technical, and administrative security safeguards to meet the requirements of the Virginia State Police, FBI and the fingerprint vendor/system developer.   
	
I then coordinated with Vertafore (vendor for Sircon system), the agent licensing section, the SCC’s Office of the Commission Comptroller and Data Integrators (our print/postal vendor) to setup email and mailing communication for multiple notice types. I reviewed and edited information within the SCC’s Invitation for Bid (IFB) to select a print vendor, directed implementation with the selected print vendor and am improving the process while creating internal procedures. Once the process was solidified, I trained Automated Systems’ staff on how to complete each month (until January 2024). Each month, careful facilitation is needed to generate, receive the files, confirm they are correct, provide to print vendor, validate letter proofs and follow up to confirm they have been sent. Mailings began, ongoing issues are assessed as needed (such as template configuration, SFTP move-it script changes, box.com setup for file transfer) and improvements of the process are underway.


## Advanced Report and Data Extraction 

My role in running advanced reports and data extraction concepts amplified due to the increased need of emailing and other needed statistics. I completed analytics and advanced reports / data extraction via SQL, MS Access/Excel and SAP Crystal to gather and organize large and complex data sets. To collect contact mailing requirements data, I’ve created a Excel form for the Bureau to use that specifies the fields and metadata available to select for mailing data pulls.  

To be able to pull accurate information from the database, I worked with Vertafore to create new contacts with reliable email data for electronic communication. Using data extraction techniques (data preparation, slicing, aggregating, null values, outliers etc.), I comprised two new company contact types (Government Relations and Company renewal) by pulling data from other contacts and multiple databases (such as Oracle DB1 and NAIC “quicklink”). Vertafore then created the new contact types with this data. Once Vertafore loaded the data, I did quality assurance testing to verify they were loaded into UAT and production environments. Since the new contacts are in the system, Automated Systems has enabled companies to be able to update the contacts themselves through the company address change portal. This is essentual to ensure the contacts are always updated and this has now allowed other users to be able to pull the contacts via a Sircon inquiry without having to complete the steps they otherwise would have (advanced SQL to join queries and use data aggregation techniques from multiple sources) to derive the contacts for mailings, company renewals and other uses.  

Other examples of scenarios I’ve pulled custom data reports and SQL queries include but are not limited to: SLB assessment missing forms notices, active & licensed surplus lines brokers, count of individual licensee expiration per month per year, closed ecases, PIN contacts with PIN numbers, uninsured motorist follow up letter recipients, etc. (cases vary by requests received)

I volunteered to become part of a pilot group to do quality assurance (QA) testing with the NAIC’s new cloud database connection, Snowflake. I have completed initial training and am scheduled to meet with the NAIC to discuss the new connection. Security access for Bureau users is currently being discussed. After QA testing, I will play a major role in adapting our current functions over to this system and train the Bureau how to use it.

## SendGrid System Implementation

*As a component of the Bureau’s Modernization Project, Bryce is working on a project with me and the Policy Compliance section to replace paper mailings with e-mails.  He successfully requested software (SendGrid) through a justification memo to the SCC’s ITD Procurement, that will eliminate the need to send out hundreds of thousands of paper mailings.  He selected the appropriate SendGrid plan by researching the plans available based on the Bureau’s needs.   He has coordinated and participated in meetings with the representatives of SendGrid and the SCC’s ITD to get this software up and running for the Bureau.   Bryce has developed a form for the divisions to use when requesting mailings.   He has worked with Vertafore to get a new company type of ‘Government Relations on the Bureau’s address portal.  These new contacts contained necessary e-mail addresses needed for electronic correspondence. His knowledge of company types and lines of insurance are invaluable as he accurately pulled the required contact information for the mailing either from Sircon or the NAIC Data Warehouse.  This new process will save the Bureau thousands of dollars.*  

The Bureau had a need to purchase a mass electronic communication system to have the ability to send out thousands of emails as it is less time consuming, more cost effective and more reliable than paper mailings. The Bureau spent approximately $221,601.75 (598,197 physical paper mailings) in FY2021. With companies, agencies, and individuals working from home, it’s increasingly important the Bureau adapts to the system infrastructure needed to deliver mass emails on important notice information. I analyzed post mailing costs to determine FY20 and 21 combined cost the Bureau approximately $328,565.30 whereas emailing would have cost $6,364 and tens if not hundreds of man hours pulling, putting together and mailing that information. The SCC’s Information of Technology Division (ITD) has an existing contract with an email vendor, SendGrid. I worked with individuals from the SCC (Clerk's Office, BOI-PCA, BOI-AS and ITD) to assess the above need for BOI to purchase its own SendGrid account. I was the primary analyst to research SendGrid and determined they could fulfil our requirements. Once it was agreed upon, I chose an appropriate subscription plan to purchase based on our projected demand volume. I then composed and submitted the justification memo to SCC's ITD. I initiated many meetings with multiple parties from SendGrid to coordinate the purchase of the web-based software account. Complications increased when setting up configuration, so I facilitated numerous meetings with ITD and multiple different SendGrid teams to configure the domain, confirm the IP address, update the new hostname and validate the CNAME records with VITA. Currently, I am in the process of vetting account verification with the SCC's Office of Commission Comptroller (Procurement), BOI office managers and the SendGrid representatives. Once this is complete extensive quality assurance testing will be done with multiple different batch emails and data extraction to verify the accuracy and success rate of the new system. Statistics will be recorded and analyzed as emails are sent out. When we have requests for unique reports or mailings, it is my job to pull the data and validate we are providing the correct information. When SendGrid is up and running, data will need to be collected for each mass email we do (as I do now).



## Balance Billing Arbitration

*Bryce is currently working on a balance billing project with the Bureau’s Policy and Compliance section, specifically the arbitrator lists.  If an insurer and an out-of-network provider cannot agree on the payment amount for the service by the end of the good faith negotiation period, one of the parties can request that the dispute be settled through arbitration. If they cannot decide on an arbitrator (from our website list), the Bureau will provide a narrowed list.  Bryce is working on improving and enhancing the way the list is narrowed.  With variables that are constantly changing (such as Fee Single Claim Dispute, Total Fee - Bundled Claim Dispute etc.), the list needs narrowing by allowing one of the parties to choose 5 fair, random arbitrators they can pick from.  He is using an algebraic optimization model with logical constraints to “bucket” the full list into 5 groups of similar price.  This will allow the random selection of one from each bucket to provide a total of 5 equally random and fair arbitrators to the network provider and insurer to pick from. Streamlining this process with a dynamic model will be more efficient, fair and accurate.  Bryce is currently in the process of building out the constraints and algebraic formulations needed to create the model in Excel.* 

The Bureau administered a new law that facilitated balance billing of consumers for emergency and non-emergency ancillary services at an in-network facility. As described on our website - “If the insurer and out-of-network provider cannot agree on the payment amount for the service by the end of the good faith negotiation period, one of the parties can request that the dispute be settled through arbitration.” (scc.virginia.gov) In the event that each insurer and out-of-network provider cannot agree to an arbitrator on our arbitrator search system, the Bureau will provide a narrowed list for insurers and out-of-network providers to choose. The PCA division has pursued my direct involvement to enhance efficiency and reliability on the methods used to create a fair opportunity for insurers and out-of-network providers. Due to arbitrators updating the list so much (Fee Single Claim Dispute, Total Fee - Bundled Claim Dispute etc.), there is a need to create a dynamic system to increase efficiency. Five fair, random arbitrators will be chosen for insurers and the out-of-network providers to pick from. I am in the process of creating an algebraic optimization model with logical constraints to “bucket” the full list into 5 groups of similar prices. Since the list changes dynamically, I’ve been asked to create a model that will then randomly select one from each bucket, enabling the insurer and out-of-network provider to be able to have a choice of 5 equally random and fair arbitrators. I am in the process of collecting the data, writing the objective, creating the algebraic formulation, forming the decision variables and building out the model. Meetings are scheduled to go over progress. Extensive testing will be needed to ensure the model is fair and accurate before implementing use to serve the insurers and out-of-network providers. 


## Annual Company Licensing Renewal

*Bryce has also led the annual Company Licensing Renewal process.  This process lasted approximately 4 months.  He planned and organized this process from start to finish and met the December deadline to send out company licensing renewal notices to over 2,000 insurers.    Bryce coordinated this annual process with the Financial Regulation Division and the Information and Technology Division. His actions involve setting-up the kick-off meeting with all parties, reviewing tasks and due dates for each team members.  Through follow-up meetings, Bryce gathered language for the renewal letters/e-mails, revised webpages and portal language in accordance with the team’s recommendations.  He created and posted meeting minutes to SharePoint.  Bryce generated reports for FRD managers to ensure past due forms would not display on the portal.  He also updated Adobe interactive forms for posting to the website.  He used SharePoint to track the progress of this process.  Bryce also rewrote the procedures for this annual process.*  


In 2020, the Company Licensing Renewal overcame a monumental shift from paper mailings to emailing. I lead and directed this change into place by extracting reliable contact emails from multiple data sources (Vertafore and NAIC) and multiple contact types while ensuring the renewal reminders were delivered in a timely manner to the best suited recipients of over 2,000 companies. It being the first time this had been done, this was a major milestone to increase efficiency and accuracy to deliver the information. Over the course of about 4 months, I planned, facilitated, revised and acted as a project manager to guarantee the project was on time and well communicated; documenting all steps and improvements along the way with detailed procedures while receiving positive feedback about the project from all parties (Financial Regulation Division - FRD, ITD and Automated Systems). The process includes creating a detailed timeline/plan, managing and assigning roles of over 10 individuals, confirming descriptive statistics of renewal counts per company type, template replacements, text/FAQ website updates, portal revisions, invoice allocation, missing forms report running, emailing the letters etc. I also created a company type form matrix that indicates which FRD analyst is assigned to which company type, which renewal template corresponds to which company type and the preferred contact type for each company type. This highly reorganized and documented process benefits Automated Systems Analysts as they will need to lead the project in future years. Every year, it will be important to validate the email contact recipients to the corresponding Companies needing Licensing Renewal reminders. 


## Working Group Meetings

I was a member of many working group meetings for the Bureau. As Automated System’s captain of Vertafore’s SIRC revenue & taxes committee, company committee and SIRC Information Technology (IT) committee I attended monthly meetings with Vertafore, discussing issues, updates etc. and report back to the business’ sections the solutions/next steps. I took and sent out monthly meeting minutes as well as correspond with applicable sections’ relevant updates from the release note enhancements while resolving any issues relating to updates. In 2019, I was the captain of the consumer services SIRC committee and facilitated a major update to its new user interface. This required numerous meetings with Vertafore and BOI’s consumer services section to perform as a liaison for system implementation, Quality Assurance (QA) testing, verify advanced system updates operated properly and consult issues reported. In January of 2021, I was reassigned to the revenue and company module, also needing new interface updates. 

Vertafore is soon requiring the use of multi factor authentication (due to highly sensitive information) to login. I have been assigned lead of this project which requires attending the SIRC IT committee meetings, researching and understanding two factor methods to coordinate with the SCC’s Office of Information Security (OIS) and determine the best option we can implement for our users. Initial meetings with Vertafore and OIS have taken place, timelines are being created and there will be more discussion during our IT committee March call. 

I regularly attend the Medigap project meetings to be able to understand the tool and implementation. Once the tool is complete, I will have the role of creating analytics on the data that is derived from the tool for Life and Health (LH) Market Conduct. SQL scripts will be created to extract the data and there are needs for Microsoft Power BI dashboards to visualize needed insights. 

In 2020, I created a new workflow for LH Rates & Forms and Automated Systems to decrease the amount of time it takes to create and convert LH Checklist Forms for very time
sensitive Affordable Care Act information. I consulted previous year’s issues by using MS Visio to visualize a new workflow process involving SharePoint, Adobe Acrobat Pro and Kentico. I held meetings with Automated Systems and LH to receive feedback, improve the process and create a new systematic labeling workflow system within SharePoint to ensure time was minimized to make/update the fillable forms place on the website. The clearly conducted procedures needed minimum updates to use for this years’ checklist updates and very positive feedback and satisfaction was received by all parties.  
