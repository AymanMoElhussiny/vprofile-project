### for ubuntu 
- virtualbox
```bash
 sudo apt install virtualbox
```
- vagrant
> Install VirtualBox To install Vagrant, first get a cloud (virtualization) hypervisor. Any virtual machine, such as KVM, Docker, VMware, or VirtualBox, is able to fulfill this purpose. This example uses VirtualBox.VirtualBox is a virtualization tool that allows users to create and manipulate several OSs as virtual machines. Since Vagrant creates virtual operating systems, it needs a tool like VirtualBox to manage them. 

```bash
sudo apt install vagrant
```
- git
```bash
sudo apt-get update
sudo apt-get install git
 ```
- corretto11jdk
> Amazon Corretto is a no-cost, multiplatform, production-ready distribution of the Open Java Development Kit (OpenJDK). Corretto comes with long-term support that includes performance enhancements and security fixes. Amazon runs Corretto internally on thousands of production services and Corretto is certified as compatible with the Java SE standard. With Corretto, you can develop and run Java applications on popular operating systems, including Linux, Windows, and macOS.
[corretto](https://docs.aws.amazon.com/corretto/latest/corretto-11-ug/generic-linux-install.html)

- maven
> Apache Maven is an open-source project management tool primarily used for developing Java applications. Maven incorporates a POM (Project Object Model) approach, which means it uses an XML file to store information about projects, configurations, and dependencies.
```bash
sudo apt install maven
mvn -version
```
- aws cli
 ```sudo apt-get install awscli```
- intellijidea
```  sudo snap install intellij-idea-community --classic ```
- vscode

- sublime text
```bash
sudo apt update
sudo apt install dirmngr gnupg apt-transport-https ca-certificates software-properties-common
curl -fsSL https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -
sudo add-apt-repository "deb https://download.sublimetext.com/ apt/stable/"
sudo apt install sublime-text
```
