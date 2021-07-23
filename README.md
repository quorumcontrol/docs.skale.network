# Docs

[![Netlify Status](https://api.netlify.com/api/v1/badges/6e1a2f3c-f2c8-43bf-a3cd-40e2a9530fe0/deploy-status)](https://app.netlify.com/sites/tender-lichterman-b7b0cc/deploys)

Requirements:

* Node v14 LTS

## UI Development

For UI development serving examples from ui/preview-src, install npm libraries in the ui folder and run the development environment:

```console
cd ui
yarn
yarn dev
```

## Run from scratch

To pull from live repos in the playbook and serve from the UI bundle, first install ui npm libraries to allow the bundle to be built. Then cd into the parent folder, install the libraries and prepare the bundle. Then run the playbook and serve the files.

```console
yarn
yarn prepare:ui     # build UI
yarn prepare:docs   # build docs
yarn serve
```
