#  Example multi threaded UDP server for Linux which uses SO_REUSEPORT and BPF microcode to spread traffic between threads. It has issue as it uses SO_REUSEADDR as workaround 

Please do not use this code for production as SO_REUSEADDR exposes you to security risks.

This is example code for my blog [article](https://pavel.network/rocky-road-towards-ultimate-udp-load-balancing-server-on-linux/)

