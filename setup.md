## Install Notepad++
[https://notepad-plus-plus.org/](https://notepad-plus-plus.org/)
## Install Git
[https://git-scm.com/download/win](https://git-scm.com/download/win) 
## Config Github SSH
[https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)
1. Open Git Bash
2. Paste: `ssh-keygen -t ed25519 -C "your_email@example.com"`
3. Start the ssh-agent: `eval "$(ssh-agent -s)"`
4. Adding SSH key to the ssh-agent: `ssh-add ~/.ssh/id_ed25519`
5. Copy SSH public key to clipboard: `clip < ~/.ssh/id_ed25519.pub`
6. Go to: [https://github.com/settings/keys](https://github.com/settings/keys)
7. Click **New SSH key** and paste key.


## Install Windows Subsystem for Linux
[https://docs.microsoft.com/en-us/windows/wsl/install-win10](https://docs.microsoft.com/en-us/windows/wsl/install-win10)
1. Enable the Windows Subsystem for Linux
    - Open PowerShell as Administrator
    - Run `dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart`
2. Enable Virtual Machine feature
    - Open PowerShell as Administrator
    - Run `dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart`
3. Download the Linux kernel update package
    - Download package: [https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi)
    - Run package
4. Restart computer
5. Set WSL 2 as default version
    - Open PowerShell
    - Run: `wsl --set-default-version 2`
6. Install Linux
    - Open [ Microsoft Store](https://aka.ms/wslstore)
    - Install Ubuntu
## Install Windows Terminal (optional)
[https://docs.microsoft.com/en-us/windows/terminal/get-started](https://docs.microsoft.com/en-us/windows/terminal/get-started)

## Install Visual Studio Code
[https://code.visualstudio.com/](https://code.visualstudio.com/)