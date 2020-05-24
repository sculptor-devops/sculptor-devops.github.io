# Introduction
This echosystem is designed for developers to automate site deploy, it control all the normal operations such as site add, remove, deploy and maintenance. With a simple client you can install in minutes and controll all the machine with the scultpor client or with integrated api. With this structure you can automate and controll from one to infinite servers. Differently from SaaS external services, that remote manage the machine, here you have complete control no need to share credentials with noone.

# Blocks Scheme

![Scheme](/assets/img/scheme.png)

**Installer** This prepare the machine, configure services and installe the agent.

**Agent** Control and manage all the machine, it expose an api endpoint.

**Client** The command line console that allow you to controll remotely your server.

# Features

- All services you need: PHP 7.4, MySQL, Nginx, Redis, Supervisor. 
- Anti hammering
- Automated unattended system security updates
- Zero downtime deploy
- Customizable deploy
- Git integrated
- Let's Encrypt automation
- Multi site and multi server
- Backup on ftp, s3, dropbox
- Monitor system kpi