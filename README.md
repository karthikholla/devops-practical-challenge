# DevOps Practical challenge

# Goal

Create & deploy a simple NGINX web server using Ansible.

# The Task

You are required to set up a new server in ec2-instance provided. It must:

* Run Nginx
* Deploy the content. This can be as simple as some static text representing a version number, for example:

```
3.0.1
```

or as complex as a full website. You choose.

# Mandatory Work

Fork this repository.

* Create a playbook to install the NGINX. Use a configuration management tool - Ansible. Provide instructions on how to create the server & on deploying the content.
* Provide a script that can be run periodically to check if the server is up and serving the expected content (version number or returning a 200 status code). Use your scripting language of choice.
* Alter the README to contain the document the steps required for the above steps.
* Automate as much as possible.
* Document each step.
* Make it easy to install

Give us access to your fork, and send us an email when you’re done. Feel free to ask questions if anything is unclear, confusing, or just plain missing.

# Extra Credit

We know time is precious, but if you want to give them a go...

* Run Nginx inside a Docker container
* Install Jenkins. Using Jenkinsfile create a Jenkins job to trigger the ansible playbook.

# Worth Knowing/Doing

* Setup Kubernetes & create a simple cluster.

# Questions

#### What scripting languages can I use?

Anyone you like. You’ll have to justify your decision. Please pick something you're familiar with, as you'll need to be able to discuss it. Preferably shell script or python.

#### What will you be grading me on?

Scripting skills, elegance, maintainability, understanding of the technologies you use, security, and in case you missed it....documentation!
We don’t want to know if you can do exactly as asked (or everybody would have the same result). We want to know what you bring to the table when working on a project, what is your secret sauce. More features? Best solution? Thinking outside the box?
Hint: we would like to be able to test this outside of the environment you create, so make it reusable

#### Will I have a chance to explain my choices?

We’ll discuss the choices you made.

#### Why doesn't the test include X?

Good question. Feel free to tell us how to make the test better. Or, you know, fork it and improve it!
