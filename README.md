Test environment

* Distro: Debian 10 buster
* Architecture: x86 64bit

Install

    $ cd ~/vue.js/npm
    $ npm install @vue/cli
    $ export PATH=${PATH}:~/vue.js/npm/node_modules/.bin

Initialize my-project

    $ cd ~/vue.js
    $ vue create my-project

Replace source files

    $ cd my-project
    $ mv src src.org
    $ git clone https://github.com/zuka0828/vue-test src

Start service

    $ npm run serve

Then, access `http://MACHINE_IP:8080/`
