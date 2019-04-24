### Coding Experts B.V.

## Gitlab CI docker image

## Toolchain

- git
- docker client
- ssh client, sshpass
- sshx (alias for `sshpass -e ssh -o StrictHostKeyChecking=no $@`)
- curl, wget
- mcli (Minio client)
- kubectl, helm


## Build

```
docker build -t codingexperts/gitlab-ci .
```

## Publish

```
docker push codingexperts/gitlab-ci
```

