# SSH-Cracker
The objective of this project is to develop an SSH brute-force tool that tests username-password combinations to gain unauthorized access to an SSH server.
- This project consists of two Python scripts:
1. advance_brute.py – An advanced SSH brute-forcing script that supports
username lists, password lists, password generation, multi-threading, and retry
mechanisms.
2. brute.py – A simple SSH brute-force script that accepts a single username and a
password list.
The tool attempts to connect to an SSH server by iterating through different username-password
pairs. If successful, it saves the credentials to a file.
