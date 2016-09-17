Kurator-RestFlow
================

This repo defines a build of [RestFlow](http://restflow.org) customized for use by Kurator users. Example workflows are included in the samples directory.

Preparing to run Kurator-RestFlow
---------------------------------

This section describes how to set up an environment for running RestFlow workflows.
 
### 1. Check installed version of Java

RestFlow requires Java version 1.7. To determine the version of java installed on your computer use the -version option to the java command. For example,

    $ java -version
    java version "1.7.0_13"
    Java(TM) SE Runtime Environment (build 1.7.0_13-b20)
    Java HotSpot(TM) 64-Bit Server VM (build 23.7-b01, mixed mode)
    $

### 2. Download the RestFlow standalone jar

RestFlow is distributed as a jar (Java archive) file. Download the jar for the [latest release](https://github.com/kurator-org/kurator-restflow/releases). It will be named something like `kurator-restflow-1.0b3-SNAPSHOT-jar-with-dependencies.jar`.

 
### 3. Create an alias for running RestFlow

Define an alias for more conveniently running RestFlow at the command line. For example, if you have saved the RestFlow jar to the bin subdirectory of your home directory, the following bash command will create an alias for running RestFlow simply by typing restflow at the command prompt. 

    alias restflow='java -jar ~/bin/kurator-restflow-1.0b3-SNAPSHOT-jar-with-dependencies.jar'

Try out the new alias by printing RestFlow help:

    $ restflow -h
