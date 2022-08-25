# hashcat-aws
hashcat on aws

To deploy, run:
ansible-playbook hashcat.yml -i env/hosts -e group_vars/all 

To destroy *ALL*, run:
ansible-playbook hashcat-destroy.yml -i env/hosts -e group_vars/all

--

On successful run the instance will self terminate.
