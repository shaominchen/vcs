# vcs
This is a VC Extension developed for vSphere Container Service.

## Installation Instructions

1. Download vcs.war
2. Install Pivotal tc Server:
3. Create a tcserver instance: tcruntime-instance.sh create tcserver
4. Deploy the web application: cp eam/eam-sample.war tcserver/webapps
5. Start tc server: tcruntime-ctl.sh tcserver start
5. Configure storage&networking on the Host for ESX agent deployment
6. Deploy ESX agent & VIB on the portlet UI

## Build Instructions
1. Clone the project
2. Install Apache Ant
3. Run "ant" in vcs folder