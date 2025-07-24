# ansible-sudo-restrictions

📊 Full presentation: [README.docx](./README.docx)

This repository contains:
- Ansible playbooks for managing restricted `sudo` access on Linux servers
- A modular structure using roles, one per team or application (e.g. TIBCO, Kafka, Elastic)
- Example `sudoers` files allowing only specific, approved commands
- YAML files with users grouped by their functional roles
- A scalable, easy-to-maintain system for secure access management

🎯 Purpose:
To restrict `sudo` rights to only the commands needed by each team or application — avoiding the use of `sudo ALL` — in a centralized, automated, and secure way.

