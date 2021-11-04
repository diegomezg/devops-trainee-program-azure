# Vault

## Goals
The main goal of this course is to the allow the trainee to deploy and operate vault, understanding the fundamental concepts and internals.

## Objectives
- Understand the basic usage and Architecture of Hashicorp Vault.
- Learn vault fundamentals usage and concepts and how to enable them: Secret Engines, Authentication Methods and Policy creation.
- Operate Vault with UI, CLI and RestAPI and learn the basics of operations like status and init.
- Deploy and configure Vault for production environments.
- Learn how to automate vault configuration with Terraform provider and scripting tools.

## Contents
1.    TAO of HashiCorp
1.    What is Vault
1.    How to install Vault locally
1.    Init and unseal vault.
1.    Vault Tokens life cycle
1.    Vault Secret engines
    1.    PKI
    1.    K/V
    1.    DB
1.    Vault Policies
1.    Vault roles
1.    Vault Auth methods
    1.    AppRole
    1.    GitHub
    1.    Username and password
1.    Vault credential rotation
    1.    DB
1.    Vault entities and groups
1.    Terraform vault provider

## Learning materials
- [Tao of HashiCorp](https://www.hashicorp.com/tao-of-hashicorp)
- [Vault documentation](https://www.vaultproject.io/docs/)
- [Learn Hashicorp](https://learn.hashicorp.com/vault)
- [What is Vault?](https://www.vaultproject.io/docs/what-is-vault)
- [Benefits and Use Cases of Vault​](https://www.vaultproject.io/docs/use-cases)
- [Comparing Versions of Vault](https://www.hashicorp.com/products/vault/features)
- [Secrets](https://www.vaultproject.io/docs/secrets)​
- [KV​](https://www.vaultproject.io/docs/secrets/kv/kv-v2)​
- [PKI​](https://www.vaultproject.io/docs/secrets/pki)​
- [Policies](https://www.vaultproject.io/docs/concepts/policies)
- [Tokens](https://www.vaultproject.io/docs/concepts/tokens)
- [Auth](https://www.vaultproject.io/docs/concepts/auth)
- [Terraform vault provider](https://www.terraform.io/docs/providers/vault/index.html)

## Labs
* [First Secret](https://learn.hashicorp.com/tutorials/vault/getting-started-first-secret?in=vault/interactive)
* [Getting started UI​](https://learn.hashicorp.com/tutorials/vault/getting-started-install?in=vault/getting-started-ui)
* [Install](https://learn.hashicorp.com/tutorials/vault/getting-started-install?in=vault/getting-started-ui)
* [KV](https://learn.hashicorp.com/tutorials/vault/getting-started-secrets-engines)
* [Versioned Key/Value Secrets Engine](https://learn.hashicorp.com/tutorials/vault/versioned-kv?in=vault/interactive) (CLI,API,UI)
* [Dynamic Secrets: Database Secrets Engine](https://learn.hashicorp.com/tutorials/vault/database-secrets?in=vault/interactive)
* [Build Your Own Certificate Authority (CA)](https://learn.hashicorp.com/tutorials/vault/pki-engine?in=vault/interactive)
* [Policies](https://learn.hashicorp.com/tutorials/vault/getting-started-policies?in=vault/interactive)
* [Policies cont.](https://learn.hashicorp.com/tutorials/vault/policies)
* [Tokens](https://learn.hashicorp.com/tutorials/vault/tokens?in=vault/tokens)
* [Token Management](https://learn.hashicorp.com/tutorials/vault/token-management?in=vault/tokens)
* [Token/Github](https://learn.hashicorp.com/tutorials/vault/getting-started-authentication?in=vault/getting-started)
* [Userpass - UI](https://learn.hashicorp.com/tutorials/vault/getting-started-auth-ui)
* [Approle](https://learn.hashicorp.com/tutorials/vault/approle?in=vault/auth-methods)
* [Entities and Groups](https://learn.hashicorp.com/tutorials/vault/identity?in=vault/auth-methods)

## Course activities
1. [Install vault with docker](01-install-vault.md)
1. [Token lifecycle](02-token-lifecycle.md)
1. [Vault operation](03-vault-operation.md)
1. [Secret engines](04-secret-engines.md)
1. [Authentication methods](05-auth-methods-md)
1. [Policies](06-policies.md)
1. [Vault entities](07-vault-entities.md)
1. [Terraform Vault provider](08-terraform-vault-provider.md)

## Collaborators
Name     |   Slack  | Email |
---------|----------|----------|
Bernardo Garza    | @bernardo.garza | bernardo.garza@digitalonus.com |
Rigel Reyes     | @Rigel Reyes | rigel.reyes@digitalonus.com |
