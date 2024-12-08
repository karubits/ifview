# ifview
**ifview** (*"interface view"*) provides a cleaner, enriched visualization of network interfaces on Linux. It leverages **ip** tools and the **rich** library to produce an attractive, colorized table displaying network interfaces, IP addresses, MAC addresses, state, MTU, and physical NIC models.

![example](/img/iface-example.png)

## Features
- Tabular and colorized output for easy readability
- Displays interface state, MAC, IP addresses, MTU
- Adds detected NIC models to the output for deeper hardware insight
- Simple and direct: no heavy dependencies beyond Python 3 and `rich`

## Getting Started

### Prerequisites
- **Python 3**  
  {🐍} [install python 3](https://www.google.com/search?q=install+python3+linux)
- **rich library** for Python  
  {💎} [install python rich library](https://www.google.com/search?q=python+rich+library+installation)
  
You can install `rich` via:
```bash
apt install python3-rich -y
