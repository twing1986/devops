# Jenkins
java -version
sudo apt-get install openjdk-8-jre
find /usr/lib/jvm/java-1.8* | head -n 3

find /usr/lib/jvm/java-1.8* | head -n 3
JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-amd64
export JAVA_HOME
PATH=$PATH:$JAVA_HOME

sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
sudo apt-get update
sudo apt-get install jenkins
# wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -
sudo add-apt-repository universe
sudo apt-get install jenkins

# sudo add-apt-reposudo dpkg-reconfigure libdvd-pkg
cat /var/log/jenkins.log
 