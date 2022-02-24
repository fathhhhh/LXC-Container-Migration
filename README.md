# LXC-Migration
We are using rsync to execute the migration

1. Get ready your linux container, and your destination VM
2. SSH into your linux container and run the "Telipot" script
3. Make sure your destination VM can be access using root user through SSH, if not you need to run "airport" script on your VM to enable root your and install rsync in not available
4. Run "Telipot" script on your VM and put your destination VM IP and Username 
![image](https://user-images.githubusercontent.com/67633326/155491908-96c79511-b876-4a3b-ab6d-7ff3a5a31d2b.png)
5. After migration complete restart your VM and use your LCX credential
6. Try run your services

