# Demonstrate-IDS-Using-Any-Snort-Tool
# Date: 
# Register No.
# Aim: 
# Algorithm: AIM: To demonstrate Intrusion Detection System (IDS) using Snort software tool. 
STEPS ON CONFIGURING AND INTRUSION DETECTION:
 1. Download Snort from the Snort.org website. (http://www.snort.org/snort-downloads)
 2. Download Rules(https://www.snort.org/snort-rules). You must register to get the rules. (You should download these often) \
3. Double click on the .exe to install snort. This will install snort in the “C:\Snort” folder.It is important to have WinPcap (https://www.winpcap.org/install/) installed 
4. Extract the Rules file. You will need WinRAR for the .gz file. 
5. Copy all files from the “rules” folder of the extracted folder. Now paste the rules into “C:\Snort\rules” folder. 
6. Copy “snort.conf” file from the “etc” folder of the extracted folder. You must paste it into “C:\Snort\etc” folder. Overwrite any existing file. Remember if you modify your snort.conf file and download a new file, you must modify it for Snort to work. 
7. Open a command prompt (cmd.exe) and navigate to folder “C:\Snort\bin” folder. ( at the Prompt, type cd\snort\bin) 
 8. To start (execute) snort in sniffer mode use following command: snort 
-dev -i 3 -i indicates the interface number. You must pick the correct interface number. In my case, it is 3. 
-dev is used to run snort to capture packets on your network. To check the interface list, use following command: snort -W

Output:
Result:
