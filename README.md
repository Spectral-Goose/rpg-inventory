How to Install Meteor and run rpg-inventory on Ubuntu.

Step 1: Install the Meteor framework
    $ curl https://install.meteor.com/ | sh

Step 2: Install @babel/runtime. This package is necessary for the project to run. You might also be prompted to run a fix for the package.
    $ meteor npm install --save @babel/runtime
    (only if needed) $ npm audit fix

Step 3: Download the project from Github, navigate to the project's home directory (rpg-inventory/), and launch the project.
    $ meteor

Step 4: Open a web browser and open localhost at the following link.
    http://localhost:3000