## Web Server Provisioning and Configuration with Ansible

Automate the provisioning and configuration of Apache web servers on CentOS and Ubuntu target machines using this Ansible playbook.

![playoutput](placeholder)

## Key Features

- **Distribution-Aware Configuration:** The playbook intelligently adapts tasks based on the target machine's distribution (CentOS or Ubuntu).
  
- **Customised HTML Styling:** The `index.html` file is dynamically customised with different background colors, providing a visually distinct touch for CentOS and Ubuntu.

## Project Structure

- `inventory`: Define your target hosts directly in the inventory file.
- `playbooks/playbook.yaml`: The main playbook for web server provisioning and configuration.
- `templates/`: Contains templates, including `webpage_template.j2`.
- `ansible.cfg`: Ansible configuration file with project-specific settings.

## Customisation

- Modify `playbooks/playbook.yaml` to suit your specific requirements.
- Customize variables in templates based on your preferences.
- Adjust settings in `ansible.cfg` if needed.

![ubuntu_output](ub)

![centos_output]()

## Author - `V Balaji`


