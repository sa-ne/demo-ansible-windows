# Ansible for Windows demo

This is a simple playbook (and roles) to demo  how Ansible could be used to automate Windows hosts.

The demo has roles that will:

 - Install IIS (Web-Server and Web-Common-Http) Windows Features, create and configure a simple website
 - Download and install gvim (The only editor that anyone needs)
 - Uses Chocolatey to install some sample packages

 There is also a flat playbook for quicker code explaination/reviews