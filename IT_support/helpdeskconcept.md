
0;115;0c#	Help Desk Workflow

A help desk is a specialized IT team that serves as the central point of contact for employees or customers seeking support. Users can reach the help desk through online reporting tools, live chat, telephone, or shared email accounts that allow all technicians to view and respond to requests.

Help desk technicians often resolve issues quickly. For example, if there's a network outage, users may contact the help desk to ask why they can't access external sites. The technician can inform them of the outage and provide an expected resolution time.

When a support request requires further action, the technician creates a "trouble ticket" using ticketing system software to manage and track the issue. Tickets can be initiated by users via a dashboard or by technicians, with the technician validating and managing the ticket.

Technicians may need to gather additional information by effectively questioning users and actively listening to their responses. They might also investigate devices directly or remotely to replicate and diagnose the problem.

After analyzing the data, the technician will either:

Solve the problem: Once resolved, the technician updates and closes the trouble ticket, enriching the ticketing system database. This helps in quickly resolving similar future issues and allows administrators to identify and address common problems.
Escalate the ticket: If the problem is complex or outside the technician's scope, the ticket is escalated to a more experienced technician. Clear, concise, and accurate documentation is crucial during this process.
The flowchart summarizes a typical trouble ticket process that a help desk technician would have to perform.

Note: Processes can vary depending on the organization.

=============================================
Ticketing workflow
=============================================

																	 -----------------
															/\--No-->|inform user and|
------------------------  ----------------------------     /if\      |remove request |
|User initiates request|->|Help desk captures details|    /the \     _________________
------------------------  |and validates the problem |-->/request\		  ----------------
    					  ----------------------------  /for suppo\--Yes->|help desk crea|
						  								\rt is val/       |tes trouble ti|
														 \id     /        |ckets         |
														  \     /         -------|--------
														   \   /                 |
														    \ /                  |
															                     |
	_____________________________________________________________________________|
	|
	|													 /\-Yes->-------------------
____|___________________   _________________________    /  \    |If solve the user |
|Help desk gathers info|-->|help desk analyzes data|-->/can \   |issues then close |
------------------------   -------------------------  /  the \  | ticket           |
						   							 /technici\ --------------------
													 \ an reso/
													  \lve it/
													   \    /
									___No_______________\  /
									|
				      ______________|________________
					  |escalate the issues to a more|
					  | experienced tech support    |
					  -------------------------------



# Introduction to queue Management

  * Managing a constant flow of incoming support tickets is crucial for keeping customer satifaction high and operations running smoothly. Queue management is the backboone of this process, ensuring that tickets are handled efficiently and in the right order. Imagine a narrow bottleneck in a factory production line. As materials flow through, if the bottlenect isn't managed everything starts to back up, causing delays and chaos, as shown in the figure. Similary, without effective queue management, tickets can pile up, creating confusion and frustration for both technicians and customers.

__________________			 			   __________________________
---> ---> --->    \						  /
				   \    QUEUE            /
---> ----> --->	    ---------------------
	--->   ---> --->  --->  ---> --->  ---> ---> ---> ---> ---> ----> 				
-->			--->	_____________________
---> --> -->	   /					 \
__________________/						  \___________________________


* Queue management starts with prioritizing tickets based on urgency and impact A priority system might be as simple as classifying ticket as low , medium	or high priority. For example, a simple password reset maybe treated as low priority, while a system outage that affects an entire department would be a high priority and demands immediate attention. Medium priority issues are important but do not affect critical functions.

Service Levels Agreements (SLAs) are formal agreements that ouline how quickly a support team must respond to or resolve different types of issues Each tickets needs to be assigned a priority level that affects how quickly it needs to be addressed accordingn to the SLA. Knowing the SLAs and priorities helps technicians determine which ticket to tackle first and ensures that high-priority issues are handled quickly and effectively .

In a well-mannered queue, every ticket is tracked from start to finish. But it's not just about fixing technical problems; it's about managing customer communication and clear communication throughout the process . while a technician works on a ticket, they must also keep customers informed . this involves explaining timelines, providing regular updates, and responding professionally, even in stressful situations. queue management isn't only about	staying organised ; it's  about keeping things running smoothly while ensuring customers  feel heard, understood, and valued.

