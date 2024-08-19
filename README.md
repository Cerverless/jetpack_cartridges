This repository contains input for the Jetpack CI/CD pipeline for [Kubernetes](https://github.com/jrb-s2c-github/atomika)

It can be run by clearing out vars.yml in the jetpack folder followed by the following command:
```
ansible-playbook -i atomika/inventory/basic_inventory.yml jetpack/deploy.yml -K -e k8s_input_dir=../../jetpack_cartridges/mergasort
```
