# Azure Key Vault - Let's Encrypt Certificates
## GitHub Action

A GitHub action that generates and renews Let's Encrypt certificates within a Azure Key Vault resource. It uses a GitHub repository to commit and read challenges from. A single 'GET' endpoint `.well-known/acme-challenge/{id}` needs to be setup for your domain.