->Ticket Creating->Techinician Assignment->Customer Communication->Timeline Explaination->Regular Updates->Professional Response->Issue Resolution->Customer Satisfaction-->

Whether you’re prioritizing a critical issue or explaining a delay to an impatient user, mastering queue management will help you navigate the challenges of the help desk world with confidence and professionalism.

========================================
Ticketing Systems
========================================


Most organizations use a ticketing system to manage their ticket queues, ensuring that support is provided in a timely and organized manner. These systems ensure that all tickets are tracked, addressed, and resolved.

Common features of most ticketing systems, whether for small, medium, or enterprise-level organizations including the following:

Ticket Management: Organizing, prioritizing, and resolving issues.
Multi-Channel Support: Handling customer inquiries from email, phone, chat, and social media.
Knowledge Base: Allowing customers to self-serve and find solutions.
Automation: Routing tickets, escalation, and resolving common issues without manual intervention.
Reporting and Analytics: Tracking key performance indicators (KPIs) like resolution time, customer satisfaction, and ticket volume.
Collaboration Tools: Allowing teams to collaborate and communicate internally on tickets.
Note: A quick internet search for “help desk software” reveals many different software vendors including Freshdesk, Zoho Desk, Zendesk, Jira Service Management, ServiceNow, and more.

The figure shows a simplified ticket designed to help you understand what information a help desk ticket could capture.

IT - Ticketing SystemTicket NumberDescriptionReported byDate createdContact infoContact infoContact infoCategoryPriority / SeverityStatusCreated byAssigned toDateDateDateSpecificsSpecificsSpecificsTicket ManagementUpdates


Description  : A free-form field that describes the request

Reported by  : Free-form fields that identify who requested the support

		 	   + A drop-down list for selecting pre-determined categories
			   + This is useful to group related tickets together 
Category     : + For example, New device/App request, employee Onboarding/Termination, su
			   pport, Report a problem, and Security incident.

Priority/Se  : + A drop-down list for selecting pre-determined priority levels
verity		   + For example, high, medium, low, or critical, major, and minor.


Status 		 : + A drop-down list for selecting pre-determined status levels
			   + For example, not started, opened, in progress, completed


Created by/	 : + free form field that identify the technician who created the ticket and
Assiged by	   who the ticket was assigned to if escalation was required


Details date/: + A drop-down list that displays the date the ticket was updated.
and specifics  + A free form field for updating the ticket.



Note: Other fields may also be available, such as platform type and model, operating system version, network connection used, and others.

In the sample ticket, some fields were system generated (in orange), drop-down (in blue), or free-form (in yellow). Drop-down fields make it easier to enter and maintain consistency. The free-form fields are used by the help desk technician to add descriptive information.

Free-form fields will be read by other technicians and managers. Therefore, it is important to use clear and concise written communication. Use plain language and short sentences. Always pay attention to your spelling, grammar, and style.


====================================
SLAs and KPIs in Queue Management
====================================

Service Level Agreements (SLAs) are essential in help desk operations because they set clear expectations for both customers and support teams. An SLA defines the amount of time a help desk team has to respond to and resolve a customer issue based on its priority level. For instance, a high-priority ticket, such as a system outage affecting multiple employees, might require a response within 30 minutes and a resolution within two hours. A lower-priority issue, like a user asking for a software upgrade, may have an SLA of 24 hours for a response and 48 hours for resolution. By establishing these time frames, SLAs help technicians prioritize their workload and ensure that urgent issues are addressed promptly, reducing downtime and customer frustration.

SLAs also provide a way to manage customer expectations. For example, if a customer submits a high-priority ticket, they expect to hear back quickly. Knowing this, a technician can reassure the customer by explaining that their issue is being treated as a priority and a response will be sent within the SLA’s defined time frame. In this way, SLAs are not just about timelines. SLAs are also about clear, transparent communication that builds trust between the help desk and the users they support.

Key Performance Indicators (KPIs) come into play by helping help desk teams measure the efficiency and effectiveness of their ticket management process. KPIs track performance over time, providing valuable data that can guide improvements in service delivery.
