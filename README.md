## Jenkins
- Jenkins is a widely used open-source automation server used to automate the software development process,one can build,test and deploy code by intergrating various plugins and tools.

## Installation 
### For Debian/Ubuntu-based systems:
- For Debian/Ubuntu-based systems:
    Update package list:
- sudo apt update

 Install Java Development Kit (JDK):
 Jenkins requires Java to run. Install the OpenJDK package:
- sudo apt install openjdk-11-jdk
- Add the Jenkins repository key:
- wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add -
- Add the Jenkins repository to your system:



sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'

Update package list again:
- sudo apt update
- Install Jenkins:
- sudo apt install jenkins

Start Jenkins:
- sudo systemctl start jenkins

Enable Jenkins to start on boot:
- sudo systemctl enable jenkins

Check Jenkins status:
- sudo systemctl status jenkins

Access Jenkins:
Open your web browser and go to http://localhost:8080 or http://your-server-ip:8080. Follow the on-screen instructions to complete the setup.


