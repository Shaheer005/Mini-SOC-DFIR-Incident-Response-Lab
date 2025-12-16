# Ubuntu Victim Setup

## Installed Packages
- auditd
- audispd-plugins

## Commands Used
```bash
sudo apt update
sudo apt install auditd audispd-plugins -y
sudo systemctl enable auditd
sudo systemctl start auditd
