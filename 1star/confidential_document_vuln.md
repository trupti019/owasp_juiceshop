#Title: Confidential Document
#Category: Sensitive Data Exposure

The challenge involves accessing and retrieving a confidential document named acquisition.md from an FTP server.

I solved this in the following ways:

1. Using Wireshark:
   What I basically did here is intercepted the request where i tried to open the legal.md file.
Sent the request to the repeater.

Found a directory listed when i deleted legal.md from the request.
Twitched some inputs .
Discovered other files through href.

![Screenshot 2025-06-09 215145](https://github.com/user-attachments/assets/f366aa39-b2e0-4a1d-9476-3ce397c6838b)

2.Access the FTP Server--- Navigated to the FTP server hosted at 127.0.0.1:3000/ftp using a web browser
![image](https://github.com/user-attachments/assets/72ab9ffe-4e98-43eb-a60f-f61a43ddd45e)

![confidential_document_1](https://github.com/user-attachments/assets/11a7da21-e622-46bf-b0fc-560f904a0d86)
