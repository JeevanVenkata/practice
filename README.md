# practice
tar xvzf
find / -name context.xml
tomcat 
 <role rolename="manager-gui"/>
  <role rolename="manager-status"/>
  <role rolename="manager-jmx"/>
  <role rolename="manager-script"/>
  <user username="admin" password="admin" roles="manager-gui,manager-status,manager-jmx,manager-script"/>
  <user username="deployer" password="deployer" roles="manager-script"/>
  <user username="tomcat" password="tomcat" roles="manager-gui"/>
jenkins
M2="/opt/maven/bin"
M2_HOME="/opt/maven"
JAVA_HOME="/usr/lib/jvm"
PATH=$PATH:$HOME/bin:$JAVA_HOME:$M2_HOME:$M2
export $PATH

/usr/lib/jvm/java-17-amazon-corretto.x86_64
/opt/maven
tar -zxvf 
docker
/etc/hostname
docker exec -it tc1 /bin/bash
cp -R * ../webapps/
FROM tomcat:latest
RUN cp -R /usr/local/tomcat/webapps.dist/* /usr/local/tomcat/webapps/
COPY ./*.war /usr/local/tomcat/webapps/
docker -build -t sample_img .

