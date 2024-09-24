# ludus-configs

## ludus.cloud range config files

#### Elastic AD Range

- Unconfigured Active Directory `acme.corp` with DC, SRV, win-11 WKSTN01 and win-10 WKSTN02 machines installed with elastic agent. Only has 80, 8080 and 443 port access to Red Team network.
- Red Team network with Windows 10 and Kali workstations that has full access to Active directory network.

#### NHA Elastic Range

- GOAD NHA lab with elastic agents installed. Requires provisioning with ansible via linux with ludus wireguard connection after range build has completed. Has full access to Open Net network
- Open Net network has redirector-1 and frontgun linux servers that have full access to Red Team and NHA networks
- Red Team network has Windows 10 workstation and ubuntu-22.04 teamserver machines and has full access to Open Net network
