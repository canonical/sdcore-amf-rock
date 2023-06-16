# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:sdcore-amf_1.3_amd64.rock docker-daemon:sdcore-amf:1.3
docker run sdcore-amf:1.3
```
