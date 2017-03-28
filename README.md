# VCS
This is a VC Extension developed for vSphere Container Service.

## Installation Instructions
1. Download vcs.war
2. Install Pivotal tc Server:
3. Create a tcserver instance: tcruntime-instance.sh create tcserver
4. Deploy the web application: cp eam/eam-sample.war tcserver/webapps, extract the war
5. Modify tcserver/webapps/vcs/WEB-INF/vcs.properties to customize self IP, VC IP and credentials
6. Start tc server: tcruntime-ctl.sh tcserver start
7. Deploy VIB on the portlet UI

## Build Instructions
1. Clone the project
2. Install Apache Ant
3. Run "ant" in vcs folder