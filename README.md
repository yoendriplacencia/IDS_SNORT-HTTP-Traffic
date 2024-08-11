# IDS_SNORT-HTTP-Traffic
Creating a single rule to detect "all TCP port 80 traffic" packets using SNORT, that is a free open-source network intrusion detection system (IDS) and intrusion prevention system (IPS)

# 1- Initializng Snort on Ubuntu.

![Screenshot 2024-08-11 182842](https://github.com/user-attachments/assets/85a6f608-fbfb-4a92-8cd0-cfc1425f23e7)

# 2- Creating the Local Rules.
We have to create the new local rules in order to detect all TCP 80 traffic

![Screenshot 2024-08-11 164724](https://github.com/user-attachments/assets/bf0b41a9-d62f-475b-b97a-b43a4a6e8199)

# 3- Running in IDS mode 
With this step we are able to detect and initiate the new rules and plugins. Finding all the packet information.

![Screenshot 2024-08-11 143605](https://github.com/user-attachments/assets/52313b78-c9ff-480f-aa52-3b27dc7a3131)

![Screenshot 2024-08-11 143926](https://github.com/user-attachments/assets/b9c85dba-8b3c-48b2-91fa-781dda04b1d9)

# 4- Read especific Snort_log_file 
If you need to access to a specific package, you need to add the command " -ntc {packet number} " after the snort log file.

![Screenshot 2024-08-11 191642](https://github.com/user-attachments/assets/24e3b431-b1bd-4dc9-ab11-45f68ddbf929)
