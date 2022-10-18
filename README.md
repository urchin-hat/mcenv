# Simple MySQL(my.cnf) Management: mcenv
mcenv allows you to easily switch the mysql connection destination configuration file.
It allows you to quickly connect to mysql without having to add command options when connecting with the mysql command.

## What mcenv does...
Quickly switch between MySQL connections.

For example, the following use cases are envisioned
- Lots of managed MySQL instances in the public cloud
- You have MySQL processes running on multiple ports

# Getting started
Manual git checkout

Clone anyenv into ~/.mcenv.
```
$ git clone https://github.com/urchin-hat/mcenv.git ~/.mcenv
```

Add ~/.mcenv/bin to your $PATH for access to the anyenv command-line utility.
```
example
$ ln -sf  ~/.mcenv/bin/mcenv /usr/local/bin
```
