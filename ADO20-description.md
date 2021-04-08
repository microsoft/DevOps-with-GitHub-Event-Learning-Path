# [ADO20] Managing the Flow of Work


### **Abstract:**
DevOps is all about continuously delivering value. Before we can even begin thinking about CI/CD, we need to make sure we do the right work. Sprint after sprint, iteration after iteration, we need to plan our work and manage our workflows. 

This includes planning and tracking all units of work for the project. With frequent small iterations, there is no time to waste. Careful planning needs to happen to ensure the correct work gets done for each iteration. With the compressed time frame for each iteration, team members must work and coordinate their activities. Thus cross (functional) team visibility of work becomes vital for that coordination and allocation of resources. Visibility also ensures problems or bottlenecks get surfaced and addressed quickly. 

Managing source control changes are also important. We need to be in a deployable state at the end of every sprint. The main branch should be protected, yet changes being introduced should not be overly hampered and slowed down by the process. Being able to iterate quickly and safely is vital. 

And Finally, we need automation surrounding all our workflows to help enable everything as well as add consistency in what we do. 

### **Long Description:**

Tailwind Traders has fully committed to the cloud. They have also gone all in on the concepts of DevOps. They've even decided on their tooling stack. And here is where the rubber meets the road. Theory is great, but now it's time to actually implement the DevOps concepts with the tool chain selected. 

In order to continuously deliver value, Tailwind Traders knew they had to have many small and frequent iterations. To be successful in this type of model, they required real-time communication of capacity as well as full transparency of work remaining. They needed to have visual tools that captured every unit of work as well as the ability to track each of these units across their iterations. Based on these criteria, they wanted to implement their agile software development using Kanban with visual Kanban boards. Kanban brings some fantastic benefits. It is a flexible process focused on continuous delivery. Work is visualized on boards clearly showing stalled work, communicating work in progress to stakeholders, identifying improperly scoped work, and calling out expedited work. 

Next, they knew they wanted to move quickly from one iteration to the next with deployments at the end of each iteration. They didn't want the overhead and complexity of maintaining many long term branches so doing trunk-based development was vital. However, they also needed to protect the main branch, keeping main in a deployable state. To truly DevOps at speed, they needed to separate the deployment of code from the releasing of features. And slow-rolling releases of features to their end-users with controlled testing in production was also important. All of this would be implemented using feature flags. 

Finally, they needed automation in place to help enable everything. When issues get filed, notifications need to happen. If someone on the team updates issues, notifications need to happen. To keep quality up, all developer check-ins must go through a pull request. At which point builds should kick off, unit tests should run, and the Tailwind Traders app should be deployed into a staging environment, so not only is the code reviewed, but the application changes are reviewed too. To simplify the PR process, a link to the staging environment should be added as a PR comment. All of these things would be done through automation. 

After doing all of this, Tailwind Traders will be in a pretty good place. They would have adopted the DevOps mindset. They would have picked their tooling. They would have implemented the processes they need with the tooling they picked. The fundamentals of DevOps will now all be in place. 

### **User problem:**

Now that we are working together with shared tooling, how do we as a larger technical team manage our workflow? 

### **Attendee Takeaways:**
* Make work in progress visible with Azure boards. 
* Use trunk-based development to keep integration pain down and master ready to ship. 
* Automate your workflow to add consistency and remove drudgery. 

### **Concepts:**
* Communication and Collaboration 
* Source Control 
* CI 

### **Technology:**
* Microsoft Teams 
* GitHub Repos 
* Azure Boards 
* GitHub Actions 
* Visual Studio Code 

### **Resources:**
* [PowerPoint Resources and speaker notes]()
* [Link to 45 min version of the session as Train-the-Trainer resource]()