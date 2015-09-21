Here's the deal:
The server is set up with the stuff you guys requested, as well as phpmyadmin. It's plugged in and sitting behind the grey filing cabinet behind the front desk. Just power it up and it should be good to go. You should be able to do everything you need to via ssh/scp (or just plug in a flash drive with your files).

WiFi:
SSID BikechainWiFi Password !iatvmoammg!

Server access info:
IP address: 192.168.1.234
User bikechain Password Ru618B>en\
User root      Password L!nnM0nkx

MySQL:
User root Password De/R3if1Icht

You should be able to do whatever you need to do using the bikechain user. Only use the root user if you explicitly need to change the server config or install something. The apache web root is /home/bikechain/public_html, so place your files there. The current index.php in there just runs phpinfo(); to make sure php is working.

I don't know what sort of access you need the internet to have to the server at this point. The current router config forwards HTTP stuff (port 80) to the existing old machine sitting in the corner. Assuming your current system only needs to be accessed from the shop this should be fine for now, as long as the service you're using to send text messages works. I can set up SSH access from the outside world in the near future but we'll have to use RSA keys rather than plain passwords. 

In case you do need to access the router settings, you'll need to go to 192.168.1.1 on a machine connected via ethernet (NOT WIFI) and use admin/b1k3ch41n0 to log in. Don't fuck things up on there though, since it's kinda critical for the entire shop and existing server to run correctly. The only wired machine in the shop you can use is the one at the counter on the right, since everything else is wireless. This is, of course, the machine with a keyboard that feels like a long pelican shit and it's running XP so it's totally secure.

I'm pretty sure I forgot about something critical so if you need to reach me you can try email or hangouts at dima.kokarovtsev@gmail.com or text me at 647 985 7596.

--Dima