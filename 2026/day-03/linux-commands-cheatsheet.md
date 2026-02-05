# Linux Commands Cheat Sheet – Day 03 🐧

**Name:** Vaibhav Sharma 
**Goal:** Daily Linux practice for DevOps 🚀

---

## 📁 File System Commands

```bash
pwd                 # Shows current directory path
ls                  # List files and folders
ls -la              # Show hidden files with details
cd foldername       # Move into a folder
cd ..               # Go one step back
mkdir test          # Create a new folder
touch file.txt      # Create an empty file
rm file.txt         # Delete a file
rm -r folder        # Delete a folder with files
cp a.txt b.txt      # Copy a file
mv old.txt new.txt  # Rename or move a file
cat file.txt        # Show file content
less file.txt       # View large file page by page
head file.txt       # Show first 10 lines of a file
tail file.txt       # Show last 10 lines of a file
tail -f app.log     # Live log monitoring

---

## 📁 Process Management

```bash
ps                  # Show running processes
ps aux              # Detailed process list
top                 # Real-time process monitoring
htop                # Better version of top (if installed)
kill PID            # Stop a process by PID
kill -9 PID         # Force stop a process
jobs                # Show background jobs
bg                  # Run job in background
fg                  # Bring job to foreground

Networking & Troubleshooting
ping google.com           # Check internet connectivity
ip addr                   # Show IP address details
ss -tuln                  # Check open ports and services
curl https://example.com  # Test API or website response
dig google.com            # DNS lookup information

Disk & System Information
df -h              # Disk space usage
du -sh folder      # Folder size
free -h            # Memory usage
uptime             # System running time
uname -a           # System information

