# Reflection 

A host-based firewall protects a server even if the network perimeter is breached because it runs directly on the server itself and filters every incoming and outgoing connection locally. It does not matter if an attacker already slipped past outer defenses; the firewall still inspects traffic and blocks anything that is not explicitly permitted, acting as a second strong layer of protection.

Managing open ports is critical to reducing attack surface because every open port that runs a service is a potential doorway attackers can test. Unused or unnecessary ports — even if they seem harmless — can contain bugs or vulnerabilities. Closing everything except the ports your services actually need removes these extra doorways and leaves fewer opportunities to attack.

Leaving a database port such as 3306 open to the public internet is extremely dangerous because databases hold sensitive and valuable information — user records, credentials, business data — and are constant targets for automated scanning and brute-force attacks. Without restriction, anyone on the internet can attempt to connect, guess passwords, or exploit database flaws to steal, delete, or destroy the entire dataset.

Completing this mission showed me how shockingly easy it is to leave a server exposed — just skipping one firewall step leaves everything open to anyone. It also taught me how quickly you can lock a system down when you follow proper order and policy, but how one small mistake — enabling the firewall before allowing SSH — instantly cuts off your own access. Security really is a continuous, careful process rather than a one-time switch you flip.

With eight completed missions now in my GitHub portfolio, the collection feels cohesive and professional. It shows clear progression — from cloud basics to infrastructure, multi-cloud, application deployment, data, operations, and now security — and demonstrates that I can follow full workflows from setup through protection and documentation. This organized, traceable history will be very valuable as I build toward future cloud roles.
