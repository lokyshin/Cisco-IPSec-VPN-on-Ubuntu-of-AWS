# Cisco-IPSec-VPN-on-Ubuntu-of-AWS
Cicso IPSec VPN on Ubuntu of AWS
This code could help you to setting your Cicco IPsec VPN on Ubuntu operation system of AWS.
When you creat one instance and login in your E2 of AWS, you just cope the code to your "~" directory.
After your chmod the .sh file (chmod -R 777 civaws_install.sh or chmod +x civaws_install.sh), you can bash civaws_install.sh to install Cisco IPSec VPN on your server.
Pls note, you also can one-key install it following the commond as bellow:
wget --no-check-certificate http://lokyshin.com/code/civaws_install.sh && chmod +x civaws_install.sh && bash civaws_install.sh 2>&1 | tee civaws_install.log
