# tekton-pipelinerun-cleaner
tekton pipelinerun cleaner using helm

# Installation
Install tekton pipelinerun cleaner using helm.
```
$ helm install pipelinerun-cleaner-v1 pipelinerun-cleaner
```
Check for installing.

```
$ helm list
NAME                    NAMESPACE       REVISION        UPDATED                                 STATUS          CHART                           APP VERSION
pipelinerun-cleaner-v1  default         1               2024-06-20 03:23:12.347301236 +0000 UTC deployed        pipelinerun-cleaner-0.1.0       1.16.0

$ kubectl get cronjob
NAME                          SCHEDULE    SUSPEND   ACTIVE   LAST SCHEDULE   AGE
pipelinerun-cleaner-cronjob   0 0 * * *   False     0        <none>          15s
```

## Uninstall tekton pipelinerun
```
$ helm uninstall pipelinerun-cleaner-v1
```

# License
Apache License, Version 2.0