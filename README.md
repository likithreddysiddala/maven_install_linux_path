# maven_install_linux_path

MAVEN INSTALLATION ON LINUX : 

1.[download maven from internet]
   # wget https://dlcdn.apache.org/maven/maven-3/3.8.4/binaries/apache-maven-3.8.4-bin.tar.gz

2. [un tar]
 # tar -xvzf apache-maven-3.8.4-bin.tar.gz

3.[changing to apache-maven directory]
 # cd /apache-maven-3.8.4/bin

4.[provide maven path in this location]
 # vi ~/.bashrc

   export M2_HOME=/opt/apache-maven-3.8.4

   export M2=$M2_HOME/bin

   export PATH=$M2:$PATH

5. [restart bash]   
 # source ~/.bashrc

6. [mandatory to install java on server]
 # yum install java-openjdk-1.8.0 -y 

7. [to see maven verion]
 # mvn --version
