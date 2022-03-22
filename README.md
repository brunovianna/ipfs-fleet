# ipfs-fleet

Deployment of go-ipfs on balena.

## What is IPFS?

IPFS is a global, versioned, peer-to-peer filesystem.
For more info see: https://docs.ipfs.io/introduction/overview/

## How to use this fleet

The IPFS API will be exposed on local network:
http://local_ip:5001/webui

## Deploy with Balena

[![balena deploy button](https://www.balena.io/deploy.svg)](https://dashboard.balena-cloud.com/deploy?repoUrl=https://gitlab.com/coletivo-coolab/ipfs-balena/ipfs-fleet)

## Pushing locally
You need to get the code from the submodule go-ipfs with
```bash
git submodule init
git submodule update
```

## Getting Help

If you're having any problem, please [raise an issue](https://github.com/brunovianna/ipfs-fleet/issues/new) on GitHub and we will be happy to help.


## License

IPFS is free software, and may be redistributed under the terms specified in the [license](https://gitlab.com/coletivo-coolab/ipfs-balena/ipfs-fleet/-/blob/main/LICENSE).
