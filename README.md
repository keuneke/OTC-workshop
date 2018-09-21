# OTC-workshop
heat orchestration templates to be used with the Open Telekom Cloud

Prerequisits: To use the templates you must have
- the python-openstack-client installed 
- the python-heatclient installed
- some of the provided templates may additionally require the OTC-extensions
- an account on the Open Telekom Cloud
- the credentials of that account put into .ostackrc (minimally that is:
       export OS_AUTH_URL=https://iam.eu-de.otc.t-systems.com/v3
       export OS_PROJECT_NAME=eu-de
       export OS_DOMAIN_NAME=<your OTC domain>
       export OS_USERNAME=<your OTC username>
       export OS_IDENTITY_API_VERSION=3)
- you can put your OTC-password in there, too, but that is not really safe; rather export it separately outside of .ostackrc

If you want to use a vagrant/virtualbox-VM with the clients already installed, you can find a prepackaged box at https://app.vagrantup.com/keuneke/boxes/OTC-tools/versions/0.4 
Inside the box, the .ostackrc that you'll want to source (after editing in your username and domain of course) is located at /home/OTC-workshop/.ostackrc

Useful documentation for using heat orchestration templates:
- https://docs.openstack.org/heat/pike/template_guide/index.html  
