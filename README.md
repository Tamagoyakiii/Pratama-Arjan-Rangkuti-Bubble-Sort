# Bubble Sort
This repository contains how to execute a Bubble sort program in python using MPI with an Ubuntu Master & 2 Ubuntu Slave.
## Topology
![image](https://github.com/Tamagoyakiii/Pratama-Arjan-Rangkuti-Bubble-Sort/assets/150600551/7198f003-9804-4498-baf0-e85683ec4e37)
## 1. Upgrade OS
Using the 'sudo apt update && sudo apt upgrade' command to update the operating system on every device.
## 2. Install Net-Tools 
Performing the installation of net-tools using the command 'sudo apt install net-tools' to check the IP address.
## 3. Konfigurasi File  
Opening the file /etc/hosts using the command 'sudo nano /etc/hosts'.
## 4. Konfigurasi SSH
Configuring SSH (Secure Shell) is used for secure authentication and data exchange between nodes in an MPI cluster. Installing SSH can be done using the command 'sudo apt install openssh-server'.
## 5. Install NFS Client
Configuration of NFS (Network File System) involves the process of setting up and configuring a file system that allows sharing files between computers in a network.
## 6. Install MPI
MPI stands for "Message Passing Interface." It is a communication standard used in parallel programming, especially in distributed programming for cluster-based or supercomputer systems. Installing MPI can be done using the command 'sudo apt install openmpi-bin libopenmpi-dev'.
## 7. Konfigurasi Python
Installing Python version 3 using the command 'sudo apt install python3'.
## 8. Menjalankan Bubble
Running the edited file using the command 'mpirun -n <number of processes> -hostfile <host list> python3 <filename>.py'.
![image](https://github.com/Tamagoyakiii/Pratama-Arjan-Rangkuti-Bubble-Sort/assets/150600551/d48e9133-b252-48d5-8392-21144655eb40)
![image](https://github.com/Tamagoyakiii/Pratama-Arjan-Rangkuti-Bubble-Sort/assets/150600551/f4e6fff2-c707-47ee-9fd8-dc924ec7f836)

