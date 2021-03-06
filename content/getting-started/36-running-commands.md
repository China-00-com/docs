+++
title = "How to Run SSH Commands"
weight = "36"

tags = ["install", "agent", "account", "quickstart"]
section = "getting-started"
categories = ["getting-started"]
type = "page"

slug = "running-commands"

[menu.main]
    url = "running-commands"
    parent = "getting-started"

+++

You'll need to connect to your server via [SSH](https://en.wikipedia.org/wiki/Secure_Shell) to run the commands - how you go about doing this depends on the type of server you're using (AWS, DigitalOcean, Microsoft Azure, etc).

If you're unsure about how to do this, you should refer to your Cloud provider's documentation:

* [Amazon Web Services - Using SSH](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AccessingInstancesLinux.html)  
* [Google Cloud Platform - SSH from the Browser](https://cloud.google.com/compute/docs/ssh-in-browser)  
* [Digital Ocean - Connect to Your Droplet with SSH](https://www.digitalocean.com/community/tutorials/how-to-connect-to-your-droplet-with-ssh)

To make an SSH connection, you'll need the following:

1.  An SSH client or Command Line Tool
2.  Username (usually _root_ on Linux)
3.  Password and/or SSH Key
4.  The IP address of your Server

_An example of the DigitalOcean's in-browser SSH tool, where you would run the command:_

![https://docs.barricade.io/src/img/getting-started/do-ssh.jpeg](https://docs.barricade.io/src/img/getting-started/do-ssh.jpeg)
