# Contributing

## Build and deploy

```bash
sudo snap install rockcraft --classic --edge
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:sdcore-amf_1.6.4_amd64.rock docker-daemon:sdcore-amf:1.6.4
docker run sdcore-amf:1.6.4
```
