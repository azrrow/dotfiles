### Prerequisites:
- clean installation of Fedora Workshop 42
- Nvidia graphics card
### Instructions:
```bash
# Update system
sudo dnf update -y

# download Nvidia
sudo dnf install akmod-nvidia

# go through fedora-hyperland-end4 instructions
# https://github.com/EisregenHaha/fedora-hyprland

# install chezmoi
# https://www.chezmoi.io/install

# initialize chezmoi and point it to this repo
chezmoi init --apply azrrow

# Reboot and choose hyperland uwsm session to login
```
