# Vagrant Multi-machine + Ansible for HAProxy + Spring Boot Spike


## Goal: 
Validate interactions and configurations between HAProxy and  Spring Boot REST service.

## How: 
Using Vagrant Multi-machine with Ansible provision to replicate a distributed topology.

    
## Evaluated

* HAProxy round-robin Load Balancing http://cbonte.github.io/haproxy-dconv/intro-1.6.html#3.3.5
* HAProxy Statistics http://cbonte.github.io/haproxy-dconv/intro-1.6.html#3.3.16
* HAProxy Logging http://cbonte.github.io/haproxy-dconv/configuration-1.7.html#8
* HAProxy http-check expect + Spring Boot Actuator Health check http://cbonte.github.io/haproxy-dconv/configuration-1.7.html#4-http-check%20expect https://github.com/rafaelpsouza/spring-boot-jersey-multi-project

