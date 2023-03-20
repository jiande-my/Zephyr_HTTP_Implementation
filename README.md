# GSoC'23 Preparation
## HTTP Server Implementation
Project Detailed: https://wiki.linuxfoundation.org/gsoc/2023-gsoc-zephyr#project_1_http_server_implementation

## Zephyr HTTP Server Demonstrate
### Simple Socket-based program in C

![](/assets/image/webserver.png)
Figure1: Running HTTPServer

![](/assets/image/client.png)
Figure2: Running HTTP Client

![](/assets/image/web-browser.png)
Figure3: Web-Browser work Fine

![](/assets/image/wireshark.png)
Figure4: WireShark capture of the HTTP traffic between the client and host

### Running Zephyr Networking with QEMU
1. Setup Zephyr environment and install SDK
1. Fetch the Zephyr net-tools project
1. Create Helper Socket
![](/assets/image/help_socket.png)

1. Start TAP device routing daemon
![](/assets/image/daemon.png)

1. Build and start the <echo_server> sample application.
![](/assets/image/echo_server1.png)
![](/assets/image/echo_server2.png)

1. Ping the Host
![](/assets/image/ping_host.png)

1. WireShark capture of the network traffic for QEMU
![](/assets/image/wireshark_zephyr.png)