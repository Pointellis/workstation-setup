# Workstation Setup

This project automates the process of setting up a new Pointellis machine using a simple [Bash](https://www.gnu.org/software/bash/) script.

## Getting Started

- Run the latest version of macOS, currently [High Sierra](https://www.apple.com/macos/high-sierra/),
  unless you have a specific reason not to
- These scripts might work on previous versions, but are maintained with only the latest macOS in mind
- If you are not on High Sierra, you need to install the latest version of [Xcode](https://developer.apple.com/xcode/)
- On High Sierra, once you have used git (below), you will have installed the command line developer tools

Open up Terminal.app and run the following commands:

```sh
xcode-select --install
mkdir -p ~/workspace
cd ~/workspace
git clone https://github.com/Pointellis/workstation-setup.git
cd workstation-setup
./setup.sh
```
