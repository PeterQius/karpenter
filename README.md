# Karpenter

Catalog of Tekton steps for CI/CD pipelines.

This repository is a work in progress.

## Steps

* git
* mvn
* buildah
* kubectl

## Pipeline

    kubectl -f apply ./tasks/git.yaml
    kubectl -f apply ./tasks/mvn.yaml
    kubectl -f apply ./tasks/buildah.yaml
    kubectl -f apply ./tasks/kubectl.yaml

    kubectl -f apply pipeline.yaml

    tkn pipelinerun logs -f hello-pipeline-run


