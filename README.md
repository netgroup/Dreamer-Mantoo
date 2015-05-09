![OSHI and DREAMER logos](http://netgroup.uniroma2.it/twiki/pub/Oshi/WebHome/dreamer-oshi-logo-github-2.png "http://netgroup.uniroma2.it/OSHI")

Dreamer-Mantoo
===================

Overview
-----------
**Mantoo** (**Man**agement **too**ls) is a set of Open Source tools meant to support SDN experiments over Mininet emulator and distributed testbeds. Mantoo is a result of the [DREAMER project](http://netgroup.uniroma2.it/DREAMER/).

Mantoo includes a number of components:  

* Topology3D - an extensible web-based graphical topology designer providing different layered network “views”  
* Topology and Service Validator - A server-side component to validate topologies 
* Experiment-Handler - Controlling emulated SDN testbeds via a web GUI
* Testbed Deployer - Producing the testbed configuration files to be used by the Management Scripts
* Management Scripts - Scripts to install and configure an OSHI testbed on distributed experimental facilities like GOFF and OFELIA  
* Mininet Extensions - Emulating OSHI networks using Mininet
* Measurements Tools - Running iperf experiments on OSHI testbeds and collecting CPU load of your VMs thanks to xentop tool  

Addtional documentation is available at http://netgroup.uniroma2.it/OSHI/ .

----------------------------------
Getting Started
---------------------

(We assume that you have git installed!)

If you pass ```--recursive``` to the ```git clone``` command, it will automatically initialize and update each component (submodule) in the repository:

```sh
$ git clone --recursive https://github.com/netgroup/Dreamer-Mantoo.git
```
Otherwise you will have to update the components manually:

```sh
$ git clone https://github.com/netgroup/Dreamer-Mantoo.git
```
You get the directories that contain the submodules, but none of the files within them yet, to obtain a single submodule  (for example, the Topology 3D):
```sh
$ cd Topology3D
$ git submodule init
$ git submodule update
```
