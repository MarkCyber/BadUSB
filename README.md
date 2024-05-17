# BadUSB
All of these scripts are for educational purposes only and not intended to be used for any malicious purposes. This is to act as a library showcasing my progress more than anything. If someone is to use any of these scripts, it is essential to have prior consent from all parties involved. Many of these scripts I have created have been improved upon using ai programs. I will not be held responsible for any actions taken using any of the scripts mentioned below:

# CredentialHarvester:
This is a script to be ran by the flipper zero, requiring a secondary USB. Name the secondary USB "MYUSB" and then plug it into the target windows machine. Then, the flipper is to be plugged in and the CredentialHarvester.txt script is to be ran. This script will take all of the credentials stored onto browsers such as Chrome, Firefox, and Edge- copying them onto the usb that is labeled MYUSB. Many of the files will either be encoded or encrypted, so due diligence is necessary when running this script (or any other script).

# RansomwareSimulation:
This script simulates a ransomware attack. Run this script by plugging in the flipper zero and running the ransomwaresimulation script. This changes all file extensions in specified directories to ".locked", preventing the use of them. This also disables task manager (requiring admin privileges) as well as displays a pop up referring to the simulated ransomware attack that has been modified to make it hard to close out off. You can revert all changes made by this script by running the RansomwareSimulationCleanup script. This is not a real ransomware attack, and is intended to be a simulation for educational purposes. This is currently a work in progress.

# RansomwareSimulationCleanup:
This script is fairly self explanatory. It is a cleanup script to revert all changes made by the RansomwareSimulation script mentioned above. This should be ran after the RansomwareSimulation script to rename all file extensions back to their original names.

# EmailSender:
This script is also fairly self explanatory. It opens up chrome and navigates to gmail (the account must be logged in), and then composes an email and sends it to a destination that you choose. You must actually type the email address and contents onto the script before this can be used. You can use this to automate emails. You can copy and paste the same script over and over in the same .txt file to send it to many emails at once. You can also use python if you have a massive amount of email addresses/names to automate this further. I can provide a python script for this if I get enough requests. Enjoy.
