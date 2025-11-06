To run the playbook:

oc login

ansible-playbook playbooks/ibm_quarkus_beginner_workshop.yml -e ACTION=create


## requirements

python3 -m pip install --user jmespath kubernetes ansible openshift
