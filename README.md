# Cloud-VM - Azure/AWS VM

## Terraform: VM Deploy - Azure

Infrastructure Template for GitHub Actions and Terraform Setup.

## Infra Overview

This repository an `infra` folder full of Terraform; to plan, deploy, and destory a Linux VM.

### Infra Components

Through the use of GitHub Actions, create terraform storage, network and VM in three terraform `components`.

### Environment Variables

To achive creation of distinct VMs, use GitHub environments; setup `variables` and `secrets` to enable the Terraform infrastructure deployment automation.

### More Infra Info

Learn more in the `infra/README` folder.

For example, the Azure section.

* [infra/README/Azure/docs/01_overview.md](infra/README/Azure/docs/01_overview.md)

## Software Maintenance

After creation of the VM, be sure to login and check for software package updates perodically:

```bash
ssh devadmin@newhost.nameor.ip
sudo apt update
sudo apt upgrade
sudo reboot
```
