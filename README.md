# ClassMe

E-Learning - LMS ( Learning Management System ).

### Version
1.0.0

### Tech

Dillinger uses a number of open source projects to work properly:

* [AngularJS] - HTML enhanced for web apps!
* [Twitter Bootstrap] - great UI boilerplate for modern web apps
* [node.js] - evented I/O for the backend
* [Express] - fast node.js network app framework [@tjholowaychuk]
* [Grunt] - the streaming build system
* [jQuery] - duh
* [Ruby On Rail] BackEnd Server
* [WebRTC] Video Streaming

### Installation

You need Git installed globally:

```sh
$ sudo apt-get update
$ sudo apt-get install git
```

You need NodeJs installed globally:

```sh
$ curl -sL https://deb.nodesource.com/setup | sudo bash -
$ sudo apt-get install -y nodejs
$ node -v
```

You need Grunt installed globally:

```sh
$ npm install -g yo bower grunt-cli gulp
```

You need Ruby & Rails installed globally:

```sh
$ git clone https://github.com/sstephenson/rbenv.git ~/.rbenv
$ echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
$ echo 'eval "$(rbenv init -)"' >> ~/.bashrc
$ git clone https://github.com/sstephenson/ruby-build.git ~/.rbenv/plugins/ruby-build
$ sudo apt-get update
$ rbenv install 2.2.0
$ rbenv global 2.2.0
$ ruby -v
$ sudo apt-get install build-essential libssl-dev libcurl4-gnutls-dev libexpat1-dev gettext unzip
$ gem install rails
$ rails -v
```

### Plugins

Dillinger is currently extended with the following plugins

* Dropbox
* Github
* Google Drive
* OneDrive


### Development

Want to contribute? Great!

Dillinger uses Grunt for fast developing.
Make a change in your file and instantanously see your updates!

Open your favorite Terminal and run these commands.

First Tab:
```sh
$ rails
```

Second Tab:
```sh
$ grunt serve
```

(optional) Third:
```sh
$ node app
```

### Todo's

 - Write Tests
 - Rethink Github Save
 - Add Code Comments
 - Add Night Mode

License
----

CNC



