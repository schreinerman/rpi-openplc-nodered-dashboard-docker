# rpi-openplc-nodered-dashboard-docker
 Stack to provide a solution with OpenPLC, NodeRed and Dashboard via HDMI
 
 Every part is provided in a seperate container.
 
 #### Docker compose

 A `docker-compose.yml` file is part of this repository
 
 The HTTP interface of the OpenPLC container can be reached by port 8080. (Modbus TCP Server at 502)
 See more information at [rpi-openplc-docker](https://www.github.com/schreinerman/rpi-openplc-docker) 

 The HTTP interface of the NodeRED container can be reached by port 1880.
 See more information at [rpi-nodered-docker](https://www.github.com/schreinerman/rpi-nodered-docker) 
 
 The VNC interface of the Dashboard container can be reached by port 5900.
 See more information at [rpi-nodered-dashboard-hdmi-docker](https://www.github.com/schreinerman/rpi-nodered-dashboard-hdmi-docker) 
 
 
 ### License

 Copyright (c) Manuel Schreiner. All rights reserved.
 Licensed under the LISENSE.txt file information stored in the project's source code repository.

 As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).
 As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.



