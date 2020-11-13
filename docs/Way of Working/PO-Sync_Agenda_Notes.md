# PO-Sync. 
**Topics for PO-Sync. to discuss between PO's**
Agenda and description re PO-Sync see here in Meetings overview:
https://citz.sp.gov.bc.ca/sites/SBC/REG/Projects/MVSM/_layouts/15/DocIdRedir.aspx?ID=S52QENDTEJAE-1724982671-2193 
* If we discuss content, let´s open the roadmap or Epic to discuss the item - and possibly update 
----
Jan 12, 2021
----
1. Jyoti to bring the CM topic again in the PO Sync, action item from Oct 9th meeting
----

Nov 27, 2021
---
1. Roy and Melissa are going to present on different options for staff ability to remove all affiliations

Nov 13, 2021
---
1. Automatic Passcode resets? 
- Staff need the ability to remove all affiliations associated to the account.
   - This is currently a manual process
   - Roy and Melissa will work on that
      - To be reviewed on Nov 27 PO Sync
2. Manage Business Page as Login for Staff.
- Raised by entities as a high priority bug.
- When staff exit entity dashboard or reopen site in another tab they should see staff dashboard.
- If we go straight to the dashboard for staff what about when we add access to other apps? Button to link to staff dashboard from main page?
   - Linda and Sienna to talk to Staff to understand the depth of the problem

----

Nov 6, 2021
----
1. Spike in issue where client affiliates to their legal entity they wants to remove from their own dashboard for another party to manage. 
   - process involves issue being logged by staff, escalated (IT Ops), sent to our team, new passcode generated in CPRD, auth tables updated, response to IT   Ops,IT Ops response to staff then back to the client.
   - Janis has dashboard requirements for moving an entity for staff
   - No client facing option logged
   - Consideration for building solution ideally before additional entity types are added
      - This needs to be added to the roadmap for the next PI
      - Melissa and Linda to work on this and create a ticket for this
1. Quantitative Analytics: With Names coming out we are going to see a significant increase in our user base across the applications. This will lead to more calls to staff for help. I want to ensure we have quantitative analytics so we know the percentage of clients who successfully complete a task in the system vs those who call
   - SRE team should have this in their roadmap for next PI
   - It might not be possible to get this before the Name request go live
1. API technical session - Loren to bring this up
   - Technical session with technical folks of "how legal API works?" was asked by the new company (RBC-OWNR)
   - Loren to share the contact details with Kaine
   - Technical session not being planned till end of this year
1. Vulnerability: SonarQube Security Advisory - Who should own this? 
   - This has been already taken care
1. Automatic refund
   - Verbal timeline 4.5 month, with an earliest start date of mid january
   - Quote is $51,000
      - Not leaning towards paying for this solution in this fiscal. There would be more development cost apart from $50K for building this end to end solution.

----
Oct 30, 2020
----
1. Third Party scan 
   - Scan on annual basis recommended from IDIM
   - Gary perkins from the ministry group has offered to do the scan in $1
   - This is covered in capital fund
   - Which Env: Test or Prod
   - Outage: No outage
   - Timeline: Early Feb
   - Codebase: All the different repos
1. GL Coding 
   - Loren to reach out to Carol for the approval on Monday
1. Automated Refund
   - Deloitte(CAS) to confirm before next Thursday on the timeline
   - We will only require refund for Direct pay. Automated refund only needed for Names flow.
   - A dependency should be cretaed for Relationship team for NR to not allow Direct pay
      - Kaine to create the ticket. BA's to discus the the ticket in the next BA guild
      - Timeline would be end of PI
   - Is there a partial refund scenario ever possible? 
      - Linda to create the research ticket
      - Timeline to get the answer by Monday(Nov 2nd)
   - For all non direct pay scenarios, Manual refund is possible through Finance
1. Search(In general)
   - Entities team to own the search feature as PPR team has already started working on it
   - Work start in Dec
   - Bob wants to stay till PPR is done. 

----
Oct 23, 2020
----
1. PayBC SLA
   - Loren to work on the SLA proposal with Melissa
   - Also, to circulate with other stakeholders like Sinead, Ian A, Ian B
1. Autoamated Refund update
   - Meeting Next week, discussed in Steering committee
   - More news to come on Monday
1. New Release Date for Payment Solution
   - new Release date is Jan 17th
   - UAT Date: Nov 23rd
   - Last Production release is Dec 1st
   - Between Dec 1st and Jan 17th - highlevel plan is to include Journal Voucher, Manage Business Dashboard etc..
   - Dec 7th is the proposed date for NR golive
1. Pro data account features
   - No concerns from anyone
1. 3-Day confirmation period for PAD
   - This will be included in Terms of Use
   - Usually under Canada processing rules, the waiting period is 15 days
1. Financial Risks and control review
   - A third party assessment is required for all the financial tools being built
   - Pay, Authentification, Lear(receipts) would be under assessment
   - Is this a mandate for go-live? - YES
   - Contract to start on Nov 7th
1. Data reset tool - Linda
   - Patrick has this on the roadmap
   - If its done early, QA team would be able to accomodate Automation testing
1. Release timing - Name Request and Relationships - Linda
   - No More users getting added to Beta NR release
1. Discussion on experience: As a premium user I am requesting a name from the new name request system, When I decide to log in with services card and have a new account mid name request, When I have a bad PAD payment, Then I am blocked completely from my transaction and if the below is true Then
   - Login with Non-authenticated user and pay with credit card
1. As a premium user I have logged in with services card and have a bad PAD payment, When I need to clear the payment with the only option of credit card, When CAS is down which affects the invoice and Credit Card payment frequently, Then I am not able to file anything urgent or able to recover my account immediately >>> just flagging this experience for discussion
   - This can happen and might result in bad experience
   - At this point, there is no solution to this. A risk to be raised for below two things and discuss in tri-weekly
      - How do we manage the down payment?
      - How do we cater the client who are in non-payment status?
1. Licensing Agrement for APIGEE..Jennifer to disucss this
   - Jennifer to check with Lisa
   - Check with Ian B for operating budget? - Kaine to action this.
1. Melissa actioned the action item for current process with GRAMS:
   - Current process Link here:
   - Proposed process: 
1. USC Direct(Procured solution to replace GRAMS) will be delayed till June 2021
----
Oct 16, 2020
----
1. Premium Payment, payment calculator - Kaine
2. Possibility of delaying the Name Request release to accomodate Premium payments release
   - General agreement to create the space for the team to have their time by either combining two releases or keeping them apart in January.
3. How ServiceBC reps will do NRs at the counter and how payment will be processed
   - Melissa is going to map out the current process with GRAMS
      - When are we going to meet to discuss? - Next PO Sync
      - Discuss the proposal and figure out the plan
      - This has to be done before NRO shut down
   - Trish is meeting with Crystal (Service BC Manager) to next week 
