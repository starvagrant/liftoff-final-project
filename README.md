# kvm-automation
This repository is a collection of shell scripts to make
kvm easier to access from the command line. The general
syntax is

kvm number <command>

Where number is 1-5 for our five kvm units. Some commands
accomodate 0 as a wildcard when it makes sense to implement
it (i.e. for quick diagnosis).

The following commands are available:

- launch: launches the kvm console
- passwd: changes the client1 account password
- mail: mails information so that it ends up in our ticket system
- clean: removes sensitive info about the kvm unit from
    the local filesystem.

- ping: pings the kvm unit.
- traceroute: performs a traceroute on the kvm unit.

The following commands are in the works:

- lsiso: lists iso files that are available via samba
- mount: mounts an iso from the samba server.
