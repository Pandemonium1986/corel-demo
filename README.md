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

-   [ ] Start the two vagrant boxes.
-   [ ] Get the github [token](http://192.168.66.100/#/templates/job_template/9?template_search=page_size:20;order_by:name;type:workflow_job_template,job_template) for awx and modify it in the [hooks](https://github.com/Pandemonium1986/corel-demo/settings/hooks) section of the project.
-   [ ] Explain the purpose of the demo.
-   Gitops approach to configuration management (Tower Graph).
-   Gitops approach to application deployment (Node Graph).
-   [ ] Show Awx.
-   [ ] Show Prometheus.
-   [ ] Show Grafana.
-   [ ] Start the demo with the presentation of the prometheus-configuration.yml playbook.
-   [ ] Generate awx_bearer_token
-   [ ] Generate branch (already exists)
-   [ ] Push awx_bearer_token 😱.
-   [ ] Pull Request.
-   [ ] Closing the Pr.
-   [ ] Check the Webhook.
-   [ ] Check the Awx job.
-   [ ] Check the Grafana dashboard.

## Authors

-   **Michael Maffait** - _Initial work_ - [Pandemonium1986](https://github.com/Pandemonium1986)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details
