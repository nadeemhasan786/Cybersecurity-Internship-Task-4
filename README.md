# Cybersecurity-Internship-Task-4
Setup And Use Of Firewall and Windows


# Firewall Configuration Task

## Task Description
Configure and test basic firewall rules to allow or block network traffic using Windows Firewall or UFW (Uncomplicated Firewall) on Linux.

## Objectives
- Configure firewall rules to allow/block specific ports
- Test firewall rules functionality
- Understand network traffic filtering concepts

## Tools Used
- **Windows**: Windows Defender Firewall with Advanced Security
- **Linux**: UFW (Uncomplicated Firewall)

## Steps Performed

### Windows Firewall Configuration
1. **Listed current firewall rules** using `netsh advfirewall` commands
2. **Blocked inbound traffic on port 23** (Telnet) with specific rule
3. **Tested the block rule** using `Test-NetConnection` and telnet client
4. **Allowed SSH traffic** on port 22 (if applicable)
5. **Removed test rules** to restore original configuration

## Author:-
[Nadeem Hasan]

# Remove rule
netsh advfirewall firewall delete rule name="Block Telnet"
