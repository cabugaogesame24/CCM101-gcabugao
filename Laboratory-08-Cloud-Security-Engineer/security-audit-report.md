# Security Audit Report

## Principle of Least Privilege (PoLP)
The Principle of Least Privilege means giving every user, account, or system only the minimum access rights and permissions they need to finish their specific tasks — nothing more. It is very important for cloud accounts because if an account gets compromised, the attacker will only have limited permissions to misuse, so the damage cannot spread widely across your cloud resources or data.

## Attack Surface
For a virtual machine, the attack surface is all the possible entry points that an attacker can try to access or exploit — such as open ports, running services, enabled accounts, and exposed applications. The larger this surface is, the more ways attackers have to try to get inside your server; closing unnecessary ports and stopping unused services shrinks this surface and makes the server safer.

## Default Deny Policy
A Default Deny policy blocks all incoming traffic automatically unless you explicitly allow it — instead of trying to block every single attacker or harmful address one by one. This approach is much safer because you only open exactly what you need, so unknown threats, new attacks, and accidental exposure to public traffic get blocked by default without you needing to list every bad source.
