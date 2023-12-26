## Web Server Provisioning and Configuration with Ansible

Automate the provisioning and configuration of Apache web servers on CentOS and Ubuntu target machines using this Ansible playbook.

## Key Features

- **Distribution-Aware Configuration:** The playbook intelligently adapts tasks based on the target machine's distribution (CentOS or Ubuntu).
  
- **Customised HTML Styling:** The `index.html` file is dynamically customised with different background colors, providing a visually distinct touch for CentOS and Ubuntu.

## Nodes
### Master Node

The master node is a crucial component in orchestrating the automation process. In this project, the master node serves as the control machine where Ansible is installed and executes the playbook.

### Target Nodes

The target nodes represent the machines where the Apache web servers will be provisioned and configured. These could be instances in a cloud environment, virtual machines, or physical servers.

In the example below, the AWS EC2 dashboard displays the master node and target nodes used in the Ansible playbook.

![ansible-nodes](/img/Ansible_nodes.JPG)

## Project Structure

- `inventory`: Define your target hosts directly in the inventory file.
- `playbooks/playbook.yaml`: The main playbook for web server provisioning and configuration.
- `templates/`: Contains templates, including `webpage_template.j2`.
- `ansible.cfg`: Ansible configuration file with project-specific settings.

## Customisation

- Modify `playbooks/playbook.yaml` to suit your specific requirements.
- Customize variables in templates based on your preferences.
- Adjust settings in `ansible.cfg` if needed.

![playoutput](/img/play.JPG)

![ubuntu_output](/img/ubuntu.JPG)

![centos_output](/img/centos.JPG)

## Author - V Balaji


