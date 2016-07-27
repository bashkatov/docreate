# docreate
Create new DigitalOcean droplet, using Ansible and Digital Ocean API V2

Get your API token from DigitalOcean and put it to the ~/.ssh/digital_ocean_token file,

$ git clone https://github.com/bashkatov/docreate.git
$ cd docreate

Set 'do_*' parameters in digitalocean.yml

$ ansible-playbook digitalocean.yml
