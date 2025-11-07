To run the playbook:

## requirements

python3 -m pip install --user jmespath kubernetes ansible openshift


##

oc login <api-url> -u <username> -p <password>

ansible-playbook playbooks/ibm_quarkus_beginner_workshop.yml -e ACTION=create -e ibm_quarkus_beginner_workshop_install_openshift_gitops=true -e ibm_quarkus_beginner_workshop_install_app_of_apps=true


