# Aviatrix CLI Cheat Sheet

## Authentication
aviatrix login                          # Log in to the controller
aviatrix logout                         # Log out
aviatrix set-controller <ip>            # Set controller IP address

## Gateway Management
aviatrix gateway list                   # List all gateways
aviatrix gateway show <name>            # Show details of a gateway
aviatrix gateway create                 # Create a new gateway
aviatrix gateway delete <name>          # Delete a gateway
aviatrix gateway restart <name>         # Restart a gateway

## VPC & Network
aviatrix vpc list                       # List all VPCs
aviatrix vpc show <vpc-id>              # Show VPC details
aviatrix network list                   # List network connections

## Peering
aviatrix peering list                   # List all peering connections
aviatrix peering create                 # Create a peering connection
aviatrix peering delete <name>          # Delete a peering connection

## Transit & Spoke
aviatrix transit list                   # List transit gateways
aviatrix spoke list                     # List spoke gateways
aviatrix spoke attach <spoke> <transit> # Attach spoke to transit
aviatrix spoke detach <spoke>           # Detach spoke from transit

## Troubleshooting
aviatrix gateway diag <name>            # Run diagnostics on a gateway
aviatrix gateway ping <name> <ip>       # Ping from a gateway
aviatrix logs show <name>               # Show gateway logs
aviatrix version                        # Show CLI version
