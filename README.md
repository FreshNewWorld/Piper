PIPER - Python Implemented Provider Emulation Resource
=====================================================

Piper is an idea concieved by Nathan Williams as an answer to learning server daemons and managing a small server in
Python that can run on just about anything.

Piper was the result of tireless hours during the creator's time doing CyberPatriot trying to program Linux and Windows
servers that and realizing one thing: Windows servers are too complicated to maintain, and Linux servers need more time
configuring than actually running. This program is designed to fix that.

Piper also will teach its users what they are setting up and how the setup is being done. This program is also aimed
at educating as much as being a lightweight, easy-to-learn replacement for Windows Server and Linux servers.

Contents of PIPER
=================

Piper is intended to have some of the basic services needed to allow a small home, office, or business network to function
without a large, dedicated server on premesies.

The Services of Piper included are:

~>HTTP server (currently using the marrow.http.server package)

~>DHCP server (currently using the pybootd package)

~>TFTP server (currently using the pybootd package)

~>DNS server (currently using the dnspython package)

~>SYSLOG server (currently using the loggerglue package)

~>NTP server (currently using the program ntpserver.py)

~>EMAIL server (NOTE: currently do not have an email server package selected. Need to construct one or find one for
                      usage in a proof-of-concept)
                      
~>FTP server (currently using the pyftpd package)


