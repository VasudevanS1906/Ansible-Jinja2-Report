# Ansible-Jinja2-Report

An Ansible playbook that uses Jinja2 templating to generate a report containing uptime information for servers specified in an inventory file. The report highlights unreachable servers and those running for more than a day.

# Project Description:

Ansible playbook and Jinja2 template to generate a server uptime report.
- Collects uptime data from specified hosts
- Identifies unreachable servers and those running for over 24 hours
- Generates a timestamped report file on the Ansible control node

# File Structure:
'''
ansible-jinja2-report/
├── hosts                  # Inventory file with server list
├── template.yml           # Ansible playbook
├── template.j2            # Jinja2 template for report
└── sample_output.txt      # Sample output of the generated report
''''
# Usage:

          ansible-playbook -i hosts template.yml

# Support and Contact

If you have any questions, please feel free to contact me at [vasudevanswornampillai@gmail.com].

# License

This project is licensed under the **MIT License**.

# Share with the community

If you find this project interesting or helpful, don't hesitate to share with your community! Let's learn and grow together!

# Conclusion

In this project, we’ve developed an Ansible playbook for deploying Jinja2 report across multiple servers,streamlining the configuration management process. The model, a beacon of performance, awaits those go into the beautiful world of Devops.
