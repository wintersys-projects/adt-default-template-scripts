
##### [MAIN REPOSITORY](https://github.com/wintersys-projects/adt-build-machine-scripts)

This is a template (in other words, it has no useful function in and of itself) that can be used as a base from which to customise and extend in order to provide useful function.
Useful function might be something like a caching server or a email server or even something like an application server such as Tomcat (although that would require the toolkit to support Java as an application language when it only currently suports PHP). 
It is expected that if other classes of servers are developed such as Caching Servers or Email Servers that they would be added to an appropriate [build chain](https://www.wintersys-projects.uk/Agile%20Deployment%20Toolkit/Development/BuildChainNodes) on the build machine and that cloud-init files would be provided according to the design pattern already followed and explain in the documentation for our [cloud-init](https://www.wintersys-projects.uk/Agile%20Deployment%20Toolkit/Operations/CloudInitWorkflow) process. 

--------------------------------

The Direcrtory Structure of this template repository is as follow:

**${HOME}/cron**  
Scripts related to the functioning of the crontab configuration

**${HOME}/installscripts**  
Scripts related to the installtion of the software that is needed for an autoscaler to operate

**${HOME}/providerscripts**  
Scripts related to 3rd party services

**${HOME}/runtime**  
A directory that is used at runtime to hold information about the state/deployment of the current autoscaler

**${HOME}/security**  
Scripts related to the security of the webserver

**${HOME}/utilities**  
Utility scripts that help with the functioning of the autoscaler