4. Schedule for staff to return part-time to lab (https://bcdevexchange.org/docs/Return-to-Workplace-Playbook.pdf)
   - Jason to set up discussion with team on this topic separately for the teams
   - Figure out the dependencies before moving to the LAB - Each of the PO's to maange the orientation for their respective team
   - First thing, 8 internal team members can join the home office and LAB space.
5. Ticket for Auto Refund(PayBC) - 
   - PayBC will present the options(time and cost) in the next steering committee, next Thursday
   -  Relationship team(@Melissa) to create a ticket and track the work under that.

----
Oct 9, 2020
----
1. Online Banking design review - decision on the Online Banking flow  ? - Loren
   - DECISION: Relationship team will own the payment design and build for Online banking
   - Kaine/Linda to send the Address future dated transaction to Policy and keep Loren in loop
   - For TO DO list - there is some work required by Entities team. It would to good to have a dependency tickets. Amit/Melissa to create one?
1. Is there any work remaining for embedding change on the project team? - If yes, how should we get there? - Trish/Simona
   - Loren and Kaine to check with BA's
   - Jyoti to brought this again after 3 months
1. NSF discusion with Carol
   - Loren to do some more research 
1. PPR Discussion
   - Approval for funding recieved
   - Couple developer, Nov + Dec
   - Jason + Linda/Sienna + Jyoti
1. Corp Supervisor meeting 
   - In general, all good. Nothing happened
   - Auto Analyze testing are being tested by Thor and Kial
   - Kaine will share the results of testing when its available
1. Sprint Demo share on Youtube - Unlisted. Confirmation required from PO's.
   - Decisison - To share the recorded file with Lab team. No objections
1. Christmas holiday celebration - Linda
   - PO's to discuss with their team if they are willing to come to Sticky Wicket
----
Oct 3, 2020
----
1. NSF changes to be review - Loren
   - Discussion still open to whether the client would be able to access their dashboard at all.

1 Payment calculator review - 4018 - Kaine
   - No concerns for the new wrapper

----
Sep 25, 2020
----
### Standing Agenda:
1. Scope of Release going next
   - incorporation application correction filing
      - OCM tasks for Public should be put on hold. Release date should not change 

### Moving Agenda:
1. Showing account setup with payment methods - Loren
1. Name request cutover action items
   - Jyoti to follow up with Trish/Lorna on the dependency of Socities online with payment around NRO
1. Sharing a recording of our Sprint Review with Dev Exchange for their Youtube channel - Jason
   - No concerns from the PO's. 
   - Jason/Jyoti to work with Ari
1. PPR MHR roadmapping
   - Will out this on hold for next week
1. Long term planning board update - things have changed and we should update our board to put up a realistic picture
   - Jyoti to setup the meetings
1. Idea: More business involvement in our Program Increment
   - Jyoti to plan this out.
1. Idea: Allocate points for Change management activities
   - This might disrupt the planning process as the team has a good average going on
   - Also, it wont be only CM activities but it would be everything apart from Dev which needs to be accounted
----
Sep 18, 2020
----
### Standing Agenda:
1. Scope of Release going next
   - On the 22nd we will put out the one time password authenticator reset (no common component changes required for Entities)

### Moving Agenda:
1. What filings clients will be able to do in person at at Service BC centre - Loren added this to agenda
   - Discussion required to make recommendations to Carol (invite Patty to this for context questions)
   - Loren to follow up with Cameron and Debbie for more detail around job aids
   - Jennifer will look into past experience in a similar situation
1. BCSC Outage this week. The BCSC will be down in production on Sunday, September 27th between 6am – 9am. Do we need a banner message as last time?
   - Covered, we are dealing with it. We have a ticket to do a banner -Loren
1. Do we need to expose(or plan to expose) Name API to other partners in the next quarter(Dec - Oct)? If yes, relationship needs to account some work on Pro data partner.
   - This will likely happen in the Spring


----
Sep 11, 2020
----
### Standing Agenda:
1. Scope of Release going next

### Moving Agenda:
1. Dependency on BCOL for NR go-live or NRO decommision on Jan 15. If there is any dependency, that needs to be scoped in the next PI
   - No Dependency on relationship team
   - Work should be done by NR Core team
1. Moving the last sprint of the year by a week for better outcome
   - All in agreement
1. Corporate search - Who is doing it?. This was discussed before, so we should revisit that and confirm the scope of work for this PI.
   - The ownership needs to be discussed. This isnt the roadmap for next PI(oct - dec). Team to revisit this by end of Dec
   - Jyoti to add this to agenda for Mid dec
1. Budget considerations for upcoming PI
   - This is in PO's radar. Plan which is put in place is considering the budget pressure. 
   - Because of uncertainity, Relationship team might drop Pro data account and Vital stats.
   - PayBC is the priority, so full focus on completing Pay BC requirement
   - For Entity team, there is no implication as of now.
1. Credit Card refund
   - Raised at the Steering committee
   - Next steps are work in progress from CAS. 
   - Amit has chalked out the current process - 4353
   - Whats the SLA on the refund process from PayBC side for Refund? - Loren to check it.
   - @Amit - To draft the the proposed solution to send an automated email notification to CAS and IT OPS. To be reviewed in next PO sync.
      - Who is building this? - Entity Team
      - When? - Next Sprint? Use the notification service
   - @Amit to check with Sumesh on whats the unique transaction number
   - @Melisa to be setup the meeting with Ian B and team to review the support process for IT OPS
   - Keep the ticket 4353 updated with findings

----
Sep 4, 2020
----
### Standing Agenda:
1. Scope of Release going next

### Moving Agenda:
1. Name Request Account Authentification
   - Are we going to do it? - Yes, by Oct 30'ish
   - If yes, which team needs to do what? - It would be mostly core Entity team. Some dependency might be on Relationship team.
   - If no, how are we going to manage the Pilot release to corp supervisor
2. Payment
   - When would we hook up other payment method with Name request payment? this decission is important for lot of things(Onboarding users like BCOL users and Corp supervisor, change impact)
   - Which team needs to do what?
      - Its all based on Auth, so all the features would be part of Oct 30'ish release when Auth piece is done
3. Credit card refund: Any update on this?
   - No update as of now. 
   - Whom to call for support requirement? 
      - Amit/Loren to get the info.
      - Ticket which can be updated with the info - 4353. Ticket updated with action items
      - Loren/Amit to complete the SLA/Email by end of next week
      - Loren/Amit to confirm with IT OPS about current NR( or any) Refund Process. 
   - Loren to follow up with Kevin.
4. Define relationship requirements for Staff Dashboard - 4688
   - Document management research is required. Which tool can be used? Entity team need to own this.
5. IT OPS
   - Linda reached out to Steven Chen. Steven Chen is to create a ZenHub ticket for IT OPS related item
   - BA Guild team to create the Zenhub template for creating above tickets.
   - IT OPS to update the distribution list
   - IT OPS to confirm whether they can take the Passcode reset.

----
Aug 28, 2020
----
### Standing Agenda:
1. Scope of Release going next

### Moving Agenda:
1. 4753(Relationship team asked Entity to do) - Grooming done
1. API Discussion on Sept 28th with PPR stakeholders
   - Pro data account will not be ready for production this PI.
1. CAS/CFS downtime email notifications
   - Linda/Jyoti/Loren/Kaine/ITOPS should be part of the email notification group
   - Loren to follow up to have the above group added for notification
   - For next weekend, we need a notice up on Business Registry page that the payment wont be available till "X" date
   - Create a ticket(Amit/Melissa) for banner update today?
      - Raise this in Tech Release meeting?
      - Banner should be up and Running by Sept 2nd till Sept 8th(6AM)

----
Aug 21, 2020
----
### Standing Agenda:
1. Scope of Release going next - Do we need to look at our upcoming releases(Sep 8th) and see whats the scope? If we are clear then we dont need to.
- Discussed

### Moving Agenda:
1. Loren - Manage business dashboard, will this make it in the PI?
   - We will defer this work on this PI
1. IT Ops Workflow - BA's starting to create the Zenhub tickets for IT OPs - Linda to bring up to discuss with relationship team
   - Steven will open tickets in ZH (except passcode ones), and post in chat if he's away. Linda will talk with him to start the week after next, with BAs covering for next week.
1. Staff dashboard scope - Confirm the requirements by Sept 15th.(4687 - Epic, 4688 - Relationship)
   - Loren bringing this into grooming for the grooming after next
1. Corporate search - when are we doing this? and who is doing this? - This came up during the long term planning for relationship team. Loren to discuss
   - Not currently a part of Entity team's planned work. We will plan for this to be added to roadmap and split between the teams (design/frontend/backend)
   - Entities is bringing corporations over in March and has a dependency on this being done
   - Plan for this in December to be able to build in January
1. Quantitative Analysis across application - when should we prioritize this? Loren to bring up
   - Proposed value of seeing where people stop and potentially identifying issues before reported
   - Review this at the end of the next PI to consider implementing before user numbers get higher
   - Giving this to the SRE team - Kaine to chat with Thor
1. Staff ability to Filter records on Account management screen. Near real names for Basic Account types(ABC Company" "ABC - Company" "ABC Company." all with different emails) - This came up in a meeting with Staff for Loren
   - Talk to designers and make sure it's consistent - Loren and Kaine
   - Respond to what staff is asking for (put in ability to find account name on staff dashboard, for example) - Loren
1. Share the user testing result with the team - Forgot what was this about?
   - updates shared
1. How to execute the upcoming PI's?
   - Remote vs In person?
   -- remote
   - When should we do it? - I propose 3rd week of September
   -- yes
   - Involvement? - Same as last one?
   -- yes
   - Duration? - 4 hrs? so that we can address the Retro
   -- yes
----
Aug 14, 2020
----
### Standing Agenda:
1. Scope of Release going next
### Moving Agenda:
1. Data lake availability to customer. Thor to bring up. Invite Thor for this meeting
   - Approval recieved for creation of project
   - Targetting to have something ready for end of September
1. Manage Business Dashboard - Decission on priority of this work.
   - Thor to break out the story on Monday and Tuesday
   - Idea would be to put some story in scope for the next Sprint and then the remaining in the following sprint
1. Staff Dashboard design
   - Not sure what the topic was to discuss
   - Quick visual whih can be sahred with teh team - mid september(TBD based on Scott availability)
1. Upgrade to Vuetify - Vuetify is undergoing a major version upgrade and our version is being deprecated 
   - Should we wait for Vue 3.0 so that we can be done upgrading all at once?
   - Decision is to wait for Vue 3.0 and put it on the table for next PI discussion
1. Dependency items which needs PO inputs:-
   1. Discuss 3966 - A temp solution was implemented, do we need to revisit this?
      - Ticket updated
   1. 2007 - What work is remaining on URL Structure?
      - Thor and Sumesh to work on the next steps
   1. 2396 - In app notificattions? Where are we going to fit this?
      - After Dec 2020
   1. Update Component component documentation : 3092
      - Ticket closed
1. SBC_Pay doesnt support credit card refund. General discussion on how are we going to manage this? Next steps(dependency?) and risk assessment if we are not able to work get to a solution by Name Request go live.
   - This has been raised in Steering committee and is on the radar of the PO's
   - The idea is to keep pushing and the deadline would be end of Sept
   - If the deadline is not met, team(Entity) woud need to build auto generated notification to a mailbox
   - Kaine to talk to Lorna about the ticket creation
1. Pro Data API meeting co-ordination - Kaine also has another meeting planned for PPR
   - Meeting with Pro data users in September
   - Kaine to share the list of companies who would be interested in interviews
1. GL Code granularity?
   - What level of revenue detail do we need to make decisions/take action?
      - This can be dealyed for few weeks. Thor, Sumesh and Greg are working on the data lake piece and should be ready with something towards the end of this PI to show the team the value of Data lake
      - Thor to connect with Sumesh on the urgency of this item
   - What data do we need to go to the CFS and be reported out by SBC Finance vs data that we keep in the data lake that we can pull ourselves?
   - Note when looking at filings codes 154 for Corporate Online, 157 for Societies Online, 74 for Firms, 27 for Coops and other entities, not considering other products like assets
----
Aug 07, 2020
----
* Meeting Cancelled

----
July 31, 2020
----
* Meeting Cancelled

----
July 24, 2020
----
1. Lab/home team release communications
   - Improve communications for Home team
   - Send the link for our Release PLanning document
   - Send the release communication email to everyone over registry


----
July 17, 2020
----
1. BC Registry Homepage - Review the draft(Loren)
   - Some feedback captured in the meeting:
      - "Go To" looks noisy.
      -  Include Names Request under Modernization Initiative
      -  Registered/Log-In section - doesnt make sense as there are three "Create Accounts" options on the page
1. To prioritize tickets 3092, 2436, 4304  - Linda
   - 3092 --> Can we start the documentation? Amit to check with team to see the progress made so far
   - 2436 --> Ticket closed
   - 4304 --> Thor and Sumesh are handling it
1. Update the Zenhub Roadmap
   - Team to update the Roadmap in next few weeks
1. Use the Friday Meeting for Organizing tickets on the releases.
   - Bring it in the PO Sync as an standing agenda
1. Getting back to work in the LAB
   - This is voluntary

----
July 10, 2020
----
* Authorization for Business in COLIN
   - We are creating a ticket for this and assigning it to Thor
   - Idea: Use the AR code or Password code to affiliate their business to their account
* Manage Business Dashboard:
   - Amit to create a spike ticket and assign it to UI folks()
* Requirements for Search functionality
   - Jyoti to create a ticket and assign it to BA's. This would be research ticket
   - Create an Epic for Staff search
   - Corp staff, Help desk staff needs to be involved
   - requirements need to be handed over to Dev team
   - Should be done by next 2 weeks
* PI Agenda and timings
   -  Invite all the team member
   - Include the team members from Home team and keep them optionals
      - David Roberts, Bob Bowles, Mihai Dinu, Cameron Wulff and Amber Andresen


----
July 03, 2020
----
a. Discuss the PI planning together
   - Have a longer term plan done for Relationship team. @Amit and Jyoti to connect.
   - 
b. PIA/STRA update for BCOMP/release on june 30th - whats outstanding?
   - Nothing is outstanding
   
c. Jyoti, Jennifer and Sandra to work on OKR's and bring more solid plan to the table.

d. Loren to create his Epics in Zenhub

e. Linda, Kaine and Jyoti to update the release board and Epics in Zenhub.
   
----
June 24, 2020
----
1. Combined Retro for Entity and Relationship team
- Lets do it every PI, after the PI, we cna bring in people for last 1 hr and do a combined retro
1. Bring the board at grooming
- Shahriar
1. Celebration
- Different options. 
1. OPS readiness for BCOMP
- Immediate need would be to include everyone on the team
- Tech review across teams on regular basis
- Do more impromptu demos - explain the features in demos
   - Record the session
   - Involve the home team
   - Lunch and learn in the month
- Long term solution- Train the IT OPS
   - Third phase is to train the HOme dev
- Involve all the team members in the email from IT OPS
- Develop a process to indicate the SLA 
- Someone still need to be accountablefor managing this
- Linda to add folks to the email which IT OPS sends us
----
June 19, 2020
----
1. Business Registry Home Page for Coops users
   - Decission was to leave it as is for now. 
   - For CO-OP users, we will wait for staff to see how many questions do they get for CO-OP users?
   - Linda to check with Trish to see the communication plan?
   - Loren to see in future if we can add " If you already have an account, Please login?" below the prominent button "Create BC Resgistry Account". Relationship team already have this in backlog
1. BComp NR Type
   - The dependency ticket wont be needed as relationship doesnt check for NR type
   - This would be there for only few months. Later NR will come in picture
1. Shared business access - Came in relationship PI Planning topic
   - How to provide access to people who are outside your account?
   - Since we are getting away from passcodes. This should be on our radar when Entity starts owning Manage business 
   - There would be epics for "Manage business" dashboard which relationshp team has it in their backlog. One of such epics would be "Search for Premium users"
1. Quality Metrics across team
   - Team to have more room in the team sprints for bugs and tech debt - almost 15% capacity should be reserved for that

----
June 12, 2020
----
1. OPS Support for account affiliation - trainings/documentation?
   - Training IT OPS for managing account affiliation. Not for now, may be sometime in july
   - Cross train LAB OPS team. This needs to be addressed
      - Shahriar has the list of cross train skills required. 
         - This needs to be specific for internal team in terms of OPS training
1. Partner support/status for BC Services Card
   - Service interupptions from PayBC and IDIM needs to be raised
   - How can we ensure PayBC is available on 24th June? - Action item to Loren
1. "Create Account" option not present when user logged in.
   - We need a place to create account option for logged in version?. Amit to create a dependency ticket
   - Do we need this before Go-live?
   - Where should we place the option? From a design standpoint, Loren to check 
1. Entities to upgrade to the latest common components so clients can access transaction history (after the 16th) or a choice of login (BCeID vs BCSC) by the June 29th
   - Relationship team(Amit) to create the dependency ticket for doing this work
   - We need to bring this up in standup.
1. BCOL Fee codes
   - Is there a need to differntiate the system while collecting the fees?
   - {Loren}: Doesn't look like
1. Celebration after june 30th
   - For planing involve Ian, Karla Maria, MRAS team
   - Jyoti and Shahriar to work together and bring up some fresh plans
1. Tri weekly status touch points
   - Odi might leave the project, may be by end of month
   - Risks around managing other filing for BCOMP's - team presented a manual way of doing that. So the risk is mitigated
   - Procurement for APA-G(cloud) has been done, contract signing pending

----
June 05, 2020
----
1. Staff payment as a common payment
   - This can be done after June 30th - Staffs are OK with that.
   - Component should have No Fee, Routing slip number, BCOL payments, help in the payment rim
      - This needs more discussion
      - Do a spike and estimate it
   - Give two weeks of time
   - bring it next to next po sync
1. Payment type for Basic account: Credit card and Online Banking
   - for Online banking, till we get the funds, the transaction wouldnt be mark completed
   - Have regression impact to Entities team
   - Loren to send the recommendations to Kaine and seek feedback.
----
May 29, 2020
----
1. Name for payees for online banking
   - "BC Registries" could be the name used
1. Deadline for dependency ticket #3806
   - Jyoti to talk to Sumesh/Saravan to align the release
1. Staff filings with BCOL payments - BCOL account vs BCOL UserID
   - Linda to do some research on this with Sumesh
   - No rush for June 30th
1. Update on Entities release dates
   - Entity team next two release dates are June 9th and June 17th
1. Staff Dashboard
   - Entity team to start own this in next Program Increment and start doing some design work
----
May 22, 2020
----
1. Linda to bring the proposal for "Static text - help text in the application"
   - Team to continue on the approach as of now and get more user feedback and then decide on the concise approach
1. Quick disucssion around Out of Province Solution
   - Account administrator will have the notary verify the person or have law firm
   - Notary will notarize the document
   - Basic BCeID, Passowrd and one time password on phone will be required for authentification - IDIM needs to sign off on use of Basic BCeID
   - Account flow will take over then - User to upload the affidavit document
   - Staff to Review the document and approve
   - Deadline - 23rd of June if everything gets right
   - Cordinator/user will get an invite from Account administrator and they can use Basic BCeID, Passowrd and one time password to login
1. Flow mapping meeting discussion
   - Involve Amit
1. Direction on documentation of requirements - Choose the right tool
   - Jamstack is another option apart from Microsot team
   - Business as usual for now. We need to bring this up post June
1. Create receipts for all types of payment #3482
- Discussed in the PO sync that the logo will be added in the footer to keep it consistent. Amit to create another ticket for that work which will be taken in the next sprint.

----
May 15, 2020
----
1. What APIs and API docs we will provide partners, when these APIs and docs will be available
   - D&D reached out for "what APIs they have".
   - Partner might have need to different API's.
   - We need to come up with a plan 
   - D&D are expected to meet early June
      - Kaine, Loren, Thor, Sumesh, Linda need to be avalable for the planning event.
   - What does need to plan have:
      - API Names
      - API Documentation
      - What does the API have?
      - When they would be available?
      - How they actually explore the API? Ex: Consoles?
      - Terms of Service
      - When we shutting down the old service, the API service need to be available. Is there any blocker with this?
   - Jyoti to schedule the meeting
1. To discuss how the navigation menu bar changes based upon logged in state.
   - Entity team can decide on the navigation part on the Business Registry page and dont need to have the existing Navigation bar
   - Cameron need to connect with Sumesh on the flow of "Create account" depending upon login state.
1. Getting feedback on strucutre of Sprint review from stakeholders
1. Remote Program Increment planning discussion. How can we do it?
   - Have distributed team co-located in different spaces
      - Entity team in one space
      - Relationship team in one space
      - All others in a different space
   - Co-locate where we can
      - Rest team can be remote
   - All Remote
   Regardless of this, if there is any remote element, we have to consider this:
      - Leverage real time digita tools
         - Real time board which can be used for Program Board, Team board and Risk board - WE DONT HAVE THIS
         - A confrencing software which gives an option of breakout - We have Zoom which we can use
         - Slack --> For any communication across team during breakout - We have this
            - Other option to have Microsoft Teams
      - More planning upfromnt. Team should have their created and Sprint goals defined before the PI planning meeting
      - Detaied Agenda and timeboxed events
         - Have the planning session in June - Epic planning
         - Have the bigger session in July - 2nd week

----
May 08, 2020
----
1. Thor and Sumesh will have a discussion with URL to be used and re-directs and bring to the table for decision to be implemented in next sprint.
   - Kaine is following up with Thor on the same.
1. Jennifer to bring the following topics for discussion
   - Updated Partner Roadmap
      - Jennifer to take a closer look at the old Roadmap and see whats mis-matching between two
   - Risk and action item log
      - Discussed and updated in the meeting
1. Discuss the dependency around BCSC content - #3655
   - Agreement on this from both the team. 
   - Jeremy can update the ticket 3655 with details.
   - Ideal time would be to recieve the updated version by end of the current sprint.
1. Sprint Planning timings
   - Entity team from 8:30-10
   - Relationship team from 10:30 AM - 12 PM

----
May 01, 2020
----
- Discussion about "where do we land" after we have created the account.
   - For MVP, users would land on Business Registry Page.
   - Some visual changes needs to be added by Scott for that
- To go through the BC registry page and gather feedback
   - [Loren]: Anything wrt to BCSC needs to be reviewed by IDIM. ANy new page needs a full review from IDIM
      - Jeremy to share the updated content of BCSC.
   - [Trish]: OPtions like "I have lost my passcode?" and "I have not recieved my consent letter"
   - There is no search functionality built in on Business Registry Page.
- A new business registry page with JAMSTACK implementation and not using the CO-OP page.
   - For now, we will haul the existing CO-OP page
      - Entities team will do the work and push the PR

----
Apr 24, 2020
----
1. Linda to bring the proposal for "Static text - help text in the application"
   - Postponed for 2 weeks
1. To discuss the "Registeries roadmap" with all PO's
   - Sandra, kaine and Loren are going to have an internal discussion and then have a discussion with Carol in the early weeks of May. 
   - We will discuss this topic later in mid may
1. To discuss the ownership of the Manage Business Dashboard in future.
   - Relationship team will own the piece till June and then later Entity team will own that.
   - Thor and Sumesh are working on carving this out from web_auth
   - Setup a meeting for early next week to discuss the missing pieces
1. Business Registry page vs CO-OP page
   - Can Co-OP page be used as Business registry page?
      - Yes it can be, but by end of June
   - Is it easy to use this page for Busienss Registry page?
      - Details will be figured out to by Dev's
   - For now,we will have a button on the Coperative online which can be used for integration test- this is the target for next sprint.
      - Linda to create a ticket for the same
      - Jyoti to book a meeting to discuss both the above topics next week
1. BN Messaging capacity
   - We will have Steven chen to look into this and take help from Kial where needed.

----
Apr, 17, 2020
----
Meeting was cancelled as Loren was not available for this meeting.
   
----
Apr, 09, 2020
----

## To discuss the release cadence process.
#### Problem statement: 
- A) Not enough time for QA’s in the release to complete the test and regression. There is always a rush to complete things in the end.
- B) Technical dependencies between the teams.
- C) Frequent change in actual deployment time of the release results in context switching and communications through multiple channel also takes important time away from Dev’s.
- D) Multiple communications to Staff for multiple release which are happening in parallel.
 
