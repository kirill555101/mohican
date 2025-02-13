# Welcome to mohican

## What's mohican?
Mohican is a free, open-source web server made for Linux systems.

Features:
* Mohican can process http requests.
* Mohican can connect to other web-servers.
* Mohican uses config file to get information.
* Mohican is controlled by command line.
* Mohican writes information into logs.

## List of commands
### 1. Start mohican web server.
```
$ sudo ./mohican.sh start
```

### 2. Build mohican web server.
```
$ sudo ./mohican.sh build
```

### 3. Get help about commands.
```
$ sudo ./mohican.sh help <command>
```

### 4. Create new config.
```
$ sudo ./mohican.sh create config
```

### 5. Get status.
```
$ sudo ./mohican.sh status
```

### 6. Reload mohican web server.

#### Reload hard
```
$ sudo ./mohican.sh reload hard
```

#### Reload soft
```
$ sudo ./mohican.sh reload soft
```

### 7. Stop mohican web server.

#### Stop hard
```
$ sudo ./mohican.sh stop hard
```

#### Stop soft
```
$ sudo ./mohican.sh stop soft
```

## Before start
### 1. You need to install gcc.
```
$ sudo apt-get install gcc
```

### 2. You need to install cmake.
```
$ sudo apt-get install cmake
```

### 3. You need to install boost library.
```
$ sudo apt-get install libboost-all-dev
```

## Getting started
### 1. You need to clone mohican repository.
```
$ git clone https://github.com/Neytrinoo/mohican
```

### 2. You need to start build command.
```
$ sudo ./mohican.sh build
```
