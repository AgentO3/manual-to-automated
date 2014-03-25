Manual to Automated Culture
===================

## Building a customer-centric culture through automated deployments 

Building a company to be customer-centric is no easy task. It requires a culture that can move fast to fix problems, develop new features, and collectively listen. 

But, today's deployment processes and cultures have a tendency to slow down responsiveness. Ironically, if we focus excessively on high quality by removing the power of an individual to deploy code to production, the more value we destroy.    

Companies often forget that code that doesn't get to production is technical debt. Why? Because that code gets stale, contention happens, and the value of that code is not delivered to customers. 

The trick of a custer-centric developer culture is to balance the need for quality with the need to get the code into production as fast as possible. 

At VividCortex, we've built up our automated deployment process as part of our culture. Like many, we started with command line scripts and today we enabled every single person in the company to use fully automated deployment through our Chatbot.

The format for this presentation is the following: 

###Command Line for Really Small Teams

*somethign about this is how you learn from command line what needs to be automated*


In the beginning, there was command line tools and everything was good. Then you add a couple more team members. Even though you think command line tools are simple the new team members find them unfamiliar. They are new of course and are in general apprehensive about pushing their changes to production for fear of doing something that brings down the application. So the new team members ask you to deploy or just don’t deploy very often, and you have become the key master for deployments. If you are out that day or unavailable or even worse get hit by a bus then nothing gets deployed. This can be a big problem if you are trying to iterate fast.

###How to Communicate Automation & Customer Centricity (is that a word?)

*how you pick small pieces to automate and how you train your team on these piecs*

So you begin to look for ways to remove yourself as a bottleneck. The first step is to automate those deployments. This is where a tool like Jenkins makes sense. You create jobs in Jenkins to run those existing command line deployment scripts. Jenkins gives you a UI with a button to push to run that deployment script. As a result, those team members which were not deploying before, are now deploying regularly. However not all of them are deploying yet, and you also added another couple of team member, but for some reason they are not deploying anything. When you ask why, they say don’t know how.

So you begin to look for ways to make those commands you automated more accessible and discoverable. You would probably start off with documentation in a wiki. However, you still have a problem of discoverability of the wiki. If your company is like ours then the chatroom is the common area of your company. This is where everyone is communicating in real time. If you make those commands, you automated in Jenkins available in the chatroom then; you have solved, the problem of discoverability and accessibility. This is one of the big ideas behind ChatOps. By putting those tools in the middle of the chat conversation the new team members are learning by seeing the existing team members run those commands. Now new team members are pushing code to production within the first few days, and the existing team members are pushing code to production multiple times a day.

###ShipIt, Even if Its Broken

*more culture, less text*

This is the evolution of deployment at VividCortex. We have a culture of “ShipIt” which means getting your code into production early and often. By using Jenkins and ChatOps, we are making what is considered by many developers to be a scary and confusing process into one that is considered by our team to be ( dare I say ) fun! The rapid pace of iteration delights our stakeholder, early adopters are excited to see new features and having their feedback steer the direction of the product, and our team members find great satisfaction in seeing the fruits of their labor being used by our customers.
