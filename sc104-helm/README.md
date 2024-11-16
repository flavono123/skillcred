# Developing Helm Charts (SC104)

[catalog link](https://training.linuxfoundation.org/certification/helm/)

## disclaimer

```shell
❯ helm version
version.BuildInfo{Version:"v3.16.3", GitCommit:"cfd07493f46efc9debd9cc1b02a0961186df7fdf", GitTreeState:"dirty", GoVersion:"go1.23.3"}
```

mock questions are based on the record from my coworker who already passed the exam and chatgpt's response, the former is by a prompt.

recommend to use vim

## mock q1

> Scenario: You are managing a Helm chart that deploys a single container Deployment. Your task is to modify the templates/deployment.yaml file to add the annotation "cluster-autoscaler.kubernetes.io/safe-to-evict": "false" to the Deployment. This annotation ensures that the cluster autoscaler will not evict this Deployment under any conditions. Make the necessary changes to the Helm template to add this annotation.
