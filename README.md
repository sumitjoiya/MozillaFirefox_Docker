# Deploying Mozilla Firefox in Docker  

## Introduction  
The project involves setting up Mozilla Firefox, an open-source web browser, within a Docker container and running it on a local host. This demonstrates the use of containerization technology to create an isolated environment for deploying and testing software. Docker, a popular containerization platform, enables developers to package applications and their dependencies into lightweight containers. The project showcases the practicality of using Docker to manage open-source applications like Firefox in a controlled and reproducible manner.  

---

## About Mozilla Firefox  
Mozilla Firefox, developed by the Mozilla Foundation, is a free and open-source web browser recognized for its speed, security, and privacy-focused features. Launched in 2002, it quickly became popular for its user-friendly interface and robust customization options through extensions and themes.  

### Key Features:  
- **Open Source:** Firefox's source code is available for public use, modification, and distribution, promoting transparency and innovation.  
- **Privacy and Security:** Equipped with features like Enhanced Tracking Protection and built-in password management, Firefox prioritizes user security and privacy.  
- **Cross-Platform Support:** Available for Windows, macOS, Linux, Android, and iOS, making it accessible to a wide range of users.  
- **Developer Tools:** Offers powerful developer tools for web development, including a JavaScript debugger and network monitor.  

---

## Report on Terminal Activity and Localhost Search  

### 1. Terminal Activity  
The terminal serves as the interface for executing Docker commands to set up, run, and manage the Mozilla Firefox container. Below is an overview of the terminal activities undertaken during the project:  

#### Pulling the Docker Image  
The first step was to download the Docker image for Mozilla Firefox or a compatible Linux distribution image capable of running Firefox. The command used:  
```bash  
docker pull jlesage/firefox  
