# Linux images

Images size varies as our upstream adds/removes/modifies tools.
Currently: ~40GB as of 02.08.2021

Image is built upon `ghcr.io/catthehacker/ubuntu:runner-*` as it provides better base than plain Ubuntu (and if you use `ubuntu:act-*`/`ubuntu:runner-*` it will save on layers)

Tools currently not included:
  - MySQL (because it slows the whole build and fails)
  - PostgreSQL (same as above)
  - certain other tools also might be unavailable as it is still work in progress (contribution appreciated)

Tags available:
  - `ghcr.io/catthehacker/ubuntu:full-latest` (currently `ubuntu-20.04`)
  - `ghcr.io/catthehacker/ubuntu:full-20.04`
  - `ghcr.io/catthehacker/ubuntu:full-18.04`

## [`ubuntu-16.04` will be deprecated soon](https://github.com/actions/virtual-environments/issues/3287)
