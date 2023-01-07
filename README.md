# ConatainerSSHdemo
Hi Folks, this repository contains a demo of containerSSH.


ContainerSSH quick start
This example is not production-ready! Please read the ContainerSSH documentation.

Step 1: Set up a Dockerized Environment. 
To run this quick start please make sure you have a working Docker environment and a working docker-compose.

Step 3: Launch ContainerSSH
For a Docker environment run docker-compose up -d in the downloaded quick-start (this) directory.

Step 4: Logging in
Run ssh foo@localhost -p 2222 on the same machine via a new terminal window. This is your test client. You should be able to log in with any password.

Step 5: Cleaning up
Once you're done, you can shut down the server using the docker-compose down, then remove the images using docker-compose rm
