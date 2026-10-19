# Screenshot Evidence Checklist

## Phase 1 — Setup
- [ ] 01-git-version.png
- [ ] 02-vscode-version.png
- [ ] 03-openssh-version.png
- [ ] 04-project-folder.png

## VPC A
- [ ] VPC details and CIDR
- [ ] Public and private subnet details
- [ ] Internet Gateway attachment
- [ ] Public and private route tables

## VPC B
- [ ] VPC details and CIDR
- [ ] Private subnet details
- [ ] Private route table

## EC2 and Security
- [ ] Bastion and application instance details
- [ ] Security group inbound rules
- [ ] Confirmation that App-A and App-B have no public IPv4 addresses

## VPC Peering and Testing
- [ ] Baseline connectivity failure
- [ ] Active VPC peering connection
- [ ] Forward and return routes
- [ ] App-A to App-B ping
- [ ] App-B to App-A ping
- [ ] SSH to App-B through the bastion
- [ ] Controlled ICMP failure and recovery

## Cleanup
- [ ] EC2 instances terminated
- [ ] Lab networking resources deleted
- [ ] Final AWS resource verification
