# 09. Networking fundamentals

Beginner reference: command, purpose, and a simple example. Examples should be adapted to your own machine or authorized lab.

| # | Command | Purpose | Example |
|---:|---|---|---|
| 1 | `ip addr` | Display network interfaces and IP addresses. | `ip addr` |
| 2 | `ip link` | Display network interface status. | `ip link` |
| 3 | `ip route` | Display the routing table. | `ip route` |
| 4 | `ip neigh` | Display the neighbor/ARP table. | `ip neigh` |
| 5 | `ping -c 4 host` | Send four connectivity test packets. | `ping -c 4 1.1.1.1` |
| 6 | `hostname -I` | Show assigned IP addresses. | `hostname -I` |
| 7 | `ss -tuln` | List listening TCP/UDP sockets numerically. | `ss -tuln` |
| 8 | `ss -tunap` | Show TCP/UDP sockets and associated processes (permissions may limit details). | `sudo ss -tunap` |
| 9 | `ip -s link` | Show interface traffic statistics. | `ip -s link` |
| 10 | `ethtool interface` | Show or inspect Ethernet interface settings, if installed. | `sudo ethtool eth0` |
| 11 | `nmcli device status` | Show NetworkManager device status. | `nmcli device status` |
| 12 | `nmcli connection show` | List NetworkManager connections. | `nmcli connection show` |
| 13 | `resolvectl status` | Show DNS resolver status on systems using systemd-resolved. | `resolvectl status` |
| 14 | `getent hosts domain` | Resolve a hostname using system name-service settings. | `getent hosts example.com` |
| 15 | `curl -I URL` | Fetch HTTP response headers. | `curl -I https://example.com` |
| 16 | `wget URL` | Download a file from a URL. | `wget https://example.com` |
| 17 | `traceroute host` | Show the route packets take toward a host. | `traceroute example.com` |
| 18 | `tracepath host` | Trace a network path, if installed. | `tracepath example.com` |
| 19 | `dig domain` | Query DNS records, if installed. | `dig example.com` |
| 20 | `nslookup domain` | Query DNS information. | `nslookup example.com` |

[← Back to README](README.md)
