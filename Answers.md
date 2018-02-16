### Your responses to the short answer questions should be laid out here using markdown.

For help with markdown syntax, [go here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)


1. #### Describe the differences between a Docker container and a virtual machine. What makes a container more aptly-suited for portability?

    It's possible to run multiple containers on the same machine. They also take up less space and they start immediately. Containers package your code and it's dependeces together and make it easily portable. 

    Virtual Machines are heavy duty and contain a full copy of an operating system, multiple apps and it's necessary libraries. They are bulky and slow to start.`
---
2. #### Using the command `docker run -p 49160:8080 -d <your_docker_username>/<your_docker_image_name>`, what does `49160:8080` specify?

    this line of code expresses the action of mapping your port on the container (8080) and the port on your local machine (49160).
---
3. #### What is the main purpose of using a "container orchestration platform" such as Kubernetes or Docker Swarm?

    When your app starts to become so large that you can't manage it yourself, container orchestration platforms like Kubernetes and Docker Swarm help manage and maintain your app.

---
4. #### How do you change the number of replicas in a Kubernetes cluster?



---
5. #### What does it mean to scale a deployed application 'horizontally'? What does it mean to scale 'vertically'?



---
6. #### Heroku also utilizes software containers for deployment. What is the main difference between the 'free' tier of containers on Heroku vs. the paid tiers?



---