##### Ideas:-
- For problem statement A) Based on the nature of our delivery, most of the features are testable towards the end of sprint. In order to give enough time for QA, we can plan to give some buffer in the release.
- For problem statement B) Start documenting the business communication and technical dependency in the release ticket in ZenHub. This will ensure that everyone knows what the other team is doing and CM will also have a clear picture.
- For problem statement C) To work on a release cadence for both the teams. If we agree on a specific date for a release from both the teams which gives buffer to QA’s as well, then we stick to those timelines no matter if we are done early.
    - Proposal is Tuesday after the Sprint. Gives 4 days buffer for QA’s.
    - Friday and Monday after the Sprint were ruled out because,
    - Wednesday after the Sprint – Team is focussed on Sprint planning and wrapping up the previous left over items
    - Thursday after the Sprint – Doesn’t give enough buffer for our QA team
    - Friday has not been a good day for deploying something towards the end of day and have a fear of not working something over the weekend.
    - Monday – Lot of flex’s. John from QA side is on flex on the Monday after the sprint ends and he usually performs production deployment verification
- For Problem Statement D) If the team agrees on a set release cadence as described in the above point, then the release planning can be done accordingly with the PO’s for all future releases. 
    - Release cadence – Have releases from both the teams on Tuesdays after the sprint. This can be treated as a set date unless anything urgent comes up.

