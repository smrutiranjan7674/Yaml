Java deployment steps(for tomcat9):
Step 1: Install OpenJDK
sudo apt update
sudo apt install default-jdk
Step 2: Create Tomcat User
sudo useradd -r -m -U -d /opt/tomcat -s /bin/false tomcat
Step 3: Install Tomcat
wget http://www-eu.apache.org/dist/tomcat/tomcat-9/v9.0.27/bin/apache-tomcat-9.0.27.tar.gz -P /tmp
sudo tar xf /tmp/apache-tomcat-9*.tar.gz -C /opt/tomcat

