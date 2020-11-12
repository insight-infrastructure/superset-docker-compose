# superset-docker-compose

Docker compose deployment of superset with nginx parameterized so that it can be wrapped with ansible in the [ansible-role-superset-docker](https://github.com/insight-infrastructure/ansible-role-superset-docker) role and deployed in the [terraform-aws-superset-docker](https://github.com/insight-infrastructure/terraform-aws-superset-docker) terraform module. 

Modify the `.env` file to override any variables in the `superset/superset_config.py` file. 

