The included portScanner.py script was created by Arman "The
Automator" Vakili.
Los Angeles, CA
www.armanvakili.com
For contact use: armantheautomator@gmail.com


**********
portScanner.py
**********
The Port Scanner does exactly what the name implies. 

Note: Chances are that you don't have the "pyfiglet" module installed 
on your machine. To install it, run the command "apt install 
python3-pyfiglet" on your terminal. Moreover, the pyfiglet module isn't 
necessary for the functionality of the script, so if you don't want to 
install it, simply remove "pyfiglet" from the top import line, and remove 
the first two lines of code right below that. (ascii_banner, 
print(ascii_banner))


Use:

Upon running, portScanner.py will ask you what IP address you want to 
scan. 
Enter the IP address to be scanned. 
Upon completion, the scanner will output onto the screen all of the open 
ports of the IP address. 

The default range of ports is 1-65535, which means all of the ports will 
be scanned. 
If you want to change this to a specific range of ports, you can do so by 
changing the "ports" variable to the range of ports you want to scan. 
If you want to only scan a handful of specific ports, change the "ports" 
variable from: 
ports = range(1, 65535)
to:
ports = { 21, 22, 23, 53, 80, 135, 443, 445} 

Make sure to change the paranthesis () to brackets {}.

Alright, that should be it. 

Happy scanning!

- 
Arman "The Automator" Vakili

