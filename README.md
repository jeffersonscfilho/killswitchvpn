# Kill Switch VPN

This script allows all traffic from the outbound connection to the internet to be redirected to the vpn network interface that is in use, preventing access to the internet output to occur by other network interface even if the vpn connection closes. It allow connection input only on 22 port.

```
Usage:  git clone https://github.com/jeffersonscfilho/killswitchvpn.git
	cd killswitchvpn
	chmod +x kill-switch-vpn-on
	chmod +x kill-switch-vpn-off
	mv kill-switch-vpn* /bin/
	./kill-switch-vpn-on
```
