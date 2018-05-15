ARP-Poison is tools for ARP Spoofing attack

### Requirements
* Scapy
```
pip install scapy
```

## Usage
```
python arp-poison.py [-h] [-i INTERFACE] [-t1 TARGET1] [-t2 TARGET2] [-f] [-q]
        [--time]
        
ARP Poisoning Tool

optional arguments:
  -h, --help            show this help message and exit
  -i INTERFACE, --interface INTERFACE
                        Network interface to attack on
  -t1 TARGET1, --target1 TARGET1
                        First target for poisoning
  -t2 TARGET2, --target2 TARGET2
                        Second target for poisoning
  -f, --forward         Auto-toggle IP forwarding
  -q, --quiet           Disable feedback messages
  --time                Track attack duration
  ```
