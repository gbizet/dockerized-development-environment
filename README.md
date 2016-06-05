# dev-env-setup
A simple and fast way to create a development environment with Jenkins, Nexus and Nginx.

# Prerequisites
- Docker
- Oracle VM VirtualBox Manager

# Getting started

1. Run prepare.bat
2. Open Oracle VM VirtualBox Manager. Right click your docker machine and map a host port (e.g. 8182) to the internal port 80 (the port to which nginx is listening)
3. docker-compose up (it will start the containers on your active machine)
4. After the initialization is finished (first time will take about 10 mins for jenkins and 2 mins for nexus maybe because they are downloading and initializing stuff in the specified volumes) you will be able to access Jenkins and Nexus at http://localhost:8182/jenkins and http://localhost:8182/nexus

Have fun! :D