#### Conclusion:
- Agreement to move forward with this plan.
- Jyoti to check the release schedule and adjust the dates as needed.

## To discuss the test automation and DevOps proposal
### Phase 1:
#### Timeline : <>
- Somebody to lead the DevOps work who can drive the value of automation and DevOps through continuous improvements.
- Scrum master and Jyoti to have a workshop(with Dev’s and QA) to come up with a Spike to document the gaps
- Develop the backlog of items which needs to be done
    - Example of this could be:-
        - Create an Epic for this and break out all the stories to cover what would be required to have a fully automated tests in Dev
        - Create an Epic for browser automation test by involving one of the QA person + One Front end dev.
- The minimum which we can do(low hanging fruits) –
    - For any schema changes, can we ask the dev’s to update the Data reset tool to make sure it doesn’t fail?
 
### Phase 2:
#### Timeline: <>
- Start estimating the Devops and Test Automation work
- Size the Browser Automation work
- Size the Automated tests in Dev
- Size the Pipeline work for items to move to test
- Once we have the rough estimation, develop the technical roadmap which shows how we are going to meet our long term goals
- The roadmap would have high level features which we can deliver in the sprint in the next quarter.
- We need to keep aside some bandwidth from Dev’s capacity to keep this going. We would need PO’s buy-in for this.
 
