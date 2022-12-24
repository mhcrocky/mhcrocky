### install gui

```
sudo apt update
sudo apt upgrade
sudo apt install tasksel
tasksel
sudo apt update
sudo apt upgrade
sudo apt install lightdm


```
### install anydesk
```
sudo apt update
sudo apt -y upgrade
curl -fsSL https://keys.anydesk.com/repos/DEB-GPG-KEY|sudo gpg --dearmor -o /etc/apt/trusted.gpg.d/anydesk.gpg
echo "deb http://deb.anydesk.com/ all main" | sudo tee /etc/apt/sources.list.d/anydesk-stable.list
sudo apt update
sudo apt install anydesk

echo "qweQWE::" | anydesk --set-password

```

### install google chrome

```
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i google-chrome-stable_current_amd64.deb

```

