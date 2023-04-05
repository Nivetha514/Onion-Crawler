# Onion-Crawler
We have created a Onion crawler to scrape data from Darkweb using TOR Network

Steps:
1. Configure TOR Control Port 
 If using unix environment go to "/etc/tor/torrc" file and uncomment "#ControlPort 9051" and hash password.
2. Use command "tor --controlport 9051" to enable control port
3. Reset hash password using "tor --hash-password 'your_password'" to generate hash password and put it in torrc file in place of hashcontrolpassword value.
4. Check if the control port is working using "telnet localhost 9051" and check authentication using 'AUTHENTICATION "your_password"'.
5. Check if all the dependencies are installed.
6. Run the code using "python3 DARKWEB.py" command.
