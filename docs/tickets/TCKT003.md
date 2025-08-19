Title: Printer shows offline for all users on floor three
Status: Resolved
Priority: High
User: Multiple
Summary: Network printer went offline after switch reboot
Steps taken: Pinged printer, checked IP reservation, restarted print spooler on server
Resolution: Reapplied static IP, updated DNS entry, restarted printer
Follow up: Schedule firmware update on weekend

# Printer shows offline for all users on floor three

After the network switch reboot, a network printer on the third floor became unavailable. Users reported that the printer status was 'Offline'. Actions: I pinged the printer to ensure it was reachable, checked its DHCP reservation, and restarted the print spooler service on the print server. After verifying, the printer still couldn't be reached consistently.

I then reconfigured the printer's static IP, updated the DNS entry, and restarted the printer itself. This resolved the issue and the device became reachable again for all users.

**Resolution:** The printer was returned to service by reapplying its static IP, updating the DNS record, and restarting the unit.

**Follow up:** Schedule a firmware update for the printer during the weekend to prevent future issues.
