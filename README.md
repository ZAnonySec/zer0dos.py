# zer0dos.py
zer0dos.py is a powerful Python script for network stress testing, capable of flooding target systems with HTTP requests using raw sockets, making it effective for testing network resilience and performance.

# Requirements

pip install requests colorama termcolor ping3 psutil

# How to Run It
First, download it. Once located in the terminal, execute:

python3 zer0dos.py        

Example: python3 zer0dos.py -d example.com -p 8080 -t 10 -s 0.1 -T 200

# More Example Commands to Run zer0dos.py with Different Options:
. python zer0dos.py -d example.com: Attack example.com on port 80 with default settings.

. python zer0dos.py -d example.com -p 8080: Attack example.com on port 8080 with default timeout, sleep time, and threads.

. python zer0dos.py -d example.com -t 10 -s 0.1 -T 200: Attack example.com with a timeout of 10 seconds, sleep time of 0.1 seconds, and 200 threads.

. python3 zer0dos.py -d example.com -p 8080 -t 10 -s 0.1 -T 200

# Features and Strengths:

# DDoS Simulation: Simulates Distributed Denial of Service (DDoS) attacks to stress-test network infrastructure.

# Threaded Attack: Utilizes multiple threads (-T option) to maximize attack efficiency and intensity.

# Customizable Parameters: Allows customization of target (-d), port (-p), timeout (-t), sleep interval (-s), and number of threads (-T).

# Built-in Ping Monitoring: Incorporates live ping monitoring to track target responsiveness during the attack.

# Data Transfer Monitoring: Monitors data transfer metrics (e.g., MB sent) during the attack to gauge impact on network traffic.

# Dynamic User-Agent Support: Randomly selects user-agents from a file (ua.txt) for diverse request headers.

# Cross-platform Compatibility: Works on Windows and Unix-like operating systems (Linux, macOS).

# Dependency on Ping3 Library: Utilizes the ping3 library for ICMP ping functionality.

# Informative Output: Provides detailed output during the attack, including ping times and data transfer statistics.

# Flexible Attack Methods: Supports both HTTP GET and POST methods for varied attack scenarios.

![22](https://github.com/user-attachments/assets/ab5a063f-a227-474b-9b6b-05e544d88ffa)
![dos](https://github.com/user-attachments/assets/c17bf7c2-45ab-44bf-8ffa-d8ccd881c523)
