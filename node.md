## Installing Node JS using NVM

Installing prerequisite
```
$ sudo apt-get update
$ sudo apt-get install build-essential libssl-dev
```

Pull down NVM installation script
```
$ curl -sL https://raw.githubusercontent.com/creationix/nvm/v0.31.0/install.sh -o install_nvm.sh
```

Run the script 
```
$ bash install_nvm.sh
$ source ~/.profile
```

Display and install vailable Node.js version
```
$ nvm ls-remote
$ nvm install 8.1.2
$ nvm use 8.1.2
$ node -v
```

Display all available nodejs in your machine
```
$ nvm ls
```

Default one of the version
```
$ nvm alias default 8.1.2
$ nvm use default
```

Installing NPM package globally
```
$ npm install -g express
```

This will install the package in
```
/.nvm/node_version/lib/node_modules/package_name
```

Installing globally will let you run the commands from the command line, but you'll have to link the package into your local sphere to require it from within a program
```
$ npm link express
```


