# telco-ran-ga-docs

Demo of delivering the Red Hat Telco RAN 4.10 docs in a container. Container is deployed to https://quay.io/repository/rhn_support_aireilly/telco-ran-410-docs

To run the container, do the following:

Pull the latest container from quay.io:
```
podman pull quay.io/rhn_support_aireilly/telco-ran-410-docs:latest
```
Run the container locally:
```
$ podman container run -d -p 5000:80 quay.io/rhn_support_aireilly/telco-ran-410-docs:latest
```

The container hosted docs are served at: http://localhost:5000/index.html
