# How to Install Sturtz Shell on Linux
## What you need:
- A computer with internet access
- This computer has to be a Linux 
- Sudo
### Note This has only been tested on Ubuntu Server 20.04
## How to Install the Shell
1. Edit Your /etc/apt/sources.list file
  `nano /etc/apt/sources.list` 
2. Add the line `deb [trusted=yes] https://apt.sturtz.ml/apt/ / `  
3. Save and exit the file with ctrl+x y enter
4. Run `apt update`
5. Install `apt install sturtzshell`
6. You can run the shell with `sturtz`
