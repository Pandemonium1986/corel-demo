# Corel Demo

![Github pipeline status](https://github.com/Pandemonium1986/corel-demo/workflows//Molecule%20-%20Branches%20actions/badge.svg)
![GitHub release](https://img.shields.io/github/release/Pandemonium1986/corel-demo.svg?logo=github)
![Github license](https://img.shields.io/github/license/Pandemonium1986/corel-demo.svg?logo=github)

Collection of resources used for demos on vagrant-corel

## Getting Started

These instructions will allow you to play the corel demo as part of the GitOps webinar.

### Prerequisites

Make sure that awx is publicly accessible.  
`Port forwarding 8086 -> 80`

## Running the demo

### Configuration

- [ ] Start the two vagrant boxes.
- [ ] Get the github [token](http://192.168.66.100/#/templates/job_template/9?template_search=page_size:20;order_by:name;type:workflow_job_template,job_template) for awx and modify it in the [hooks](https://github.com/Pandemonium1986/corel-demo/settings/hooks) section of the project.
- [ ] Explain the purpose of the demo.
- Gitops approach to configuration management (Tower Graph).
- Gitops approach to application deployment (Node Graph).
- [ ] Show Awx.
- [ ] Show Prometheus.
- [ ] Show Grafana.
- [ ] Start the demo with the presentation of the prometheus-configuration.yml playbook.
- [ ] Generate awx_bearer_token
- [ ] Generate branch demo/configuration
- [ ] Push awx_bearer_token 😱.
- [ ] Pull Request (No github actions).
- [ ] Closing the Pr.
- [ ] Check the Webhook.
- [ ] Check the Awx job.
- [ ] Check the Grafana dashboard.

### Node exporter

- [ ] Continue the demo with with the presentation of the node-exporter-install playbook.
- Show playbook.yml
- Show molecule.yml
- Show workflows/molecule.yml
- [ ] Generate branch demo/node
- [ ] Modify the default version of pne (1.0.X).
- [ ] Pull Request (github actions).
- [ ] Check actions results.
- [ ] Check the Webhook (is not triggered).
- [ ] Check the Awx job (is not triggered).
- [ ] Modify the default version of pne (1.0.1).
- [ ] Execute the job manually.
- [ ] Check the Grafana dashboard.
- [ ] Check actions results.

## Authors

- **Michael Maffait** - _Initial work_ - [Pandemonium1986](https://github.com/Pandemonium1986)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details
