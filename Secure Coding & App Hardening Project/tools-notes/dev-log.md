## 📅 Day 1 — 1-12-2025

### 🎯 Goal
Configure and install a Windows 10 Pro VM on VMWare Workstation 17 Player to run on the home network.  

### 🔨 What I did
Steps:
- Downloaded a Windows 10 Pro ISO file from the Microsoft website
- Created a new virtual machine on VMWare Workstation 17 Player and allocated sufficient resources to run a Windows machine (16GB RAM, 4 processor cores, 100GB storage)
- Connected the Windows 10 VM to the internet through Bridged mode for the network adapter

Tools used:
CMD Prompt

Commands used:
ipconfig /all

### 🐞 Issues / Roadblocks
- What didnt work
- Errors encountered
- Misconfigurations or confusion

- Unable to connect the VM to the internet even though it was directly connected to the home network through the Bridged adapter.

### 🧠 What I learned
- Security concepts learned
- Mistakes corrected
- Why something was insecure

- The VM was misconfigured to automatically connect to both the VirtualBox Host-Only Ethernet Adapter and Realtek (home network) adapter which caused internet connectivity problems
- When enabling both options, the VM can pick either adapter but often selects the wrong one (VirtualBox adapter) which is a fake, isolated adapter with no internet access by design
- The Realtek adapter is the real physical Ethernet adapter that connects to the router with internet access that provides VM with an IP, default gateway and DNS

### ⏭️ Next session
- Install all project tools and applications
________________________________________________________________________________________________________________________________________________________________________________________________________________________

## 📅 Day 2 — 28-12-2025

### 🎯 Goal
Install all the tools and applications within the scope of the project.

### 🔨 What I did
- Step-by-step actions taken
- Tools used
- Commands run (if useful)

### 🐞 Issues / Roadblocks
- What didn’t work
- Errors encountered
- Misconfigurations or confusion

### 🧠 What I learned
- Security concepts learned
- Mistakes corrected
- Why something was insecure

### ⏭️ Next session
- Clear next steps
________________________________________________________________________________________________________________________________________________________________________________________________________________________

## 📅 Day 3 — 01-01-2026

### 🎯 Goal
Setup Git to remotely connect to my Github repo and update changes made.

### 🔨 What I did
- Step-by-step actions taken
- Tools used
- Commands run (if useful)

### 🐞 Issues / Roadblocks
- What didn’t work
- Errors encountered
- Misconfigurations or confusion

### 🧠 What I learned
- Security concepts learned
- Mistakes corrected
- Why something was insecure

### ⏭️ Next session
- Clear next steps
