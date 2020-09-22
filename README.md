# AndroidVPN-OpenVPN
VPN application using OpenVPN servers. This test application uses VPN configuration files from https://www.vpngate.net/en/.


Android VPN app based on OpenVPN library.

</br>
<img height='450' width ='250' src="https://i.imgur.com/5GV1Y2L.gif" />
</br></br>

## Note

I use free OpenVPN configuration file from this site https://www.vpngate.net/en/ </br>
I am not sure how long it will work with the free ovpn file. It's better to update ovpn files with your own ovpn.
</br></br>

## Instruction to update server list:
1. Replace/add your .ovpn file with <b> assets/</b> directory .ovpn file
2. Now go to MainActivity.class and find the "getServerList()" method there you have to update server information.
3. [!Optional] At Last go to SharedPreference.class and find the "getServer()" method there update default server information.
</br> </br>
<img height='450' width ='300' src="https://i.imgur.com/kcGZY4P.png" /> 
</br>
<img height='400' width ='500' src="https://i.imgur.com/mlb8Nqe.png" />
</br>
<img height='400' width ='500' src="https://i.imgur.com/GgvoPP9.png" />