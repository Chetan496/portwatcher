# Portwatcher

A python utility to scan for different ports and check whats running, get notified when something starts running on that port etc.

## Using portscan

portwatch watch [PORT]

here we watch for a particular port every 5 seconds and report name of the process and any file handlers opened by that process.

portwatch scan
should scan for everything currently listening and flag anything bound to to 0.0.0.0.
should scan for wellknown database and cache ports on priority.

