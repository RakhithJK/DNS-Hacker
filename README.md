# F.A.Q
DNS Resolver Hack

<div align="center">
    <img src="" width="400px"</img> 
</div>


# About DNS HACKER
DNS Resolver is a software service running on any computer, in this case MIRC/IRC Network. DNS Resolver service forwards DNS 
Queries to the DNS Server, in this case MIRC/IRC DNS Server for Name Resolution, on behalf of Operating System using DNS
Resolver (a DNS Client) and other applications, this is where DNS Resolver ask DNS Name Server to provide information and
resolve specific IP to Address. This will cause our DNS query to resolve for DNS Server going from MIRC/IRC Server to
victim DNS, once resolve, we can access victim pc shares or null shares remotly, as if we are into victim local network.
- Types of Access
1. Read, write or both
2. Vhost Networks
5. If you are connected to null shares, you will see something like routers, printers, scanners, remote machines
6. If you see $, it means that is unix
7. If you are stuck at access, you will still know victim exact username or list of usernames available

# Ideas
1. Windows: Change victim hosts files or regedit remotely
3. *nix based system, obtain /etc/shadow /etc/passwd /etc/services

# Warning
1. Do not over due victims, wait 24 hours otherwise you will over load DNS queries because that will affect your DNS Client

# List
1. It can poison Windows/*nix/mac
2. LAN/WLAN/NAT
3. This does not work on websites/web systems

# How-To Section
1. Load the script into IRC/MIRC Client
2. Find any victim in channel or outside IRC/MIRC (you should know IP)
3. Enter /dns Victim_IP
4. This will resolve
5. On Windows: Start menu then run enter \\\VICTIM_IP that is resolved (you will see new window)
5. On Linux: Smbclient //VICTIM_IP (with or without other parameters, if neccessary)
