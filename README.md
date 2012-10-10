DHCP-server-scanner
===================

Unix console utility that implements DHCP client functionality to scan DHCP servers

To compile it you need 'cmake' utility installed

*How to compile:* just do './cmake.sh'

*How to use:* 'bin/dhcpd-detector-release -i eth0'

Example of response:
--------------------

<pre>
<----- DHCP scan started ----->
DHCP server MAC: 78e7d1f7c56e
DHCP: Received msgtype = 2
Server host name: Nathiny.dom.melko.com
Boot filename: boot\x86\wdsnbp.com
DHCP server IP 172.24.153.1
DHCP relay IP 0.0.0.0
DHCP next server IP 194.95.62.7
proposed MASK: 255.255.255.0
proposed GW: 172.24.153.1
proposed DNS 0: 4.4.4.4
proposed DNS 1: 8.8.8.8
proposed IP: 172.24.153.79
<----- stopped ----->
</pre>

*P.S. this is very basic functionality project and it doesn't support full DHCP protocol features*
