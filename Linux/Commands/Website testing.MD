# Testing a Website from the Command Line in Linux

To test a website from the command line in Linux, you can use a combination of tools and commands to perform various types of tests and checks. Here are some useful commands you can use:

## Ping:
To check if a website is reachable and measure round-trip time.

```bash
ping example.com

## Traceroute:
To trace the route packets take to reach the destination server.

```bash
traceroute example.com


## curl: 
To fetch a web page and display its content or headers.

```bash
curl -I example.com   # Fetch headers
curl example.com      # Fetch content

## wget: 
To download files from the web.

```bash
wget https://example.com/file.zip

## nslookup / dig: 
To perform DNS lookups and query DNS information.

```bash
nslookup example.com
dig example.com

## telnet: To check if a specific port on a server is open.

```bash
telnet example.com 80   # Check if port 80 is open (HTTP)

## netcat (nc): To establish network connections for testing purposes.

```bash
nc -vz example.com 443  # Check if port 443 (HTTPS) is open

## htop: To monitor system resources and processes interactively.

```bash
htop

## iftop: To monitor network bandwidth usage by individual connections.

```bash
sudo iftop

## mtr: A combination of ping and traceroute, providing detailed network statistics.

```bash
mtr example.com

## ss / netstat: To display active network connections and listening ports.

```bash
ss -tuln   # List listening ports
ss -tn     # Display active TCP connections

These commands can help you diagnose network issues, test website availability, check DNS configurations, and monitor network traffic. Use the appropriate command based on the specific test you want to perform.
