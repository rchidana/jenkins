# jenkins

### Installing Jenkins on Linux

### Get Repo Key

  wget -q -O - https://pkg.jenkins.io/debian/jenkins-ci.org.key | sudo apt-key add -

### Append Debian List to servers sources.list

  echo deb http://pkg.jenkins.io/debian-stable binary/ | sudo tee /etc/apt/sources.list.d/jenkins.list
  
### Update apt-get

  sudo apt-get update
  
### Install Jenkins & its dependencies

  sudo apt-get install jenkins

### Start Jenkins Service

  sudo systemctl start jenkins
  sudo systemctl status jenkins
  
  

# Running jenkins as & when required (not installing it)

  Install JDK 1.8 or JDK 1.11
  Download Jenkins War File
  >java -jar jenkins.war
  
