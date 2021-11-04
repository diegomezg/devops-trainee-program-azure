# Hashicorp Consul
## Day 3

### Contents
- ACL System
- Roles, Policies and Tokens
- KV Store
- Consul Watches
- Consul Template

### Useful links:
- [Google Slides - Day 3](https://docs.google.com/presentation/d/1-1Wz_K7TVRtHnT1MZRXOW4fswSik1E5bfVg084jKHBs/edit?usp=sharing)
- [Documentation - Consul ACL](https://www.consul.io/docs/security/acl)
- [Documentation - Consul KV](https://www.consul.io/docs/dynamic-app-config/kv)
- [Documentation - Consul Watch](https://www.consul.io/docs/dynamic-app-config/watches)
- [Github - Consul Template](https://github.com/hashicorp/consul-template) (You can check the README for an intro and a small demo)

### Interactive tutorials:
- [Securing Consul with ACLs](https://learn.hashicorp.com/tutorials/consul/access-control-setup-production)
- [Store data in Consul KV](https://learn.hashicorp.com/tutorials/consul/get-started-key-value-store)


## Integrating Activity

### Instructions for the activity are available here
- [Google Document - Consul Dashboard and Counting](https://docs.google.com/document/d/1HSzKOqf04ERY0KSA9tH3zQ8anc7gt4ajUbeKCh_5pj4/edit?usp=sharing)

### Deliverables
A zip file with your name containing the following: 
- Screenshot of the Consul UI showing the registered services
- Screenshot of the Dashboard UI functioning correctly
- Screenshot of the counting policy
- Screenshot of the dashboard policy
- The server.hcl file used to start the consul agent
- The counting.hcl and dashboard.hcl files used to register the services



### Evaluation

| Metric  |  Value  |
| ------------  | ------------ |
|  Consul agent running with ACL enabled | 40%  |
|  Policies for Counting and Dashboard | 10%
|  Counting and Dashboard services registered including their side-cars | 30% |
|  Functional Dashboard application |  20% |
