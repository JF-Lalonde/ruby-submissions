### Project Template

### [Project Title]

### Pitch

1 sentence that explains the value proposition of the application. How would you explain it to a potential business partner, team member, or investor?
  * I'll be creating a node cluster using Raspberry Pis to run docker containers that will be hosting a node.js backend app, then load stressing the app to demonstrate how Kubernetes can distribute the load to other clusters and even keep the app alive when a container is taken down (offline). 

### Problem

1-3 sentences describing the problem that you are trying to solve.
  * Once an app becomes popular it could be faced with quite a bit of traffic. How an app handles scaling can determine whether or not it will survive, so I want to build my own version of a container cluster to demonstrate their ability to scale an app efficiently when traffic increases significantly.

### Solution

1-3 sentences describing how your application will solve that problem.
  * Using an external load stresser app, I will demonstrate how an app run on multiple containers is able to withstand an influx of traffic, and even persist when one or more containers are taken down.

### Target Audience

1-3 sentences describing what type of user your app would be applicable to.
  * This type of deployment is often reserved for companies that have become large enough to necessitate containerization. I hope to show that with the advent of ultra-cheap computers like the Raspberry Pi even small-scale companies or individual developers can afford to be set up for traffic influx from the get-go.

### New Techniques

Which new techniques are you hoping to implement?
  * Aside from creating a node.js backend, everything will be new. Creating Docker nodes on Raspberry Pis using Hypriot OS, installing Kubernetes as an orchestration service, and finally load-stressing using a third-party will all be new.

### Workflow

What project management tool will you be using to manage your progress?
  * I'll be making cards in Waffle to track progress.
