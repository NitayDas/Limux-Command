## Basic File and Directory Commands
'''
ls          # List files and directories  
cd          # Change directory  
pwd         # Show current directory path  
mkdir       # Create a new directory  
rmdir       # Remove an empty directory  
rm          # Remove files or directories  
cp          # Copy files or directories  
mv          # Move or rename files or directories  
touch       # Create a new empty file  
cat         # Display file content  
'''

## File Viewing and Manipulation
'''
less        # View file content page by page  
more        # Similar to less, but with fewer features  
head        # Show first 10 lines of a file  
tail        # Show last 10 lines of a file  
tail -f     # Continuously monitor a file (e.g., logs)  
nl          # Number lines in a file  
wc          # Count lines, words, characters in a file  
cut         # Extract specific columns or fields  
sort        # Sort lines in a file  
uniq        # Remove duplicate lines  
'''

## Searching and Finding Files
'''
find        # Search files and directories  
locate      # Quickly find files by name  
grep        # Search for patterns in files  
which       # Show path of a command  
whereis     # Locate the binary, source, and man page  
'''

## User and Permissions
'''
chmod       # Change file permissions  
chown       # Change file owner  
chgrp       # Change group ownership  
whoami      # Show current user  
id          # Show user and group ID  
su          # Switch user  
sudo        # Run command with superuser privileges  
'''

## Process Management
'''
ps          # Show active processes  
top         # Monitor running processes  
htop        # Interactive process viewer (if installed)  
kill        # Terminate a process by PID  
killall     # Kill processes by name  
nice        # Start a process with priority  
renice      # Change priority of a running process  
'''

## Networking
'''
ping        # Test network connectivity  
ifconfig    # Show network interfaces (older systems)  
ip a        # Show network interfaces (modern systems)  
netstat     # Show network connections (deprecated)  
ss          # Display socket statistics  
curl        # Fetch web content from terminal  
wget        # Download files from the internet  
'''

## System Information and Monitoring
'''
uname -a    # Show system information  
df -h       # Show disk usage  
du -sh      # Show size of a directory  
free -h     # Show memory usage  
uptime      # Show how long the system has been running  
hostname    # Show or set the system hostname  
'''

## Package Management (Debian/Ubuntu)
'''
apt update              # Update package index  
apt upgrade             # Upgrade all packages  
apt install <package>   # Install a package  
apt remove <package>    # Remove a package  
'''
