
## requirements

python3 -m pip install --user jmespath kubernetes ansible openshift

## To run the playbook:


1. OpenShift Login

    oc login with token from OpenShift Console

    (or) 

    ```
    oc login <api-url> -u <admin-user> -p <admin-password>
    ```

2. Run the Playbook

    ```
    ansible-playbook playbooks/ibm_quarkus_beginner_workshop.yml -e ACTION=create  -e workshop_user=<username> -e workshop_password=<password>
    ```