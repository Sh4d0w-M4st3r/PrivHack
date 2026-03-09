# PrivHack

PrivHack its an bash framework developed to find weak points on Linux local systems.
This means that tool scans youre system, to try find, or do attacks between his modules: 

Possible privilege scalation vulns (like SUID, very open permission, or sensitive/critical files with r+w).

Dangerous commands that are installed that allow possible attacks or malware injection without been root user.

Checks if current user is in root group (has or not privileges).

Brute force to root account (but can be other).

And an special bypass for alphabetic blocking characters using only symbols.
(This one in an real scenario you cant use the framework because (literally you have blocked alphabetic characters...) 
so you will need to do it manually but i leave anyway the payload on tool, to show you how works...).

---------------------
###REQUERIMENTS###
---------------------

Commands or tools: N/A can work without nothing installed is full system commands.

Root: The tool doesn't require root, is designed to work without root to test OS local system vulns or attacks.

Dictionary: By default the tool comes with an mini dictionary version from famous rockyou.txt but you can use other dictionary.

---------------------
###Execution###
---------------------

git clone https://github.com/Sh4d0w-M4st3r/PrivHack.git && 
cd PrivHack && chmod +x PrivHack.sh && bash PrivHack.sh
