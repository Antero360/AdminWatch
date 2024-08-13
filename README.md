# AdminWatch

(Nov 2020)
ADVISORY: I, the creator, do not condone nor enable the malicious use of my code from here on in. All the code contained here, is STRICTLY for educational purposes. I will not be held liable for anyone that downloads this code, makes edits, and uses it for malicious intents.. That is your own doing.

AdminWatch is an application aimed for remote administration of Windows machines as of date of publish. It consists of two applications running in tangent with one another.  The main driver, monitors all established connections on the user's machine, generates a report on a 15 minute interval, and emails it to the administrator.  The second application, PacketSniffer, monitors the incoming traffic on the network, runs all ip addresses against a list of well known malicious IP Addresses, and automates the blocking of said IPs should they be on the list. PacketSniffer generates a report that also gets emailed to the administrator , on a 5 minute interval.

Any errors that may occur will also be emailed to the administrator for patching.
