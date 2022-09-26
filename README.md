# VS-Code-Android-Termux-2022
Download the official VS Code for Android Termux - Ubuntu
- Download Visual Studio Code for Arm64 using the official Microsoft direct download link:
```bash
wget -0 code.deb "https://code.visualstudio.com/sha/download?build=stable&os=linux-deb-arm64"
```
- Make the file executable
```bash
chmod +x code.deb
```
- Install the code.deb
```bash
sudo dpkg -i code.deb
```
- Launch from terminal
```bash
code . --no-sandbox
```
