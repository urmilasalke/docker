# Write an Ansible playbook that does the following operation in manage node

1.Configure docker
2.start and enable docker services
3.pull the httpd server image from the docker hub
4.copy the html code in /var/www/html/ directory and start the web server

# Ansible

Ansible is a software tool or platform that provide the simple but powerful automation for cross-platform computer support.Avoid writing script or custom code to deploy and update your apllication.

In Ansible, there are two categories of computers:
1.control node-The control node is the one that runs ansible.
2.managed node-The managed node is any device being managed by the control node.

Ansible works by connecting to nodes(client,server,etc) on a network, and then sending a small programm called an ansible module to that node.Ansible execute these module over the SSH and removes them when finished.The only requirement for this interaction isthat your ansible control node has login access to the manage nodes.SSH key are the most common way to provide access, but other forms of authentication are also supported.

# Docker

Docker provides the ability to package and run an application loosely isolated environment called a container.Docker is an open platform for developing, shipping, and running applications. Docker enables you to separate your applications from your infrastructure so you can deliver software quickly. With Docker, you can manage your infrastructure in the same ways you manage your applications.
