# 1. JTPserver Info
a. JTPserver is a shell script on most POSIX systems. This script help you to install and configure a WebServer with: JDK(OpenJDK), Tomcat, and PostgreSQL .
#
b. Curent OS support: FreeBSD 11, CentOS 7 .
#
# 2. Install
## a. Install Script Stable
### Install base
First: Install curl gzip 
### Download source
mkdir -p /home && cd /home && curl -o JTPserver-1.0.0.tar.gz -L https://github.com/iQuyet/JTPserver/archive/1.0.0.tar.gz
### Extract
tar -xzvf JTPserver-1.0.0.tar.gz
### Run script
sh JTPserver-1.0.0/jtp_latest
### Done
#
### or Run with a commandline
mkdir -p /home && cd /home && curl -o JTPserver-1.0.0.tar.gz -L https://github.com/iQuyet/JTPserver/archive/1.0.0.tar.gz && tar -xzvf JTPserver-1.0.0.tar.gz && sh JTPserver-1.0.0/jtp_latest
#
## b. Install Script Master
### Run with a commandline
mkdir -p /home && cd /home && curl -o JTPserver-master.tar.gz -L https://github.com/iQuyet/JTPserver/archive/master.tar.gz && tar -xzvf JTPserver-master.tar.gz && sh JTPserver-master/jtp_latest
#
# 3. Note

#
# 4. Log
## 1.0.0
OS Support: FreeBSD 11 (openjdk8-jre, Tomcat 8, PostgreSQL 9.5 ); CentOS 7 (jre, Tomcat 8, PostgreSQL )
#