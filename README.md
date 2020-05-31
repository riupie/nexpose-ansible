## NOTE
Forked from https://github.com/eanylin/ansible-lab/


## Integration of Ansible Tower with Nexpose Rapid7

The playbooks in this repository is meant to

1. Add a new asset and perform a scan on it
2. Perform ad hoc scan on an asset
3. This playbook could be used one individual or multiple asset.

### Adding New Asset to Nexpose Rapid7

User will need to provide information for the following variables

1. target_servers - Server to be added
2. site_id - The ID of site in Nexpose Rapid7
3. template_id - The ID of template that will be used during scan. ( still not work).
The workflow will perform the following tasks

1. Create entry for the new VM in Nexpose Rapid7
2. Perform a scan on the new VM
3. Generate a summary report and email the HTML report to relevant parties


### Perform Ad Hoc Scan on an Asset

User will need to provide information for the following variables

1. target_servers - Server to be added
2. site_id - The ID of site in Nexpose Rapid7
