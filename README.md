# Pritunl Config Script

This is my personal config script for me, to be able to execute and stop my vpn config.

How to use this repo
1. Clone this repo
2. Copy script to your /usr/local/bin or /usr/local/sbin <br>
`$ cp pritunl-config /usr/local/sbin/pritunl-config`
3. Change the permission to be executable <br>
`$ chmod +x /usr/local/sbin/pritunl-config`

How use the command
1. Disable Auto Start
`$ pritunl-config disable`

2. Enable Auto Start
`$ pritunl-config enable`

3. Stop All VPN Connection
`$ pritunl-config stop`

4. Start All VPN Connection
`$ pritunl-config start`
