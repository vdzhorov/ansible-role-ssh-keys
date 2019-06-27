# ssh-keys

ssh-keys - A simple role to manage SSH keys

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

* Upload your public SSH keys to public_keys folder. Make sure your keys do not have whitespaces at the beginning or the end.
* Set your from_ips in vars section.
* Set the ansible user in vars from which deployment will happen.

## Deployment

Just run ```ansible-playbook -i '<IP>,' playbooks/ssh-keys.yml ``` and that is it!

## Built With

* [Ansible 2.8](https://docs.ansible.com/ansible/latest/roadmap/ROADMAP_2_8.html) - Ansible 2.8

## Authors

* **Valentin Dzhorov** - *Initial work* - [vdzhorov](https://github.com/vdzhorov)

## License

This project is licensed under the MIT License.

## Company
* **Delta.BG**

## Acknowledgments

* I am quite lazy sometimes and needed a simple role in order to manage user's keys across multiple servers.
