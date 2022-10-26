# Vanilla OS Packages Repository

## Setup (for Kinetic)
```bash
curl -s --compressed "https://repo.vanillaos.org/kinetic/KEY.gpg" | gpg --dearmor | sudo tee /usr/share/keyrings/vanilla-archive-keyring.gpg
sudo curl -s --compressed -o /etc/apt/sources.list.d/vanilla-os.list "https://repo.vanillaos.org/kinetic/vanilla-os.list"
sudo apt update
```

for other versions, change the codename from kinetic to the other one.
