# OTC-workshop
heat orchestration templates to be used with the Open Telekom Cloud

Prerequisits: To use the templates you must have
- the python-openstack-client installed 
- the python-heatclient installed
- some of the provided templates may additionally require the OTC-extensions- an account on the Open Telekom Cloud
- the credentials of that account put into .ostackrc (minimally that is:
       export OS_AUTH_URL=https://iam.eu-de.otc.t-systems.com/v3
       export OS_PROJECT_NAME=eu-de
       export OS_DOMAIN_NAME=<your OTC domain>
       export OS_USERNAME=<your OTC username>
       export OS_IDENTITY_API_VERSION=3)
- you can put your OTC-password in there, too, but that is not really safe; rather source it separately outside of .ostackrc


Further useful documentation of the used tools:
- https://docs.openstack.org/heat/pike/template_guide/index.html  
