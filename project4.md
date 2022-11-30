##  **PROJECT 4 IMPLEMENTATION/DOCUMENTATION OF A SIMPLE BOOK REGISTER WEB FORM USING (MEAN STACK)**

## STEP 1 – INSTALLATION OF NODEJS


### Ubuntu update

`sudo apt update`

![sudo-apt-update](./images/sudo-apt-update.PNG)
![sudo-apt-update1](./images/sudo-apt-update1.PNG)

### Ubuntu upgrade

`sudo apt upgrade`

![sudo-apt-upgrade](./images/sudo-apt-upgrade.PNG)
![sudo-apt-upgrade1](./images/sudo-apt-upgrade1.PNG)
![sudo-apt-upgrade2](./images/sudo-apt-upgrade2.PNG)

### Addition of certificate

`sudo apt -y install curl dirmngr apt-transport-https lsb-release ca-certificates`

`curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -`

![sudo-apt-y-install](./images/sudo-apt-y-install.PNG)

![curl-sl](./images/curl-sl.PNG)


### Installing NodeJS

`sudo apt install -y nodejs`

![sudo-apt-install-y-nodejs](./images/sudo-apt-install-y-nodejs.PNG)

## STEP 2 – INSTALLATION OF MONGODB

### Install MongoDB

`sudo apt install -y mongodb`

### Starting server

`sudo service mongodb start`

![sudo-apt-mongodb-start](./images/sudo-apt-mongodb-start.PNG)

### Verify that the service is up and running

`sudo systemctl status mongodb`

![sudo-apt-mongodb-start](./images/sudo-apt-mongodb-start.PNG)


### Installing npm

`sudo apt install -y npm`

![sudo-apt-install-y-npm](./images/sudo-apt-install-y-npm.PNG)

### Installing body-parser package

`sudo npm install body-parser`

![sudo-npm-install-body-parser](./images/sudo-npm-install-body-parser.PNG)

### Creation of a folder called Books

`mkdir Books && cd Books`

![mkdir-books](./images/mkdir-books.PNG)

### Initialising npm project

`npm init`

![mkdir-books](./images/mkdir-books.PNG)

## Adding file server.js

`vi server.js`

![server-js](./images/server-js.PNG)

## STEP 3 – INSTALLATION OF EXPRESS AND SETTING UP OF ROUTES TO THE SERVER

## Installation of express mongoose

`sudo npm install express mongoose`

![express-mongoose](./images/express-mongoose.PNG)

## Creation of apps folder

`sudo npm install express mongoose`

![apps-cd-app](./images/apps-cd-app.PNG)

## Creating routes.js file

`vi routes.js`

![vi-routes-js1](./images/vi-routes-js1.PNG)

![vi-routes-js](./images/vi-routes-js.PNG)

## Creating a folder named models and cd into the created folder

`mkdir models && cd models`

![mkdir-models](./images/mkdir-models.PNG)

## Creating a file named book.js

`vi book.js`

![vi-book-js](./images/vi-book-js.PNG)

![books-js](./images/books-js.PNG)

## STEP 4 – ACCESSING THE ROUTES WITH ANGULARJS

## Creating a folder name public and CD into the folder

`mkdir public && cd public`

![mkdir-public](./images/mkdir-public.PNG)


## Adding a file named script.js

`vi script.js`

![vi-script-js](./images/vi-script-js.PNG)

![script-js](./images/script-js.PNG)

## Creating a file named index.html inside public folder

`vi index.html`

![vi-index](./images/vi-index.PNG)

![index-js](./images/index-js.PNG)

## Starting the server

`node server.js`

![node-server-js](./images/node-server-js.PNG)

`curl -s http://localhost:3300`

![curl](./images/curl.PNG)

![inbound rule](./images/sec-grp.PNG)

## This is how the Web Book Register Application will look like in browser

![web](./images/web-log.PNG)

![database](./images/database.PNG)