### Long term goals:
- Develop the DevOps skill within the Dev team
- Code coverage using a tool decided by team
- Fully running automated tests in Dev
- Automated Integration tests to move things from Dev to Test
- Have a full proof release deployment strategy
 
### What we are doing now:-
- Refactoring of Data reset tool
- QA Integration test

#### Conclusion:
- Agreement to move forward with this plan.
- Jyoti and SHahriar to move forward with this plan starting with small workshops.

### Email captured at Business Level vs Account level
  #### Short term questions
  - How do we capture those emails? Can the account level email used? 
   - Yes, we do have the emails at account level which can be used.
   - If we are collecting the email(Registered office email) at Incorporation flow, should we send this info to Relationship team(Business Profile level)?
  
  #### Long term questions
  - How do we manage the flow going forward?
   
- A decission was taken to not pursue this item as of now the value this might bring compared to the effort involved is not on the higher side.
 - Start planting these questions in the upcoming user session if possible, otherwise postpone it after BCOMP go-live.

----
Apr, 03, 2020
----
1. Discussion about Business profile: need to make email field as a mandatory input by user. #3080
https://app.zenhub.com/workspaces/entity-5bf2f2164b5806bc2bf60531/issues/bcgov/entity/3080
    - Can we check the data from database to see if the email address from business contact and user profile is same? If yes, it can be prepopulated.
    - Email at the account level is mandatory but not at the business level
    - Action items:
        - Get all the emails for CO-OPs. Loren to check with Steven. Change management needs it as well.
        - BA's to confirm the user flows. Can we reconcile this?
