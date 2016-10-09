# SSH Tunneler

Create a reverse tunnel from current PC to a given server

## Goal

A single project to enable desktop-user friendly reverse tunnel system, for support-givers to deploy, and apply in various scenarios:

* As a tehnical support provider, you want to connect to users who are behind NATs and firewalls, running Linux, Windows or OS X; you want your users to be able to simply open an application that allow them to give you access to their PC, and allow them to shut down that access when they stop the application.
* As a maintenance operator, you want your customer's server to have a mechanism where the customer can turn on or off access to the machine from outside their LAN.
* As a maintenance operator, you want to be able to instruct a machine you manage, which is behind a NAT, to be able to temporarily be accessible.
* You want to secure connections through your own proxy SSH server.

This project aims to provide the tools to allow this to be done, using SSH tunneling.

## Target Platforms

* Linux desktops (with a local VNC server)
* Windows Pro desktop (taking advantage of the integrated RDP)
* Mac OS X desktop (integrated screen sharing, whose state is controlled using OSA scripting)
* Linux servers (this project will provide a web interface)
