rpm-tomcat6
===========

An RPM spec file to install Tomcat 6.0.

To Build:

`sudo yum -y install rpmdevtools && rpmdev-setuptree

`wget https://raw.github.com/nmilford/rpm-tomcat6/master/tomcat6.spec -O ~/rpmbuild/SPECS/tomcat6.spec`

`wget https://raw.github.com/nmilford/rpm-tomcat6/master/tomcat6.init -O ~/rpmbuild/SOURCES/tomcat6.init`

`wget https://raw.github.com/nmilford/rpm-tomcat6/master/tomcat6.sysconfig -O ~/rpmbuild/SOURCES/tomcat6.sysconfig`

`wget https://raw.github.com/nmilford/rpm-tomcat6/master/tomcat6.logrotate -O ~/rpmbuild/SOURCES/tomcat6.logrotate`

`wget http://www.gtlib.gatech.edu/pub/apache/tomcat/tomcat-6/v6.0.37/bin/apache-tomcat-6.0.37.tar.gz -O ~/rpmbuild/SOURCES/apache-tomcat-6.0.37.tar.gz`