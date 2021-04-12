## [ADO50] Operating Software in the Cloud


### **Abstract:**
DevOps doesn't stop when you deploy. Incident response, identity management, and controlling access to production are all part of learning to run software well.

### **Long Description:**

Tailwind Traders has come far in their DevOps journey. They are working as one unit between the development and operations teams – even as they continue to grow. Work in progress is visible across the technical team and decisions are made with more complete information based on the state of that work. Build and release are happening consistently and get better every time there is a problem. We are starting to see some cracks in this story now. One of the senior IT admins, one who provisioned much of the original environment in fact, has moved on to another opportunity. After cleaning up all Azure Active Directory-related artifacts from the former employee, things start to fail. And things are failing catastrophically across their stack. 

Emails go out and channels are notified, but there is not a specific person or group responsible for acting on those alerts. Because of the low-level nature of the failures (authentication failures), it is tough to figure out who is responsible for responding. 

The Tailwind Traders team begins to respond. They put together a small cross-functional team to begin responding to the outage and start to recover. But they don’t want this to happen again. One of the team members suggests defining a role of Designated Responsible Individual for each team. Teams can set up rotations for this role and that person would be responsible for responding to and starting any incident response. They don’t necessarily have to solve everything themselves, but they gather the initial information and can start to pull in additional help as needed. The decide to use the Shifts app in Microsoft Teams to create their DRI schedules. 

Their next course of action is to start removing areas where only individual team members have rights or ownership of infrastructure components or authenticate automation. They use Azure AD Service Principals and Managed Service Identities to provide authentication and access control for their Azure resources. For those services where they cannot use a managed identity or service principal, the team creates calendar reminders or re-occurring tasks to periodically validate/rotate the credentials associated 

Over time, the team finds and reduces the number of places the infrastructure and application depend on individual people. They refine and improve their DRI on-call process and improve their incident response practices. They move many of their regular tasks into Logic Apps and Azure Functions to allow them to execute under the service principals/managed identities and remove user access to production environments. 

### **User problem:** 

How can we operate our software in the cloud more effectively at scale? 

### **Attendee Takeaways:**
* For incidents to be effectively managed, someone needs to be responsible for responding. 
* No magic people or machines! Reduce the dependence on individual user accounts or environments with service principals and managed identities. 
* Use automation to deliver change into the environment – remove manual steps. 

### **Concepts:**
* Security and Compliance 
* Communications and Collaboration 
* CD/Release Management 

### **Technology:**
* Azure AD (Service Principals and Managed Identities) 
* Microsoft Teams (Shifts) 
* Azure Monitor 
* Azure Logic Apps / Azure Functions 

### **Resources:**
* [PowerPoint Resources and speaker notes](https://aka.ms/aaa/devops/slides/ado50)
* [Link to 45 min version of the session as Train-the-Trainer resource](https://aka.ms/aaa/devops/video/ado50)