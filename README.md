# asdf-oc

![CI](https://github.com/sqtran/asdf-oc/workflows/CI/badge.svg?branch=master)


[OpenShift Client CLI](https://github.com/openshift/oc) (oc) plugin for [asdf](https://github.com/asdf-vm/asdf) version manager.

## Install

```bash
asdf plugin add oc https://github.com/sqtran/asdf-oc.git
asdf install oc latest
```

## Use

Check the [asdf](https://github.com/asdf-vm/asdf) README for instructions on how to install and manage versions of oc.


## Note

This plugin no longer bundles `kubectl` along with `oc`.  If you need plain vanilla `kubectl`, you'll need to install that asdf-plugin separately.