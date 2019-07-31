## What is Pastejacking
Nearly all browsers allow websites to run commands on the users’ computers. This feature can allow malicious websites to take over your computers’ clipboard. That is, when you copy something and paste it to your clipboard, the website can run one or more commands using your browser. The method can be used to change the Clipboard contents. While it may not be much dangerous if you are just copying to Notepad or Word etc. , it could be a problem for your computer if you paste something directly to the Command Prompt.

## Working:
1. Victim open the website with paste jacking script
2. Copies the written text. Powershell command is also being copied that is hidden in the source code of web page.
3. Pastes the copied text in CMD and PowerShell command get executed.
4. Gets a session.

## Tools :
1. Empire Post Exploitation framework. Used to generate powershell command.
2. PasteJacking HTML page. https://pastebin.com/DWycNqeg
