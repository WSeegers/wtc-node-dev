wtc-node-dev
===============

To assist with the setting up of a dev environment for the platformers project
scripts will be include to ensure we are working in compatible environments


brew
-----
Using the script from https://github.com/tolsadus/42homebrewfix, install brew.

Run this command from your terminal:
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/Tolsadus/42homebrewfix/master/install.sh)"
```

node.js
-------
Install node.js using brew:
```
brew install node
```

postgresql
----------
Install postgresql using brew:
```
brew install postgresql
```
Then to start the service use:
```
brew services start postgresql
```
