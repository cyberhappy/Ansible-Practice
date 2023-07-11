Welcome to my Ansible playbook repository! This collection of playbooks showcases my practical experience with Ansible
 while working with various operating systems, including Linux servers, Cisco routers, and Cisco switches.

## Introduction

Ansible is an open-source automation tool that simplifies infrastructure management and deployment. This repository
 contains a curated set of Ansible playbooks that I have practiced and developed during my learning journey.

## Playbook Overview

- linux-servers: This directory contains playbooks for managing Linux servers. It includes tasks such as package
 installation, file management, service configuration, and more.

- cisco-routers: Here, you will find playbooks specific to Cisco routers. These playbooks focus on tasks like
 configuring interfaces, setting up routing protocols, managing access control lists (ACLs), and so on.

- cisco-switches: This directory includes playbooks designed for Cisco switches. They cover tasks such as VLAN
 configuration, port security settings, switchport assignments, and other switch-related configurations.

Feel free to explore each directory to gain insights into how Ansible can be used to automate different aspects of
 server and network management.

## Getting Started

To get started with these playbooks, follow these steps:

1. Install Ansible: Ensure that Ansible is installed on your local machine by referring to the official documentation
 at [docs.ansible.com](https://docs.ansible.com/ansible/latest/installation_guide/index.html).

2. Clone the Repository: Use the following command to clone this repository to your local machine:


   <pre><code>git clone https://github.com/cyberhappy/Ansible-Practice.git  </code></pre>

4. Navigate to the relevant directory: Depending on which type of device you want to manage, navigate to the
 corresponding directory (linux-servers, cisco-routers, or cisco-switches).

5. Execute the Playbook: Run the desired playbook using the command:

   <pre><code>ansible-playbook -i inventory.ini playbook.yml </code></pre>
   Replace inventory.ini with your inventory file containing the target device details and playbook.yml with the
 name of the playbook you wish to run.

Feel free to modify the playbooks according to your specific requirements and explore different Ansible modules and
 features to enhance your automation capabilities.

## Contributing

Contributions to this repository are welcome! If you have any improvements, bug fixes, or additional playbooks that you
 would like to contribute, please feel free to open a pull request. Let's learn and grow together!

## License

This repository is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute the playbooks
 in accordance with the terms of the license.

---

I hope you find these Ansible playbooks useful for managing Linux servers, Cisco routers, and Cisco switches. If you
 have any questions or suggestions, feel free to reach out. Enjoy automating with Ansible!

