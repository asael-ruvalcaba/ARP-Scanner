# ARP-Scanner
An ARP scanner maps IP addresses to media access control (MAC) addresses and can be used to determine hosts that are active. It only works within a local area network (LAN), so the attacker must be connected to the internal network.

### The necessary modules are imported:
- `signal`: Allows you to handle system signals, such as Ctrl + C.
- `scapy`: Library used to build, send, capture and analyze network packets.
- `argparse`: To parse command line arguments in a structured way.
- `sys`: To use sys.exit() and exit the program.

### Use and Execution
Para ejecutar este script, puedes usar el siguiente comando en la terminal:
`python name_script.py -t <IP or range IP>`

Example
`python ARPscanner.py -t 192.168.1.1/24`
This will scan all IP addresses in the range `192.168.1.1` to `192.168.1.254` using ARP and display the responses received.
