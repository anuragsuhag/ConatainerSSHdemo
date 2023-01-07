# ConatainerSSHdemo
Hi Folks, this is a repository containing a demo of containerSSH.

![SSH](https://user-images.githubusercontent.com/52308512/211169079-42da4d73-4146-435d-9087-5a75bbd5b142.png)

ContainerSSH demo/start
This example is not production-ready! Please read the ContainerSSH documentation to setup auth and config server.

Step 1: Set up a Dockerized Environment.

To run this demo, please make sure you have a working Docker environment and a working docker-compose.

Step 2: Launch ContainerSSH

For a Docker environment run docker-compose up -d in the downloaded directory.

Step 3: Logging in

Run ssh foo@localhost -p 2222 on the same machine via a new terminal window. This is your test client. You should be able to log in with any password.

Step 4: Cleaning up

Once you're done, you can shut down the server using the docker-compose down, then remove the images using docker-compose rm.
