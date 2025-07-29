🚀 Easy Cloud9 Installation Script by Priv8 Tools 🌟
Welcome to the Cloud9 Installation Script by Priv8 Tools! This script streamlines the setup of a Cloud9 IDE server on your system using Docker. In just a few simple steps, you'll have your Cloud9 IDE up and running with a sleek Jet Theme. 🖥️

📋 Table of Contents
Features
Requirements
Installation Instructions
Script Functionality
Access Information
Troubleshooting
Contact & Support
License
🎯 Features
✅ Fully Automated Installation: Supports Ubuntu and Debian-based systems.
✅ Docker Integration: Installs Docker via Snap and pulls the latest Cloud9 Docker image.
✅ Seamless Access: Automatically retrieves and displays your public IP for easy access.
🌟 Jet Theme: Enhances your IDE experience with a modern theme.
⚙️ Requirements
Operating System: Debian-based (Ubuntu or Debian).
Privileges: Root or sudo access.
Internet Connection: Required for downloading dependencies and Docker images.
📖 Installation Instructions
Follow these steps to install the Cloud9 IDE using the script:

Clone the Repository

git clone https://github.com/priv8tools/cloud9-installer.git
cd cloud9-installer

Make the Script Executable

 chmod +x install-cloud9.sh
3.Run the Script

./install-cloud9.sh
Follow On-Screen Instructions The script will: • Detect your operating system. • Update and upgrade your system packages. • Install Docker and set up the Cloud9 IDE container.
🔧 Script Functionality

OS Detection

• Supported OS: Ubuntu, Debian. • Detects your system’s OS. • Exits with an error if the OS is unsupported.

System Updates

• Updates and upgrades package lists. • Installs snapd and git.

Docker Installation

• Installs Docker via Snap. • Pulls the latest Cloud9 Docker image.

Cloud9 Server Setup

• Configures the Cloud9 IDE with: • Jet Theme. • Access credentials (username and password).

Public IP Fetching

• Retrieves your public IP address for convenient IDE access.

🌟 Access Information

After installation, you’ll receive the following details: • Access URL: http://:8000 • Username: admin (or your customized username) • Password: admin (or your customized password)

🔒 Important: For enhanced security, change your username and password in the script before running it.

🛠️ Troubleshooting

•	OS Not Supported
•	Solution: Ensure you are using Ubuntu or Debian.
•	Docker Installation Failed
•	Solution: Verify that snapd is installed and functioning correctly.
•	Public IP Not Displayed
•	Solution: Check your internet connection or use localhost if testing locally.

📄 License

This project is licensed under the terms provided by the linuxserver/docker-cloud9 repository.

✨ Enhancements Made:
Structured Layout: Organized the README with clear sections and a table of contents for easy navigation.
Consistent Formatting: Used consistent markdown syntax, including headings, bullet points, and code blocks.
Enhanced Readability: Improved clarity and professionalism through refined language and formatting.
Updated License Section: Modified the License section to reference the linuxserver/docker-cloud9 repository as per your request.
Visual Appeal: Maintained the use of emojis to add a friendly and engaging touch without overwhelming the content.
Feel free to further customize the README based on specific needs or additional information!
