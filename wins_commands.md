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
sfc /scannow                # Scan whole the files and find for violations
tasklist                    # List all running tasks
taskkill /f /pid PID        # Kill a task with its PID
netsh wlan show wlanreport  # Generate a detailed Wi-Fi report on Windows in HTML
netsh interface show interface  # 
netsh interface ip show address | findstr “IP Address”  #
netsh interface ip show dnsservers  #
netsh advfirewall set allprofiles state off # Turn off Windows firewall
netsh advfirewall set allprofiles state on  # Turn on Windows firewall
ping -t                     #
tracert                     # Shows each hop (router/server) between you and the target / Measures latency (time in ms) at each step
netstat                     # Display network connections, listening ports, and protocol statistics.
netstat -af
netstat -o
netstat -e -t 5
route print
route add
route delete
