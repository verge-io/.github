# VergeOS — The Infrastructure Operating System

**VergeOS** is an infrastructure operating system that converges **compute, vSAN storage, disaster recovery, networking, and private AI** into a single unified platform.

It’s built around a simple idea: **1 UI / 1 API / 1 Update = 1 Install Package**.

## Start here

- 📚 Docs: https://github.com/verge-io/docs
- 🧱 Terraform Provider: https://github.com/verge-io/terraform-provider-vergeio
- 🐍 Python SDK: https://github.com/verge-io/pyVergeOS
- 🧰 CLI: https://github.com/verge-io/verge-cli

## Core components (baked in)

- **VergeHV (Hypervisor):** integrated Type-1 hypervisor built on KVM
- **VergeFS (vSAN Storage):** distributed storage that pools capacity across the cluster with tiers, dedupe, snapshots, and self-healing
- **VergeFabric (Networking):** software-defined networking with routing, DHCP/DNS, firewall/NAT/VPN, and micro-segmentation

## Automation & integrations

- Terraform: https://github.com/verge-io/terraform-provider-vergeio
- Python: https://github.com/verge-io/pyVergeOS
- Go: https://github.com/verge-io/govergeos
- PowerShell: https://github.com/verge-io/PSVergeOS
- Ansible: https://github.com/verge-io/ansible-collection-vergeos
- Packer: https://github.com/verge-io/packer-plugin-vergeio
- Monitoring: https://github.com/verge-io/vergeos-exporter


## Support / issues

Please open issues in the relevant repository and include:
- VergeOS version
- cluster/node layout (high level)
- logs / screenshots as appropriate
