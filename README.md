# DB Services Ansible Playbook

This repository contains Ansible playbooks for installing and configuring various database services on target hosts.

## Supported Services

- Elasticsearch
- Apache Kafka
- MongoDB
- PostgreSQL
- Apache Pulsar
- Redis

## Prerequisites

- Ansible 2.9 or higher
- Target hosts running a supported Linux distribution (e.g., Ubuntu 20.04, CentOS 8)
- SSH access to target hosts

## Usage

1. Clone this repository:
   ```
   git clone https://github.com/drensokoli/ansible-db-service-installation.git
   ```

2. Update the `inventory.yml` file with your target hosts.

3. Run the playbook:
   ```
   ansible-playbook -i inventory.yml DB_SERVICE/playbook.yml
   ```
## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.