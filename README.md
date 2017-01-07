# clovis

![clovis](https://i.imgur.com/A8aWlGI.gif)

clovis is a command line tool to get your [LÖVE](https://love2d.org/) prototype up and running in a matter of seconds

It will create all the necessary files and directories, download lume.lua and lurker.lua from their original sources, init a git repository and fire up your default text editor so you can start prototyping right away.

It includes Lurker, a small module which automatically hotswaps changed Lua files in a running LÖVE project.

# Install
Well, maybe you should not use it yet but as it's messy and suits only my own needs but here's how you can try it.
```bash
git clone https://github.com/felipebueno/clovis.git
cd clovis
chmod +x clovis
export PATH=$PATH:$PWD/clovis
cd path/to/your/new/game
clovis new mygame
```

# About
For now clovis is just a shell script with a bunch of commands that create the files and folders that I use with my little experiments. My goal is to make it a kind of package manager for LÖVE (something like [Leiningen](http://leiningen.org/) for Clojure), handling different LÖVE versions and libraries, automating builds and packaging, etc.
