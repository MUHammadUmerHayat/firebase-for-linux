# firebase-for-linux

<h2><b>Install a specific version of Node.js using NVM</h2>

There is another way to install Node.js on a server with Ubuntu 18.04. Using an NVM (Node Version Manager), we can choose a specific version to install. It’s great if you want to use an LTS version or just the latest version available.

1)  First, download NVM using wget. If you are not sure you have wget, run this command.


           sudo apt install wget

2)  Now, run this command:

           wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.34.0/install.sh | bash


3)  The next step is to allow NVM to be used from your user’s bash profile by running this command:


           source ~/.profile
 
4)  Now, you can use NVM to show all the versions of Node.js available to install.


           nvm ls-remote

5)  Now,you will see the List of available Node.js versions for Ubuntu.



6)  Feel free to choose the one you want. For stability and support we recommend version 12.16.2. To do it, run this command:

           nvm install 12.16.2

7)  You can check if the installation was successful by checking the version of Node.js. To do this execute:

           node -v
           
Checking Installed Node.js version

8)  You can check npm version by running

           npm -v
           
 <h1> Install firebase on ubuntu</h1>
 
1)  To install firebase on your system ,run this command
   
           npm install -g firebase-tools
           
2)  To check firebase verion

            firebase --version
           

Congrats, everything went well. Node.js and firebase is correctly installed and ready to use.
