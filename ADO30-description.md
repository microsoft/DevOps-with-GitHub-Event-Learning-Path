# [ADO30] Building in Security and Quality

### **Abstract:**
Security and compliance are core concerns for organizations. Adopting DevOps practices and delivering software faster can increase those concerns. We can take steps to increase security and compliance as part of our DevOps lifecycle. 

### **Long Description:** 

The Tailwind Traders technical team is settling in on their new tooling. Work is moving across their boards and filling them with a sense of accomplishment. Unfortunately, all is not well. There have been several instances where new releases were deployed on vulnerable container images or missing settings. The team’s leadership is also worried that since they are moving at a quicker pace, are they really reviewing their code as thoroughly as possible? Are they sacrificing code quality and defensive coding in the name of cycle time? 

To address these concerns, the team investigates what they can do. Their first step is turn on the security features inside of GitHub. Turning on dependency alerts and code scanning target two serious problems (outdated dependencies and common security practice violations in code) right at the repository level. 

Next, they look at their container registry. By subscribing to Azure Security Center, they can add container scanning to their Azure Container Registry. This helps them ensure that they are keeping current on all the dependencies in the container images. 

Finally, to improve their environment management, they use Azure Resource Manager templates to define their environment and Azure Policy to help ensure that Azure Security Center is enabled and other important environmental concerns are managed (like only allowing inbound HTTPS traffic). These policies and templates are defined in code, kept in source control, and deployed by command line automation or CI/CD. 

### **User problem:** 

We can build and develop software more quickly, but misconfiguration and security issues are causing too many problems. 

### **Attendee Takeaways:**
* Shift security left by enabling security at the earliest possible point. 
* Keep your container images current and be aware hidden dangers in base images. 
* Use infrastructure as code and policy as code to provide consistency in environments. 

### **Concepts:**
* Security and Compliance 
* Communication and Collaboration 
* CI 

### **Technology:**
* GitHub Automated Pull Requests for Security Updates 
* GitHub Secret Scanning 
* GitHub Advanced Security 
* Azure Container Registry 
* Azure Security Center 
* Azure Policy 
* Azure Resource Manager Templates 
* Azure Kubernetes Service (LPK) 

### **Resources:**
* [PowerPoint Resources and speaker notes]()
* [Link to 45 min version of the session as Train-the-Trainer resource](https://youtu.be/nxL_40ndJ4I)