# helm-charts

Create a helm chart repo in github

```
$ In the repository containing the Helm chart
i.e. cd fluentd-cloudwatch
❯ helm package .
Successfully packaged chart and saved it to: /Users/surjitbains/Documents/git/SCM/polarpoint/helm-charts/fluentd-cloudwatch/fluentd-cloudwatch-0.12.1.tgz
❯ cp fluentd-cloudwatch-0.12.1.tgz ../
❯ helm repo index --url https://polarpoint-io.github.io/helm-charts/ .
❯ git add .
❯ git commit -m 'fluentd-cloudwatch'
❯ git push
```

Configure the “helm-charts” repository as a Github pages site

In the “settings” section of your git repository, scroll down to Github Pages section and configure it as follow:


