Initial stages of a command line USB PCAP parser.

# Quick Start
Once installed, you can load up a pcap and analyze it:

```python
In [1]: from USB import USB

In [2]: usb = USB("./task.pcap")

In [3]: usb
Out[3]: <USB packets=835>

In [4]: usb.devices
Out[4]: [<Apple, Inc. Aluminum Keyboard (ISO) v0.6.9 USB2.0.0 bus_id=1 address=3>]
```

# Requires
 - python 3.5+
 - tshark

# Install
Install using pip:

```bash
$ pip install .
```
