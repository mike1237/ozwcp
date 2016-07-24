# ozwcp
Open Zwave Control Panel in a Docker Container


This container provides the Open Zwave Control Panel exposing the web server on the default port of 8090.

Example run command:
**docker run -d -p 8090:8090 --device=/dev/ttyACM0:/dev/ttyACM0 n5qm/ozwcp**
