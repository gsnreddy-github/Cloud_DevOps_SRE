# Linux: Testing a Website

To test a website from the command line in Linux, you can use a combination of tools and commands to perform various types of tests and checks. Here are some useful commands you can use:

### Commands
1. Ping: To check if a website is reachable and measure round-trip time.

```sh
ping example.com
```

1. Traceroute: To trace the route packets take to reach the destination server.

```sh
traceroute example.com
```

1. curl: To fetch a web page and display its content or headers.

```bash
curl -I example.com   # Fetch headers
curl example.com      # Fetch content
```

1. wget: To download files from the web.

```bash
wget https://example.com/file.zip
```

1. nslookup / dig: To perform DNS lookups and query DNS information.

```bash
nslookup example.com
dig example.com
```

1. telnet: To check if a specific port on a server is open.

```bash
telnet example.com 80   # Check if port 80 is open (HTTP)
```

1. netcat (nc): To establish network connections for testing purposes.

```bash
nc -vz example.com 443  # Check if port 443 (HTTPS) is open
```

1. htop: To monitor system resources and processes interactively.

```bash
htop
```

1. iftop: To monitor network bandwidth usage by individual connections.

```bash
sudo iftop
```

1. mtr: A combination of ping and traceroute, providing detailed network statistics.

```bash
mtr example.com
```

1. ss / netstat: To display active network connections and listening ports.

```bash
ss -tuln   # List listening ports
ss -tn     # Display active TCP connections
```

These commands can help you diagnose network issues, test website availability, check DNS configurations, and monitor network traffic. Use the appropriate command based on the specific test you want to perform.


