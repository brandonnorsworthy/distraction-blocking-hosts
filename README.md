# Host Blocker
This is a list of hosts that are algorithmically designed to occupy your time, using the host file of your computer you can add some more friction for you to disable it. Helps to destroy habits.

You can obviously remove any domains you want to keep :)

## Instructions
1. Open your hosts file:  
  Windows: `C:\Windows\System32\drivers\etc\hosts`  
  Mac/Linux: `/etc/hosts`  

1. Copy and Paste the list above to the bottom of your hosts file.  
  *note* if your host file already contains some data, paste this list at the end  

1. Save the file  
  Windows: Run Notepad as Administrator, then open and save the hosts file.  
  Mac/Linux: Use sudo nano /etc/hosts and enter your password.  

1. Clear DNS Cache to apply changes *(may not be required)*  
  Windows: Run ipconfig /flushdns in Command Prompt.  
  Mac: Run sudo dscacheutil -flushcache and sudo killall -HUP mDNSResponder in Terminal.  
  Linux: Run sudo systemd-resolve --flush-caches or restart your computer.  

## Devices
- Mac/Linux: `/etc/hosts`
- Windows: `C:\Windows\System32\drivers\etc\hosts`
- iOS: Use DNS blocker and use this host list as your domains. Eg: Use NextDNS :)
