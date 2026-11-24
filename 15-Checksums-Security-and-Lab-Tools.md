# 15. Checksums, security & safe lab tools

Beginner reference: command, purpose, and a simple example. Examples should be adapted to your own machine or authorized lab.

| # | Command | Purpose | Example |
|---:|---|---|---|
| 1 | `sha256sum file` | Calculate a SHA-256 checksum. | `sha256sum download.iso` |
| 2 | `sha512sum file` | Calculate a SHA-512 checksum. | `sha512sum download.iso` |
| 3 | `md5sum file` | Calculate an MD5 checksum; not suitable for modern security verification. | `md5sum file.zip` |
| 4 | `gpg --version` | Display the GnuPG version. | `gpg --version` |
| 5 | `gpg --verify file.sig file` | Verify a detached signature when the trusted public key is available. | `gpg --verify package.sig package.tar` |
| 6 | `openssl version` | Display the OpenSSL version. | `openssl version` |
| 7 | `openssl rand -hex 16` | Generate 16 random bytes represented as hexadecimal. | `openssl rand -hex 16` |
| 8 | `openssl s_client -connect host:443` | Inspect a TLS connection to a host you are authorized to test. | `openssl s_client -connect example.com:443` |
| 9 | `nmap --version` | Display the Nmap version. | `nmap --version` |
| 10 | `nmap -sn 192.0.2.0/24` | Discover hosts on a network you own or are authorized to assess. | `nmap -sn 192.0.2.0/24` |
| 11 | `wireshark` | Open the graphical network protocol analyzer, if installed. | `wireshark` |
| 12 | `tshark --version` | Display the TShark command-line analyzer version. | `tshark --version` |
| 13 | `tcpdump --version` | Display the tcpdump version. | `tcpdump --version` |
| 14 | `tcpdump -D` | List capture interfaces available to tcpdump. | `sudo tcpdump -D` |
| 15 | `lynis audit system` | Run a local system security audit, if installed. | `sudo lynis audit system` |
| 16 | `ufw status` | Show uncomplicated firewall status, if installed. | `sudo ufw status` |
| 17 | `aa-status` | Show AppArmor status, if available. | `sudo aa-status` |
| 18 | `fail2ban-client status` | Show Fail2ban status, if installed and running. | `sudo fail2ban-client status` |

[← Back to README](README.md)
