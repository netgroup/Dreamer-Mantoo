![Alt text](repo_data/dreamer-logo.png "Optional title")

Dreamer-Mantoo
===================

Full documentation for the project is available at 

---------------------------

Overview
-----------
**Mantoo** is a set of Open Source tools meant to support
SDN experiments over emulators and distributed testbeds. 

----------------------------------
Getting Started
---------------------
Assuming git installed:

```sh
$ git clone https://github.com/netgroup/Dreamer-Mantoo.git
```
By default you get the directories that contain submodules, but none of the files within them yet, to obtain a single submodule  (for example, the Topology 3D):
```sh
$ cd Topology3D
$ git submodule init
$ git submodule update
```
If you pass ```--recursive``` to the ```git clone``` command, it will automatically initialize and update each submodule in the repository:

```sh
$ git clone --recursive https://github.com/netgroup/Dreamer-Mantoo.git
```