1. Release planning process- technical dependencies between teams.
    - Timing of the release changed where the Dev's was not sure when its going to be deployed.
    - Jyoti to work throguh this process - and work on the alignment of releases between teams.
----
Mar, 26, 2020
----
1. UAT testing for Staff. UAT process was discussed in SOS and there are some inputs required.UAT process is documented here:-  https://github.com/bcgov/entity/blob/master/docs/Way%20of%20Working/UAT-Process.md
    - Recommendation to go forward with : "User testing" for staff
1. Sandra wants to discuss below topics: - For Decision:
   - ROI on prototyping ppr
      - Decission to move forward with this. Financing statement, search, dashboard. These will be wireframes or HTML mockup.
      - Demo for PO's on April 7th
      - Kevin is working on the list of Regulatory changes required in order to start the PPR again in Fiscal year. Probably by end of next month.
   - PPR production content- keep it standing or remove from cluster?
      - This shoud be put down as it takes resources. 
      - Can be done as per team convienence. 
   - Advise needed: before we unplug, what dependencies does we need to consider?
      - No concerns from any other team
   - API specs doc approach
      - During the course of documentation, some resource would be required from Loren and Kaine team.
    - Lessons learnt 
      - Do we need to involve more folks apart from Assets team?
        - Sandra to conduct the lessons learnt within Assets team and circulate the results/outcome to PO's.
1. Loren agree w. Kaine: Business profile: need to make email field as a mandatory input by user. #3080
https://app.zenhub.com/workspaces/entity-5bf2f2164b5806bc2bf60531/issues/bcgov/entity/3080
    - Ticket has been updated.
1. Jyoti to bring up Organizational level changes(if there is anything required)
    - Waldemar and Bryan is going to roll off by end of this month(31st March)
1. Information architecture
    - Proposal to be sent to Linda, Kaine and Thor after Loren reviews it.
    - To be done by Next PO SYNC

----
Mar, 19, 2020
----
1.	Upcoming Dependencies discussion. I don’t have the list of dependencies, so would look up to PO’s to bring anything up where there is a dependency else we can go through what we have from PI planning.
1. Static Text - Help Text in the application - common approach & design
   -  ensuring a consistent design/UI for displaying help text in the application, across all Registry products (other than tool tips),
        - Relationship team overall ownership of UI including help
        - Little study on information structure.(Tools like Jamstack)
        - Linda and team to discuss to comeup with a proposal. Proposal might include - What problem are we trying to solve? and how are we going to solve it? Interactions and help text across teams.
        - Usability testin is an important aspect of providing help information.
        - 2 Weeks from now - 
            - And then discuss with other PO's.
    - ensuring the use of plain language and tone,
    - the process to update/review/approve content is efficient, and
    - we’ve considered what static content will live on the website vs. the application.
1. Formal process for triaging requests between teams
    - Remote working - this is working well
    - Scrum Masters to discuss this and take another crack to see what works best for three teams.
1. Updates from myself RE: COBRS discussion and Tech Review
   - Include Ian B in the upcoming meetings
   - Tech Review: Jyoti to run the tech review for few more instances and then see if the frequency needs to be increased.

----
Mar, 13, 2020
----
1. COVID-19 Impact to team's way of working
    1. How do we perform the Sprint review? Remotely?
        - Yes, Jyoti to send the Skype invite.
    1. If anyone is coming back from Vacation(from abroad), as per the recommendation from Government of Canada, its recommended to self-quarintine themselves for 2 weeks and then join work
1. Discuss options for X-PRO Solution. This is for delegate authentification
    1. Social Sign In
    1. One time password
    Loren is working with Thor, Andrew and Sumesh to have the recommendations drafted. This draft has to goto Bev and Carol by EOD today.
1. Discuss notification delivery dependency
    - For Entity, sending the Output and BN number through email after incorporation.
    - Which email are we using? - User Profile, Business contact info?
    - Modify the template which Loren has. The email template has to be updated by Entities team.
    - To have a technical meeting, to udnerstand the notification flow. Jyoti to setup that(Use the Tech Review Meeting. Send the Agenda)
    - Sending the document along with email needs more work from Loren's team
    - Linda/Jyoti to have the flow ready for how are we using the notification?
    - There could be a possibility of "In-App" notification but in the next PI.
1. OXD Research
    - Sandra to put the list of things by Monday EOD to send it to Claire for research work.
    - Loren and Sandra to sync up on this topic.
    - Hours allocated as of now:
        - 55 hours for last week of March
        - 55 hours for first two weeks of April
        - 70 hours for last two weeks of April
            - Loren to confirm the hours.
1. Working Group for Regualtion change
    - Sandra, Bryce, Carol and Kevin met and recommended for a working group for Regulation change
    - Sandra and Kaine to have a chat about engaging different groups.
1. Documentation
    - Use the G-Suite for documentation till the time there is any other recommendation from other team
    - Jyoti to invite Assets team for starting the documentation work.
1. Commom Components 
    - Jyoti has this topic for Tech Review

----
Mar, 09, 2020
----
1. Dependency on common components- From Entities to Relationship
    - If there is an update on common components - there has to be a ticket(dependency) created from Relationship side to let the others team be aware. This is to avoid rework from other teams using those components.
    - There also needs to have some discussion about using these common components in future. From architecture side, Thor was consulted, however DEV’s need to chat about it. Action item is on Jyoti to setup the meeting for Devs.
1. Actions items from Sprint review - if there is anything which we need to action. Jyoti to setup the meeting with Key devs to take up before PI planning
1. Review of the vision document which we are going to present in PI meeting.
    - PO’s to review the Vision document if possible and provide feedback in the PI meeting
1. Review of the Roadmap - There are some changes to the roadmap from Relationship team, so we will quickly go through them.
    - Authentication changed to User Accounts – Since User accounts scope has increased, timelines have been shifted accordingly.
    - Discussion needs to happen around search functionality(Staff search in particular). Kaine/Linda to ask BA’s to figure out the minimum requirement for Staff search for end of Sept(this is considering that COLIN has to be replaced by that time)
    - Jyoti to setup meeting with Thor and Bob for COBRS. There needs to be a plan in order to shut down COBRS.
    - Kaine is taking the charge on CRM/CXM. It needs to span out till end of the year. More discussion in PI planning meeting.
   

