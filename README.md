# helm-charts

Create a helm chart repo in github

```
$ In the repository containing the Helm chart
i.e.

$ helm package .
Successfully packaged chart and saved it to: SCM/polarpoint/thanos-helm-chart/thanos/thanos-0.5.1.tgz
$ cp ../../thanos/thanos-0.5.1.tgz . 
$ helm repo index . # create or update the index.yaml for repo
$ git add .
$ git commit -m 'Added Thanos Helm Chart'
$ git push
```
