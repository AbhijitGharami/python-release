# python

To vendor python package into your release, run:

```
$ bosh vendor-package python-2.7 ~/workspace/bosh-packages/python-release
```

Included packages:

- python-2.7

To use `python-*` package for compilation in your packaging script:

```bash
#!/bin/bash -eu
source /var/vcap/packages/python-2.7/bosh/compile.env
pip install ...
```
