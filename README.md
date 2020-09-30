# COVID-19-Tracker-Application

It is a web application which gives the number of COVID-19 patient across the globe.

## Getting Started


Through this application, the people can find the total number of COVID-19 patient across the globe, country and state and can also find the number of daily cases.


## Prerequisites

You need to install these softwares

```
Java
Maven
```


## Installing

### Must install JDK-11 or onward.

Installation and running steps for OpenJDK, version 11 on Ubuntu.

Ensure your system is up-to-date:

```
$ sudo apt-get update
$ sudo apt-get upgrade
```
1. Install the OpenJDK 11 development kit, which includes OpenJRE 11:

```
$ sudo apt-get install openjdk-11-jdk
```
Alternatively, if you simply want to run Java applications that you have already downloaded, you can choose to only install OpenJRE 11:

```
sudo apt-get install openjdk-11-jre
```
2. Check the version of the JRE to verify that it has been properly installed:

```
java -version
```
As of the time of this publication, this command should return:

```
openjdk version "11.0.8" 2020-04-14 LTS
OpenJDK Runtime Environment 18.9 (build 11.0.7+10-LTS)
OpenJDK 64-Bit Server VM 18.9 (build 11.0.7+10-LTS, mixed mode, sharing)
```
3. If you have chosen to install the full OpenJDK development kit, check the version of the compiler as well:

```
javac -version
```
As of the time of this publication, this command should return:

```
javac 11.0.8
```
#### Set Environment Variables

1. This section will instruct you on how to set the JAVA_HOME and PATH environment variables to help ensure that your Java applications will run without issue.

```
1 # [...]
2 export JAVA_HOME=$(dirname $(dirname $(readlink -f $(which java))))
3 export PATH=$PATH:$JAVA_HOME/bin
```

2. Save the changes and exit your text editor.
3. Reload the ~/.bashrc file:

  ```
  source ~/.bashrc
  ```
4. Verify that the JAVA_HOME and PATH variables were set correctly:

```
echo $JAVA_HOME
echo $PATH
```
 The JAVA_HOME variable should be set to the directory that contains your OpenJDK installation, and the PATH variable should include the directory that contains the OpenJDK binary files.


### Installation steps for Maven on Ubuntu with apt 

Update the packages index and install Maven by entering the following commands.

```
$ sudo apt update
$ sudo apt install maven
```
To verfiy the installation, run 

```
$ mvn -version
```
The output should look something like this:

```
Apache Maven 3.6.3
Maven home: /usr/share/maven
Java version: 11.0.7, vendor: Ubuntu, runtime: /usr/lib/jvm/java-11-openjdk-amd64
Default locale: en_US, platform encoding: UTF-8
OS name: "linux", version: "5.4.0-26-generic", arch: "amd64", family: "unix"
```


## Contributing

- Collecting the Data from the following GitHub link.
- Not sure this is accurate data but for now this data is correct.




