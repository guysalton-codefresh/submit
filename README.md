# Codefresh plugins 

Codefresh Plugins are Docker images made especially for use in Codefresh freestyle steps. Each plugin facilitates a common task that would otherwise be difficult to achieve.
See each plugin readme for more info and usage instructions.
See [Contributing.md](Contributing.md) for details on how to submit a new plugin.

## Plugins

| Plugin|  Description| Tags|
| --- | --- |  --- |
| [Anchore Plugin](https://github.com/codefresh-plugins/anchore-plugin) | Analyze Docker images and generate a detailed manifest using Anchore| `anchore` `docker`|
| [Azure build](https://github.com/codefresh-plugins/azure-build-plugin) | Deploy Helm charts | `kubernetes` `helm`|
| [Codefresh Cli](https://github.com/codefresh-plugins/cli) | Operate on Codefresh resources | `cli` `codefresh`|
| [Slack Message Sender](https://github.com/codefresh-plugins/slack-message-sender)| Send message to slack| `slack` `notify`|
| [Slack Notifier](https://github.com/codefresh-plugins/slack-notifier)| Notify slack channel| `slack` `notify`|
| [Deploy to ECS](https://github.com/codefresh-plugins/ecs-deploy)| Deploy docker image to ECS| `ecs` `deploy` `containers` `aws`                         |
| [Annotate Gitlab Merge](https://github.com/codefresh-plugins/cf-gitlab-mr-annotate) | Annotate GitLab Merge Requests | `git` `gitlab` `ci`   |
| [Deploy Kompose](https://github.com/codefresh-plugins/cf-kompose-plugin)| Deploy Docker Compose to Kubernetes cluster with Kubernetes [Kompose](http://kompose.io) | `docker` `docker-compose` `kompose` `deploy` `kubernetes` |
| [GitHub PR](https://github.com/codefresh-plugins/github-pr-plugin)| Operates on pull requests on GitHub | `github` `pull-request` |
| [Run Jenkins Jobs](https://github.com/codefresh-plugins/cf-run-jenkins-jobs)| Run jenkins job from codefresh pipeline| `jenkins` `job`|
| [Deploy to DCOS](https://github.com/codefresh-plugins/cf-deploy-dcos) | Deploy application image to DC/OS cluster | `dcos` `deploy` `containers` |
| [Interact with Jira](https://github.com/codefresh-plugins/jira-cli-docker) | Interact with Jira from codefresh pipelines| `jira` `workflow`|
| [Makisu](https://github.com/codefresh-plugins/cfstep-makisu) | Building images using the Makisu tool | `makisu` `uber`|
| [release to npm](https://github.com/codefresh-plugins/npm-publish) | Release npm modules from a pipeline | `npm` |
| [Twistlock](https://github.com/codefresh-plugins/cf-twistlock) | Security scanning of docker images using Twistlock | `security` |
| [Aqua](https://github.com/codefresh-plugins/cfstep-aqua) | Security scanning of docker images using Aqua | `security` |
| [Paclair](https://github.com/codefresh-plugins/cfstep-paclair) |  Security scanning of Docker images using paclair | `security` |
| [Import Docker Images](https://github.com/codefresh-plugins/cf-import-image) | Import Docker images metadata into Codefresh| `docker` `codefresh`|
| [Google KMS](https://github.com/codefresh-plugins/google-kms) | Encryption/Decryption with Google KMS| `KMS` `codefresh`|
| [Github Release](https://github.com/codefresh-plugins/cfstep-github-release) | Managing GitHub releases | `github` `release`|
| [Google GKE](https://github.com/codefresh-plugins/plugin-gke) | GKE Clusters | `GKE` `codefresh`|
| [Vault](https://github.com/codefresh-plugins/cf-vault-plugin) | Export Vault Key/Value pairs as ENV variables | `Vault` `codefresh`|
| [Blue Green Deployment](https://github.com/codefresh-plugins/k8s-blue-green-deployment) | Perform blue/green deployments on a Kubernetes cluster| `deploy` `blue-green` `progressive`|
| [Canary Deployment](https://github.com/codefresh-plugins/k8s-canary-deployment) | Perform blue/green deployments on a Kubernetes cluster| `deploy` `canary` `progressive`|
| [Gitter Notifier](https://github.com/codefresh-plugins/gitter-notifier) | Notify gitter channel| `notifications` `gitter`|
| [Sendgrid](https://github.com/codefresh-plugins/sendgrid-plugin) | Send an email notification via sendgrid| `notifications` `email`|
| [Telegram Notifier](https://github.com/codefresh-plugins/telegram-notifier) | Notify on Telegram| `notifications` `telegram`|
| [SMS Notifier](https://github.com/codefresh-plugins/send-sms) | Send SMS notification with Twilio| `notifications` `twilio` `sms`|


