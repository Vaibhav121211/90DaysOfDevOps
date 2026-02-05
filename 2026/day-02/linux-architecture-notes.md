# Day 02 – Linux Basics Notes 🐧

Today I learned some basic concepts about how **Linux works internally**, which are very important for **DevOps and server management**.

---

## 🧩 Main Parts of Linux

Linux has **three main parts**:

### 1️⃣ Kernel
- Kernel is the **core part** of Linux.
- It controls:
  - CPU
  - Memory
  - Disk
  - Hardware devices
- All programs run **with the help of the kernel**.

---

### 2️⃣ User Space
- This is the space where **users interact with the system**.
- We:
  - Type commands
  - Run programs
- Examples:
  - Terminal
  - Applications
- User space communicates with the **kernel** to perform tasks.

---

### 3️⃣ systemd
- `systemd` is the **first process** that starts when the system boots.
- Responsibilities:
  - Starts all required system services
  - Manages running services
  - Restarts services if they fail
  - Maintains logs

---

## ⚙️ Processes in Linux

- A **process** is a program that is currently running.
- When we run any command:
  - A new process is created
- Each process has a unique number called **PID (Process ID)**.
- One process can create another process.

---

## 📌 Process States

Common process states I noted:

- **Running** – Process is executing
- **Sleeping** – Process is waiting for resources
- **Zombie** – Process has finished but not fully removed
- **Stopped** – Process execution is paused

---

## 🔧 systemd and Service Management

- `systemd` helps manage **services** on Linux.
- We can:
  - Start services
  - Stop services
  - Restart services
  - Check service status
- It can automatically restart services if they stop.
- Logs can also be checked using `systemd` tools.

---

## 🧪 Important Linux Commands (Daily Use)

```bash
ps                    # View running processes
top                   # Monitor CPU and memory usage
systemctl status nginx # Check status of nginx service
journalctl            # View system logs
kill PID              # Stop a process using PID
