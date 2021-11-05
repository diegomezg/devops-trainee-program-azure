# DevOps security using Vault
# Challenge

#### Requirements
1. One node with Centos 8 and postgresql.
1. Three nodes with Openbsd

### Instructions
In this activity you are installing and configuring a complete vault solution.
* Note: ansible and terraform will run on a Centos 8 node.

#### Install Vault
Install vault on openbsd with ansible using the .zip method on 3 nodes.
1. Create user and group for vault with a nologin bash and home on /opt/vault
1. Install vault on /opt/vault
1. Create init.d script to manage vault
1. Eneable TLS on each node

#### HA
Configure vault HA Cluster (raft) with ansible using the previous nodes.

#### LB
Install and configure NGIX on Centos 8 with ansible to balance https traffic on vault nodes.

#### Auth
1. Configure with terraform TLS auth method on vault.
1. Configure with terraform Approle auth method on vault.

#### Secrete Engine
1. Configure TOTP with terraform
1. Configure transit engine with terraform
1. Configure Database secret engine for postgresql (node Centos 8) with terraform

#### Policies
1. Create 2 admin vault users for TLS auth
1. Create 1 user for TOTP, transit engine and Database secret engine

#### App
Create a app to store and retrieve credit card numbers on a database.
1. Use transit engine
1. Use Database secret engine with short-lived credentials (10 seg)
1. Use vault agent
1. Use approle user created


### Expected deliverables
- A production grade cluster
- Code on a repository
- Code documentation on markdown files
- App which uses vault

### Evaluation

| Metric name | Description | % Value |
| ----------- |-------------| -------:|
| Demo Day | the team will run their solution and answer questions | 100% |
