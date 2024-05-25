# BadUSB Scripts
--------------------
All of these scripts are for educational purposes only and not intended to be used for any malicious purposes. This is to act as a library showcasing my progress more than anything. If someone is to use any of these scripts, it is essential to have prior consent from all parties involved. Many of these scripts I have created have been improved upon using ai programs. I will not be held responsible for any actions taken using any of the scripts mentioned below:

## VulnerabilityScanner:
This is a script intended to be ran by a flipper zero, utilizing a secondary USB for all results to be saved onto. This script will scan for vulnerabilities by the means of checking for outdated software, open ports, firewall and antivirus statuses, smbv1 status, network services, password and audit policies, and more. Then, this script will check for any CVEs that could be found and will save a results.txt file on the secondary USB in a folder with the PC name of the target machine being scanned. Logs will will also be saved onto that USB for further analysis if necessary.

## CredentialHarvester:
This is a script to be ran by the flipper zero, requiring a secondary USB. Name the secondary USB "MYUSB" and then plug it into the target windows machine. Then, the flipper is to be plugged in and the CredentialHarvester.txt script is to be ran. This script will take all of the credentials stored onto browsers such as Chrome, Firefox, and Edge- copying them onto the usb that is labeled MYUSB. Many of the files will either be encoded or encrypted, so due diligence is necessary when running this script (or any other script).

## RansomwareSimulation:
This script simulates a ransomware attack. Run this script by plugging in the flipper zero and running the ransomwaresimulation script. This changes all file extensions in specified directories to ".locked", preventing the use of them. This also disables task manager (requiring admin privileges) as well as displays a pop up referring to the simulated ransomware attack that has been modified to make it hard to close out off. You can revert all changes made by this script by running the RansomwareSimulationCleanup script. This is not a real ransomware attack, and is intended to be a simulation for educational purposes. 

## RansomwareSimulationCleanup:
This script is fairly self explanatory. It is a cleanup script to revert all changes made by the RansomwareSimulation script mentioned above. This should be ran after the RansomwareSimulation script to rename all file extensions back to their original names. If not all .locked files are reverted, run this script once more to confirm all changess and revert the extensions back to their original state.

## EmailSender:
This script is also fairly self explanatory. It opens up chrome and navigates to gmail (the account must be logged in), and then composes an email and sends it to a destination that you choose. You must actually type the email address and contents onto the script before this can be used. You can use this to automate emails. You can copy and paste the same script over and over in the same .txt file to send it to many emails at once. You can also use python if you have a massive amount of email addresses/names to automate this further. I can provide a python script for this if I get enough requests. Enjoy.

## EmailScriptGenerator.py:     
This is a python script to automatically create BadUSB scripts to auto send emails. This is similar to the EmailSender badUSB script, except this auto generates many emailsender badusb scripts to change emails and names based on an excel sheet with this information. This takes a excel sheet with the columns named "Names" and "Emails" and will then make a badusb script using the name + email of each person. There are various subject options that will be chosen from, to minimize "spam" detection if possible. If you want to keep the same subject for all emails, just paste the same thing to all 7 subject placeholders. Change the contents of the email to what you want to send and the signature to your name. This can be very useful in a business setting.
