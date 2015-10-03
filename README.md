# How to install Program or Package     #backend




### 1. Install NodeJS & npm
```
 curl -sL https://deb.nodesource.com/setup | sudo bash -
 sudo apt-get install nodejs
 sudo apt-get install npm
 sudo ln -s /usr/bin/nodejs /usr/bin/node

```

### 2. Install ExpressJS
```
 npm init                       ---> create file package.json
 npm install express --save     ---> install package express make for server

```

### 3. Install http-server
```
 npm install http-server -g
 
```

### 4. Install Socketio
```
 npm init                              ---> create file package.json
 npm install --save express@4.10.2     ---> install package express make for server
 npm install --save socket.io          ---> install package socketio
```




# How to install MongoDB



### 1. install
```
 mkdir myproject                    ---> create folder project
 cd myproject
 mkdir data                         ---> create folder for database
 npm init
 npm install 
 
```

### 2. start MongoDB
```
 mongod --dbpath ./data
 sudo apt-get install libkrb5-dev
```
