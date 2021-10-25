### cursos
https://www.udemy.com/course/hadoopstarterkit/learn/lecture/2995878#overview

emplear versión 3.1.3

### videos
https://www.youtube.com/watch?v=g7Qpnmi0Q-s
https://www.youtube.com/watch?v=R7w8FAlnhAw&list=PLG1t8jaLbxA9xRB9usec8-fHWq7F6Kaau


### activar telnet
https://www.ryadel.com/en/telnet-windows-10-client-setup-install-activate/

dism /online /Enable-Feature /FeatureName: TelnetClient

### error JAVA_HOME
https://stackoverflow.com/questions/31621032/hadoop-on-windows-error-java-home-is-incorrectly-set

set JAVA_HOME=C:\Progra~1\Java\jdk1.8.0_131\

### instalación
hdfs namenode -format

### luego de instalación para iniciar servidor
en el sbin start-all.cmd

### crear carpeta
hdfs dfs -mkdir /user/rbm


### en linux ejecutar luego de modificar yarn-site.xml

jps 

### corrección de error en debian 10
https://forum.proxmox.com/threads/apt-get-update-error-changed-its-suite-value-from-stable-to-oldstable.94726/
apt-get update --allow-releaseinfo-change

### configurar JAVA_HOME
https://vitux.com/how-to-setup-the-java_home-path-in-debian-10/
export JAVA_HOME=/usr/lib/jvm/java-1.11.0-openjdk-i386

### configurar HADOOP_HOME
warn util: unable to load native-hadoop library for your platform
export $HADOOP_HOME=/lib/native/libhadoop.so.1.0.0

### comandos
sbin
stop-dfs.sh



8:54