----
Feb, 27, 2020
----
1. Loren: 2691 (BC Reg Nav Bar) - recommendation from team not to release it later for user; ready for Entity team this Sprint
    - This was no longer needed to discuss in this meeting
1. User Feedback loop process - trish to present it
    1. The product team will share the wireframes with staff before the release. There is no time in the OCM checkpoint meeting to review the wireframes.
    1. Provide the oppurtunity to Staff of using Test Environment before the release going live.
    1. Trish to work with Business on setting the expectation 
    1. Feedback Loop - Create a bugs and use label as per the team - In OCM Check point
                        - Label them with Feedback label(Client/Staff Feedback - Purple)
                        - Put the ticket in Bug Column
                        - POs to look into bug triage meeting
                        - Trish to go through with Staff on all those Bugs
1. Epic Template
    1. The template was discussed in the meeting and team will create/update all the future epics as per the template.

- Note: There were few dependencies which were not discussed in the meeting as we overrun on time. PO's/SM's to update the agenda as much as possible before the event, so that its easier to facilitate. Jyoti to make sure to check with PO's before the start of the meeting if the Agenda needs to be updated. Priority should be to disucss the dependencies/prioritization followed by other topics.

----
Feb, 20, 2020
----
1. Refine ideas for "API Gateway": 
https://app.zenhub.com/workspaces/entity-5bf2f2164b5806bc2bf60531/issues/bcgov/entity/1088
    - For Assets team(in order to engage with customer), if they want to use the API gateway by end of June they need to publish design by end of March
    - Sandra to invite Thor and Kaine to the next Assets Sprint planning meeting
    - Sandra to invite Thor and Kaine/Loren to Epic planning meeting.
    - First customer user gateway by end of June
1. Force the user to set-up an account when they create a user account (Loren, Trish) - this point come from the discussion and understanding of this story: https://app.zenhub.com/workspaces/entity-5bf2f2164b5806bc2bf60531/issues/bcgov/entity/2689
    - Jyoti will setup a meeting with Sumesh, Severan and Andrew.
    - Bring the estimation topic for Andrew
    - Deadline for this is 28th April
1. URL Disucssion between team
    - bcregistry.gov.bc.ca is approved URL
    - Assets team can use the Co-OP url appended with PPR
    - New process to get the domain. Thor is working with Assets and Relationship team, Already approved by LAB
1. Assets team dependency on Relationship
    - Assets team to sync up with Thor to get this going.
1. On Accounts dashboard, clarify about the dependency on "File Now" option. Is there anything which is needed by entities team?
    - This has been decided. File now button will not be there in banner for now.

#### Decission:
    - All three PO's decided to go with relative estimation i.e. Using Fibonacci

##### Action Items:
    - Sandra to invite Thor and Kaine to the next Assets Sprint planning meeting
    - Sandra to invite Thor and Kaine/Loren to Epic planning meeting.
    - All three SM's to introduce the topic of estimation(Fibonacci) in their next planning meeting. Jyoti to bring this in SoS.
    - Jyoti to setup a meeting with Entities and relationship team on dependency ticket 2689

----
Feb, 13, 2020
----
1. Refine ideas for "API Gateway": 
https://app.zenhub.com/workspaces/entity-5bf2f2164b5806bc2bf60531/issues/bcgov/entity/1088
@Jyoti: invite Thor to that session (see ticket)  - Invited
    - Thor didnt join this meeting, so we will bring it again as part of next PO sync

1. Staff dashboard to manage their work.
    - Shoud be prioritized in next PI planning meeting
    - Some of the things to consider while scoping as part of Next PI planning: Would Name request items be part of this dashboard?

1. Can correction framework be reused for authorizing an account to manage a business(Ex: If a client wants to get the ownership of their business back, they submit a request(using digital form) to Staff)? If yes, then its a dependency on Entities team to do this work for relationship team.
    - Requesting access to Business
    - The same framework can be used, however there is no urgency to build this piece for relationship team
    - When it has to be built : Not prioritized for current quarter

1. Dependencies
    1. **Dependency from Assets to relationship**
        * Redirect for authentification
        * RFC for seeking changes to CI/CD pipeline- feedback is pending. Please ask RFC submitter to follow up with reviewers
    1. **Dependency from Relationship to Entities**
        * BCOL payment scenario in case of failures
    1. **Dependency from Entities to Relationship**
        * Affiliate NR : NR/Entity/Relationship
        * BCOL Error messages
    1. **MRAS and Name Request**
        Check with MRAS team their dependency with BC REg - who is doing this?
        Two workarpunds
        a. 
        b. Once BCOMP incorporates it has to be updated in MRAS
    1. **Credit Card Payments and Name Request**
        * Paybc is offline from Sat 6 to Noon of Sunday
        * Weekend submission of more an issues
        * NR is up on 6AM to 10PM
        * Loren to send the putage timings of PayBC
        * How many Outages are there for PayBC which is unknown
        * There are three projects going together - MRAS, NR and BCOMP, how do we stagger UAT?
        * KArla maria to be aware
    1. **Benefit Company Incorporation and Name Request**
        * Connecting bcol and NRO - After June
        * Use legacy NRO in terms of using CORP/Benefit complanies
        * This may start in one month
        * We need the Stakeholder to be aware
1. Action items:-
    - Loren to send an email to Carol about BN messaging and clarify
    - PO's to check and update the release plan document to reflect the current status
    - Lorna to have her items updated in the Release planning document here
    - Lorna to have all the Epics planned(till end of March) in "Roadmap" section of Zenhub
    - Linda to have a poster in team spaces for Social meet up by end of Feb 12th
    - Linda to talk to operations team for changing some of the criterio for documenting issues(IT Ops)
    - Shahriar to set up a meeting for discussin the dependency ticket 2485
    - Jyoti to post the picture in roclket channel for Name request discussion
    - Lorna to setup a meeting with NRAS(Nisha) to help us answer below
        - Are we delivering XPRO-BC?(Any redirect)
        - What does MRAS redirect?
        - What is available in MRAS test Env?
        - NRO - BComp workaround
    - Loren needs to action on the below
        - Name Request(Pay BC Issues)
        - Carol needs info
        - Stats on Current Outages
        - Impact on Credit card payments because of the Outages
    - Kaine needs to work on Conversion Corp- BC(not priority)
  
        
----
Feb, 6, 2020
----
1. Update on Roadmap in ZenHub
2. Update on Epics across team in ZenHub
3. Any Shift in priorities for the team?
    - Entity team has to pick Correction 1.0 as priority. - DONE
    - Incorporation work needs to be put on hold for now till 1.0 is deployed to production
        - This might move out of June. Needs to be discussed in the upcoming sprint planning meeting.
    - Corrections 2.0 doesnt have to be done necessarily after 1.0
    - Deadline is Feb 28th to deliver Corrections 1.0
    - Relationships needs to re-evaluate the work for current Sprint and next based upon the work which they need to do for Entities.
        - Jeremy might be helping on design stuff - issues created and linked (WS, 2020-02-07)
    - Update the release plan with two releases
        - AGM Picker 
        - Comments field for ledger(corrections 1.0)
        - Corrections 1.0
    - Update OCM - Formal communication might has to be done
