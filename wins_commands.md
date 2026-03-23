# CMD Commands

## Commands
```bash
ipconfig                    # IP information
ipconfig /all               # IP information details
findstr                     # find string in result "ipconfig /all | findstr DNS"
ipconfig /release && ipconfig /renew # Refreshing IP address
ipconfig /displaydns        # List all DNS records of computer in current
clip                        # Copy all contents of cmd "ipconfig /displaydns | clip"
ipconfig /flushdns          # Delete/remove DNS resolver cach
nslookup                    # DNS servers for particular url "nslookup google.com"
getmac /v                   # MAC address information
assoc                       # view or set file extension associations, basically, it tells Windows which file type a file extension belongs to.