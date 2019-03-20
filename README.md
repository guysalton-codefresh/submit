# Codefresh plugins 

Codefresh Plugins are Docker images made especially for use in Codefresh freestyle steps. Each plugin facilitates a common task that would otherwise be difficult to achieve.
See each plugin readme for more info and usage instructions.

## Plugins

| Plugin|  Description| Tags|
| --- | --- |  --- |
| [Helm](https://github.com/codefresh-plugins/helm) | Deploy Helm charts | `kubernetes` `helm`|
| [Codefresh Cli](https://github.com/codefresh-plugins/codefresh-cli) | Operate on Codefresh resources | `cli` `codefresh`|
| [Slack](https://github.com/codefresh-plugins/slack)| Send message to slack| `slack` `notify`|
| [Deploy to ECS](https://github.com/codefresh-plugins/ecs-deploy)| Deploy docker image to ECS| `ecs` `deploy` `containers` `aws`                         |
| [Annotate Gitlab Merge](https://github.com/codefresh-plugins/cf-gitlab-mr-annotate) | Annotate GitLab Merge Requests | `git` `gitlab` `ci`   |
| [Deploy Kompose](https://github.com/codefresh-plugins/kompose)| Deploy Docker Compose to Kubernetes cluster with Kubernetes [Kompose](http://kompose.io) | `docker` `docker-compose` `kompose` `deploy` `kubernetes` |
| [GitHub PR](https://github.com/codefresh-plugins/github-pr)| Operates on pull requests on GitHub | `github` `pull-request` |
| [Run Jenkins Jobs](https://github.com/codefresh-plugins/cf-run-jenkins-jobs)| Run jenkins job from codefresh pipeline| `jenkins` `job`|
| [Deploy to DCOS](https://github.com/codefresh-plugins/cf-deploy-dcos) | Deploy application image to DC/OS cluster | `dcos` `deploy` `containers` |
| [Interact with Jira](https://github.com/codefresh-plugins/jira-cli) | Interact with Jira from codefresh pipelines| `jira` `workflow`|
| [Makisu](https://github.com/codefresh-plugins/makisu) | Building images using the Makisu tool | `makisu` `uber`|
| [release to npm](https://github.com/codefresh-plugins/release-to-NPM) | Release npm modules from a pipeline | `npm` |
| [Twistlock](https://github.com/codefresh-plugins/cfstep-twistlock) | Security scanning of docker images using Twistlock | `security` |
| [Clair](https://github.com/codefresh-plugins/clair) |  Security scanning of Docker images using Clair | `security` |
| [Import Docker Images](https://github.com/codefresh-plugins/import-docker-images) | Import Docker images metadata into Codefresh| `docker` `codefresh`|
| [Google KMS](https://github.com/codefresh-plugins/google-kms) | Encryption/Decryption with Google KMS| `KMS` `codefresh`|
| [Github Release](https://github.com/codefresh-plugins/github-release) | Managing GitHub releases | `github` `release`|
| [Google GKE](https://github.com/codefresh-plugins/gke) | GKE Clusters | `GKE` `codefresh`|
| [Vault](https://github.com/codefresh-plugins/vault) | Export Vault Key/Value pairs as ENV variables | `Vault` `codefresh`|