4. Any new dependency identifies across teams?
    - Priority filing (dependency from Entity to Relationship)
    - BCOL dependency
        - Needs ticket from Entity team. Currently there is no design
5. How to track items from issues from Actual end users
    - Can we use certain labels for items which involve LAB
    - Can the user group be identified? Like - CO-HO?
5. Update on Action items?
    - Jyoti to create a dependency template in ZenHub - DONE

## Action Items:
-   PO's to create Epics and depdendencies in ZenHub(all what was discussed in PI planning) by end of Feb 12th
-   Linda to have a poster in team spaces for Social meet up by end of Feb 12th
-   Loren to check with Carol on
    - Overall UI ownership
    - BN Messaging
- Linda to talk to operations team for changing some of the criterio for documenting issues(IT Ops)


----
Jan, 30, 2020
----
1.  Follow up on Action item from last 2 week
    - BN Messaging - Loren to follow up with Carol
    - Loren to check with Carol and reflect to the team what does it mean that Relationship team is responsible for overall UI
        - This will be followed up in next sync with Carol(Feb 10th)
2.  Entities dependency on Lorna team to understand what we are getting from NRO, what kind of validation has been done and passed to Entities and what happens when NR status changes mid-flight, how it needs to be handled.
    - Action tasks has been identified for the team.
    - Working with an assumption that users are logged in to do the incorporation.
        - Work flow diagram for Name request flow - BA's can take that responsibilityt. 
        - Jyoti to check with Sumesh if he has any workflow.
3.  Staff dashboard to manage their work - All the three teams are involved but its not decided who will do it
    - Design/research action item on Jeremy. This is currenty the discovery phase. This is on back radar for now.
    - Jyoti will confirm with Scott
    - Jyoti to check with Kaine if this is going to be in Service Now.
4.  Process for identifying dependencies across teams
  
  ## Action Items:
  - Jyoti to create a dependency template in ZenHub - DONE
  - Can we have a informal meet-up at the end of the month? Social meet up 
  
  ## Decisions made:
  - PO's agreed in this meeting to use the Dependency process for this Program Iteration (i.e. nex three Sprints).
----
Jan, 23, 2020
----
1. Discuss abut Business Contact Info - what is the source of truth? Does this info comes from Relationship dashboard and we consume it? or Should we get the information and publish it to Relationship? or Both?
    - Jeremy and Scott agreed that Entities is the currently gettting this information during incorporation and Relationship will ingest it. Relation is currently the record holder. 
    - R will create a task to take this information into their system. This would be a research task
2. Entities team needs to know where/how would the client start the incorporation process(timing in particular? Dependency on Relationship team. Some of the related things are: 
    - What happens when payment is succeful where does the user lands?
    - What happends when payment is unsuccesful? Does user gets Resume or cancel option on the Accounts dashboard
    - How does client resume the flow? from which dashboard?
        - Jeremy has showed the design
        - Scott needs to provide the User Story for Jeremy. User stories would be better. Linda, Scott and Jyoti will provide the requirement in form of user stories
        - Liv will follow up with Scott and Jeremy on the common login
3. BN Messaging decission
    - Carol Direction is to have BN messaging have no duplication of work across teams
    - Calrify with Carol what this is about? - Loren to follow up with Carol(Next week)
4. Impediments regarding EDB - Decisions needed how to best resolve that? Its impacting everyone.
    - I think we briefly touched upon this in PI planning meeting. There is some dollars approved to have EDB folks working on this to stabilize. But we can quickly disucss that.
    - Five days of approval for EDB guys to stabilize the EDB solution. Tendayi's team(Bob/walter) needs to be involved. 
    - SHould we have someone from back office? - David Roberts
    - Thor is the point of contact. 
    - Patrick would be available from R team
    - Richard from K's team
    - Pay this company 30K/year - 24/7 availability.
5. Using Roadmap in ZenHub
    - End of February is the target to have all the teams aligned
    - All the three PO's agree to use this Road map feature
    - Can Asset team use the same repoisotory?
        - W and J to work with Bryce
6. Using Release tag in ZenHub
    - All the three PO's agree to use the Release Tagging feature
    - What kind of naming convention are we going to use for Release across 3 teams? - Jyoti to put some options
7. What does it mean that Relationship team is responsible for UI?
        - Loren to check with Carol and reflect to the team what does it mean for the other team.
8. Follow-up on topics & action items below (last PO-Sync)

## Decisions made:
- Jeremy showed the Navigation structure design to all PO's and there was no concern raised in taking that forward.
https://preview.uxpin.com/ec5725a91e5ed646c9217e6295f9b87b3b6a7bfc#/pages/121718326/simulate/sitemap
- All the three PO's agree to use the Release Tagging feature for any release they are deploying to Production/Market
- All the three PO's agree to use the Road map feature in ZenHub to layout their Epics as per the discussion in the PI planning meeting. The Roadmap needs to be maintained/updated in ZenHub going forward. Any changes to priorities needs to be reflected in ZenHub RoadMap

----
Jan, 16, 2020
----

1. Decisions needed
- IE 11: Do we want to agree to not support IE 11 overall? It means, users will not be able to open a page with IE11. 
    Reason: It breaks stuff
    - Check with OCIO if needed. IAN Bot to check and provide recommendations to PO. 
        - Tendayi reached out ( 16th Jan). Ian Bot is following up with Robert Walker on this
    - Not Priority. It must fails gracefully
    - Talk to Kaine about the priority of defects
    - Stats of bugs - How many? Priority?
    - Can we recommend on the page that latest version of Chrome is supported?
    
- Issues assigned to "Emmanuel" in ZenHub
    - No problem with Kaine's team.
    -  No Action required from Loren team
    - Most of the things are already handled

- Premium Account - How its impacting Asset's team?
    - Tendayi and Loren team discussed this together on 16th Jan. Links for technaical docs were provided to Tendayi's team.
    - BRP will help to solidify this
    - SM to work out a proess to have the dependencies defined in ZenHub
    - How do we document the interfaces/API ? - Nitin working with Jyoti and see the process flow.
        - This can be shown in Sprint Review

- Not eligible for BCSC - How its impacting Asset's team?
    - This is required by May 2020(Production vs Market). Production vs MArket not clear? 
        - Tendayi to check with Carol.
    - This is still relevant for Lorens team to deliver it by May 2020.
        - W to check with Loren if there is any ticket/issue created?
    - Loren might have dependency on IDIM to deliver it by May 2020.
        - Loren to discuss this with Carol(Is this a throw away work if IDIM comes it with own solution)?
        - Loren to book a check in meeting with IDIM
        - Circulate the solution architecture with THor/Sumesh
        - What is the Epic for this item?
