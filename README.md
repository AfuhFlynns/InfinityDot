# InfinityDot 🚀✨

[![Version](https://img.shields.io/vscode-marketplace/v/yourpublisher.extension-name)](https://marketplace.visualstudio.com/items?itemName=yourpublisher.extension-name)
[![Downloads](https://img.shields.io/vscode-marketplace/d/yourpublisher.extension-name)](https://marketplace.visualstudio.com/items?itemName=yourpublisher.extension-name)

## 📜 Table of Contents

- [🌟 Overview](#overview)
- [⚡ Features](#features)
- [📥 Installation](#installation)
- [🛠️ Usage](#usage)
- [⚙️ Configuration](#configuration)
- [🤝 Contributing](#contributing)
- [📜 License](#license)
- [💡 Support](#support)

## 🌟 Overview

**InfinityDot** is a comprehensive Visual Studio Code extension that brings full language support for .NET development, including C#, VB.NET, F#, Blazor, and more. With features like executing code via `dotnet run`, integrated compilation and debugging, and intelligent intellisense, this extension is designed to boost productivity and streamline your development workflow. 🖥️💡

![InfinityDot Banner](https://via.placeholder.com/1200x400.png?text=InfinityDot+Banner)

## ⚡ Features

- **🚀 Run .NET Code:**  
  Execute projects with the `dotnet run` command directly from VS Code.
- **🛠️ Compilation & Debugging:**  
  Integrated debugging tools including breakpoints, watch windows, and call stack analysis.
- **🧠 Enhanced Intellisense:**  
  Smart code completion, inline error checking, and navigation support for multiple .NET languages.
- **🎯 Additional Tools:**  
  Custom code snippets, real-time error highlighting, code refactoring, and more.
- **🔗 Seamless Integration:**  
  Works harmoniously with your existing .NET toolchain and libraries.

## 📥 Installation

1. Open Visual Studio Code.
2. Navigate to the Extensions view (`Ctrl+Shift+X`).
3. Search for **InfinityDot**.
4. Click **Install**.
5. Reload VS Code if prompted.

**Prerequisites:**  
Make sure you have the .NET compiler installed on your system. Download it from [dotnet.microsoft.com](https://dotnet.microsoft.com/en-us/download).
**If you are using linux or mac or just want the terminal:**

**1.** chocolatey on windows: 
> Open powershell as administrator
> First install choco:

```bash
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

> Install dotnet sdk:
```bash
choco install dotnet-sdk -y
```

_Note: For other distributions or .NET versions, refer to the [official Microsoft documentation for windows](https://docs.microsoft.com/dotnet/core/install/windows)_

**2.** Linux (Ubuntu/Debian-based):
> Open the terminal with _ctrl + alt + t_

```bash
# Download the Microsoft package repository configuration
wget https://packages.microsoft.com/config/ubuntu/20.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb

# Install the package repository configuration
sudo dpkg -i packages-microsoft-prod.deb

# Remove the downloaded file (optional)
rm packages-microsoft-prod.deb

# Install necessary HTTPS transport package
sudo apt-get update
sudo apt-get install -y apt-transport-https

# Update package lists and install the .NET SDK (example uses .NET 6.0)
sudo apt-get update
sudo apt-get install -y dotnet-sdk-6.0
```

_Note: For other distributions or .NET versions, refer to the [official Microsoft documentation for linux](https://docs.microsoft.com/dotnet/core/install/linux)_

**3.** macOS (using Homebrew):
> Open the terminal with Command (⌘) + Space
> Update or install homebrew and install dotnet sdk:

```bash
brew update
brew install --cask dotnet-sdk
```
_Note: For other distributions or .NET versions, refer to the [official Microsoft documentation for macos](https://docs.microsoft.com/dotnet/core/install/macos)_

**For more info checkout dotnet docs: [.NET documentation](https://learn.microsoft.com/en-us/dotnet/)**

## 🛠️ Usage

- **▶️ Running Code:**  
  Open your .NET project and run the `Run .NET Code` command from the Command Palette (`Ctrl+Shift+P`).
- **🐞 Debugging:**  
  Set breakpoints and launch the debugger using the provided configurations.
- **✨ Intellisense:**  
  Enjoy intelligent code suggestions as you type in supported languages.
- **📂 Creating a New .NET Project:**  
  Use the command `dotnet new console` to create a new project. By default, a C# project is generated. If you provide an optional parameter `--language <language extension>` (for example, `--language fs` for F#, or `--language vb` for VB.NET), InfinityDot will generate the corresponding project using your installed .NET compiler.  
  **Note:** The command creates an application based on the text following `dotnet new console`. Currently, InfinityDot does not support GUI programming, but this feature is planned for future releases.

_For detailed usage and configuration options, please refer to our [GitHub Repository](https://github.com/AfuhFlynns/InfinityDot)._

![Usage Example](https://via.placeholder.com/800x400.png?text=Usage+Example)

## ⚙️ Configuration

Customize **InfinityDot** settings via `File > Preferences > Settings` and search for `InfinityDot`.

## 🤝 Contributing

Contributions are welcome! Please see our [Contribution Guidelines](CONTRIBUTING.md) for more information on how to help improve **InfinityDot**. 💙

## 📜 License

InfinityDot is released under the [MIT License](LICENSE.md).

## 💡 Support

If you encounter issues or have suggestions, please open an issue on our [GitHub Repository](https://github.com/AfuhFlynns/InfinityDot). 🛠️💬

---

🎉 *Happy Coding!* 🚀
