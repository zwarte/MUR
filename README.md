SSH-telnet-proxy-tunnel
=======================

Tunnel SSH connections through a telnet tunnel

This script is based on tunnel.py by Urban Kaveus and Simon Josefsson.
I used tunnel.py for years to get out of our company network.
For quite some time now I am mostly working inside og virtual machines,
and I experienced problems: sometimes it worked,
sometimes it simply did not connect to the remote machine.

Since I do not speak perl, I converted the script to Python.
On the way, I also switched from forking to select().

I would like to get your feedback on it.
