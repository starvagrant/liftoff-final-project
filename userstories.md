# User Stories for KVM project

User stories follow a

    As a < type of user >, I want < some goal > so that < some reason >.

format.

1.  As a network technician,
    I want a command that pings kvms
    so that I can tell if one is offline.

2.  As a network administrator,
    I want a command that displays network hops to kvms
    so that I can make sure no one has messed with router configs.

3.  As a network administrator,
    I want a command that ensures password compliance
    so that I know kvm login credentials are secure.

4.  As a network technician,
    I want a command that sends login credentials to the ticket system,
    so that I can send the credentials to the customer.

5.  As a customer,
    I want to know what has been installed on my machine,
    So that I can verify my machine's os has been properly installed.

6.  As a customer,
    I would like to know when my windows license expires,
    So that I can ensure my machine does not stop unexpectedly.

7.  As a network technician,
    I want a command that displays what isos are available
    So that I can fulfill customer requests.

8.  As a network technician,
    I want a help menu
    So that I know what commands are available to the kvm script

9.  As a network technician,
    I would like to have a installation preloaded into the
    kvm.

## User Stories Completed

1. The following command kvm 0 ping fulfills this request.
2. The following command kvm 0 traceroute fulfills this request.
3. The following command kvm <number> passwd fulfills this request.
4. The following command kvm <number> mail fulfills this request.
7. The following command kvm lsisos fulfills this request.
8. The following command kvm help fulfills this request.
9. The following command kvm <number> mount <iso> fulfills this request

## Unimplemented User Stories.

5. Consider command kvm checksum for this purpose.
6. This seems outside the scope of the project. KVM has no internal
mechanism for checking up on Window's licenses, and would involve
monitoring beyond the scope the program.
