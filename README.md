═══════════════════════════════════════════════════════════════════════════════
                      VERIFY INDIA - INSTALL COMMANDS
                        Copy-Paste Ready | One Shot
═══════════════════════════════════════════════════════════════════════════════

┌─────────────────────────────────────────────────────────────────────────────┐
│ 📱 TERMUX (Android)                                                        │
└─────────────────────────────────────────────────────────────────────────────┘

pkg update && pkg upgrade -y
pkg install python git -y
pip install requests
git clone https://github.com/CyberSuraj/verify_india.git
cd verify-india
python verify_india.py

┌─────────────────────────────────────────────────────────────────────────────┐
│ 🐧 KALI LINUX                                                              │
└─────────────────────────────────────────────────────────────────────────────┘

sudo apt update && sudo apt upgrade -y
sudo apt install python3 python3-pip git -y
pip3 install requests
git clone https://github.com/CyberSuraj/verify_india.git
cd verify-india
python3 verify_india.py

┌─────────────────────────────────────────────────────────────────────────────┐
│ 🐧 UBUNTU / DEBIAN                                                         │
└─────────────────────────────────────────────────────────────────────────────┘

sudo apt update && sudo apt upgrade -y
sudo apt install python3 python3-pip git -y
pip3 install requests
git clone https://github.com/CyberSuraj/verify_india.git
cd verify-india
python3 verify_india.py

┌─────────────────────────────────────────────────────────────────────────────┐
│ 🪟 WINDOWS (PowerShell)                                                    │
└─────────────────────────────────────────────────────────────────────────────┘

python --version
pip install requests
git clone https://github.com/CyberSuraj/verify_india.git
cd verify-india
python verify_india.py

┌─────────────────────────────────────────────────────────────────────────────┐
│ 🍎 macOS                                                                   │
└─────────────────────────────────────────────────────────────────────────────┘

brew install python3 git
pip3 install requests
git clone https://github.com/CyberSuraj/verify_india.git
cd verify-india
python3 verify_india.py

┌─────────────────────────────────────────────────────────────────────────────┐
│ 🎩 ARCH LINUX / BLACKARCH                                                  │
└─────────────────────────────────────────────────────────────────────────────┘

sudo pacman -Syu
sudo pacman -S python python-pip git
pip install requests
git clone https://github.com/CyberSuraj/verify_india.git
cd verify-india
python verify_india.py

═══════════════════════════════════════════════════════════════════════════════
                              ⚡ ONE-LINERS ⚡
═══════════════════════════════════════════════════════════════════════════════

TERMUX:
pkg update -y && pkg install python git -y && pip install requests && git clone https://github.com/CyberSuraj/verify_india.git && cd verify-india && python verify_india.py

KALI / UBUNTU:
sudo apt update -y && sudo apt install python3 git -y && pip3 install requests && git clone https://github.com/CyberSuraj/verify_india.git && cd verify-india && python3 verify_india.py

ARCH / BLACKARCH:
sudo pacman -Syu --noconfirm && sudo pacman -S python git --noconfirm && pip install requests && git clone https://github.com/CyberSuraj/verify_india.git && cd verify-india && python verify_india.py

═══════════════════════════════════════════════════════════════════════════════
