# P1ckl3d Web Shell: A Comprehensive Guide to Advanced Web Shell for Security Testing

![P1ckl3d Web Shell](https://r00t-shell.com/wp-content/uploads/2025/02/P1ckl3d-Web-Shell.png)

> **⚠️ Important Security Notice**
>
> This tool is intended for **authorized security testing only**. Using this tool without explicit permission is **illegal** and could result in **serious legal consequences**.

## 🔍 Introduction

In the realm of **cybersecurity** and **penetration testing**, having the right tools is crucial for thorough security assessments. The **P1ckl3d Web Shell** is an advanced tool designed specifically for **security professionals** conducting authorized penetration testing.

## ✨ Key Features and Capabilities

| Feature                   | Description  |
|---------------------------|--------------|
| 🔄 **Dynamic Command Execution** | Execute real-time shell commands, maintain history, and avoid page reloads |
| 📁 **File Management** | Seamless file uploads, directory navigation, and file downloads |
| 🔍 **System Information Gathering** | Retrieve OS details, network configurations, user info, and security settings |
| 🌐 **Network Reconnaissance** | Gather details about running processes, services, and open ports |
| 🔑 **User Privilege Escalation Analysis** | Identify potential privilege escalation vectors |

## 🛠️ Installation and Setup Guide

### Prerequisites
- A web server with PHP support
- Proper authorization to conduct security testing

### Installation Steps
1. **Download** the `webshell.php` file from the repository:
   ```bash
   git clone https://github.com/RootShelll/P1ckl3d-Web-Shell.git
   cd P1ckl3d-Web-Shell
   ```
2. **Identify** a suitable upload point on the target system.
3. **Upload** the file through the identified vulnerability.
4. **Access** the web shell through the uploaded URL.

## 🚀 How to Use P1ckl3d Web Shell

### Basic Commands
```bash
# Execute system commands
command> ls -la

# Change directory
command> cd /var/www

# View file contents
command> cat config.php
```

### Advanced Features
- **Enumerate Running Processes:** `ps aux`
- **Check Open Ports:** `netstat -tulnp`
- **Retrieve User Information:** `whoami && id`

## ✅ Best Practices for Usage

✔️ Always maintain detailed logs of your testing activities  
✔️ Remove the web shell immediately after testing  
✔️ Use **secure connections** when possible  
✔️ Follow the target organization's **security testing guidelines**  

## 🔧 Troubleshooting

| Issue | Solution |
|--------|------------|
| **Permission Denied** | Check file permissions and user context |
| **Upload Failed** | Verify file size limits and server configurations |
| **Connection Issues** | Check network connectivity and firewall rules |

## 📜 Legal Disclaimer
This tool is intended strictly for **ethical hacking and penetration testing** within legal boundaries. The authors and contributors **do not** take responsibility for **misuse or illegal activities** related to this software.

## 📫 Contact & Support
For any queries, contributions, or issues, reach out via:
📧 Email: security@R00t-shell.com  
💬 Discord: [Join our community](https://github.com/RootShelll/)  
🐙 GitHub Issues: [Report a bug](https://github.com/RootShelll//issues)

