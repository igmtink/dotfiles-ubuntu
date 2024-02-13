# IGMT Workstation

### Tools & Technologies
- **Git:** Version control system for code and configuration.
- **Node.js:** JavaScript runtime environment.
- **Curl:** Command-line tool for downloading and scripting.
- **Rustup:** Toolchain installer for the Rust programming language.
- **Alacritty:** Terminal emulator with advanced customization options.
- **Fish:** User-firendly and interactive shell with a modern command-line experience.

## Installation
1. **Git:**
Use the following command to install Git:
```bash
sudo apt-get install git
```

2. **Node.js:**
Follow the official NodeSource instructions for your architecture:
[NodeSource](https://github.com/nodesource/distributions?tab=readme-ov-file#installation-instructions)

Alternatively, use this command:
```bash
curl -fsSL https://deb.nodesource.com/setup_21.x | sudo -E bash - &&\
sudo apt-get install -y nodejs
```

3. **Curl:**
Install Curl with this command:
```bash
sudo apt install curl
```

4. **Rustup:**
Follow the installation instructions on the Rustup website: [Rustup](https://rustup.rs/)

5. **Alacritty:**
Follow the manual installation steps on the Alacritty website: [Alacritty](https://github.com/alacritty/alacritty/blob/master/INSTALL.md#prerequisites)

6. **Fish**
- Add the Fish repository:
```bash
sudo apt-add-repository ppa:fish-shell/release-3
sudo apt update
```

- Install Fish:
```bash
sudo apt install fish
```

- Set Fish as your default shell:
```bash
chsh -s $(which fish)
```

- Logout and login for the change to take effect.
