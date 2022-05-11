### DOCUMENTATION OF PROJECT-3 MERN STACK IMPLEMENTATION

## <center>BACKEND CONFIGURATION

In this project I would be deploying a web solution based on MERN stack in AWS Cloud.

We will need to setup an instance of t2.nano family with Ubuntu Server 20.04 LTS (HVM) image, Node.JS, Expressjs & Mongodb database.

Now launch an Instance of t2.nano with Ubuntu Server 20.04 LTS (HMV) image

![alt text](./Images/AWS%20console.JPG)


First update and upgrade Ubuntu by running the following commands

<code>sudo apt update</code>

Then upgrade ubuntu

![alt text](./Images/sudo%20update.JPG)

<code>sudo apt upgrade</code>

Lets get the location of Node.js software from Ubuntu repositories.

<code>curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -</code>

![alt text](./Images/curl%20command.PNG)

To install Node.js on the server, run the command;

<code>sudo apt-get install -y nodejs</code> The command also installs both node.js and npm, NPM is a package manager for Node like apt for Ubuntu, it is used to install Node modules & packages; also manage dependency conflicts

![alt text](./Images/sudo%20apt%20get.PNG)





