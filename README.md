# SETOOLKIT
The Social-Engineer Toolkit (SET) is specifically designed to perform advanced attacks against the human element. 
It was designed to be released with the http://www.social-engineer.org launch and has quickly became a standard tool in a penetration testers arsenal.
The attacks built into the toolkit are designed to be focused attacks against a person or organization used during a penetration test.

# Usage 
SET by default works perfect for most people however, advanced customization may be needed in order to ensure that the attack vectors go off without a hitch. First thing to do is ensure that you install the requirements for this tool from the directory by this command:
```
(professor㉿kali)-[~/setoolkit]
└─$ pip3 install -r requirements.txt 
```
After that, make sure that you have updated SET, from the directory:
```
(professor㉿kali)-[~/setoolkit]
└─$ ./set-update 
```
Once you’ve updated to the latest version, start tweaking your attack by editing the
SET configuration file :
```
(professor㉿kali)-[~/setoolkit]
└─$ nano config/set_config
```
And finally you can run it normally by running setoolkit file :
```
(professor㉿kali)-[~/setoolkit]
└─$ ./setoolkit 
```
If it show up like this : ./setoolkit: command not found   then make it excutable by the following command (and repeat last command after it) :
```
(professor㉿kali)-[~/setoolkit]
└─$ chmod +x setoolkit
```
