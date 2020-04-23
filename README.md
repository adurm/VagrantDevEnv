# Vagrant Development environment
This repository consists of a node application containing mongodb.

## Prerequisities to run
- Vagrant
- VirtualBox

## How to use
1) Create the two virtual machines (one for app, one for database)
```bash
$ vagrant up
```

2) Enter the app virtual machine
```bash
$ vagrant ssh app
```

3) Navigate to the correct foloder
```bash
$ cd /home/vagrant/app
```

4) Install the app's dependencies
```bash
$ npm install
```

5) Run the app
```bash
$ npm start
```

6) On your web browser navigate to the url: 'development.local'
 
