# To practice CI/CD with gitlab and github.

## Notes(Some of exceptions)
1. Ansible problems:
    * /ect/ansible/hosts
    ```
    [workshop:vars]
    ansible_port=22
    ansible_user=vagrant
    ansible_host=127.0.0.1
    ansible_ssh_pass=vagrant
    ansible_become_pass=vagrant

    [workshop]

    localhost
    ```

    * /ect/ansible/ansible.cfg
    ```
    [defaults]
    host_key_checking=False
    ```
2. Virtual Box:
    * Set VM
    * Set gitlab-runner

3. Set envs
    * stg_domain_name = 127.0.0.1
    * stg_host_ip = 127.0.0.1
    * stg_user_user = vagrant
    * stg_user_pass = vagrant
    * prod_domain_name = 127.0.0.1
    * prod_host_ip = 127.0.0.1
    * prod_user_user = vagrant
    * prod_user_pass = vagrant