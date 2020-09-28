FROM busybox:latest

EXPOSE 2020 2121

### LABELS can be used to trace docker image to its source code. The LABELS will be available under "docker info" in Artifactory.
### LABELS can also be viewed using "docker inspect <imageid>".
### Used in continuous integration and continuous delivery builds. Developer builds take default values
LABEL Build.Number=${project.version} Build.Date=${build.timestamp} Git.Commit=${git.revision} Git.Branch=${git.branch}

