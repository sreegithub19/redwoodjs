![RedwoodJS Logo](https://github.com/vercel/vercel/blob/main/packages/frameworks/logos/redwoodjs.svg)

# RedwoodJS Example

This directory is a brief example of a [RedwoodJS](https://redwoodjs.com) app with [Serverless Functions](https://vercel.com/docs/concepts/functions/serverless-functions) that can be deployed to Vercel with zero configuration.

## Deploy Your Own

Deploy your own RedwoodJS project, along with Serverless Functions, with Vercel.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vercel/vercel/tree/main/examples/redwoodjs&template=redwoodjs)

_Live Example: https://redwood-template.vercel.app_

### How We Created This Example

To get started with RedwoodJS on Vercel, you can [use Yarn to initialize](https://redwoodjs.com/tutorial/installation-starting-development) the project:

```shell
$ yarn create redwood-app ./my-redwood-app
```

Steps:

- node -v
  v16.10.0
- yarn -v
  1.15.0
- npm install
  - yarn create redwood-app ./netlify-deploy (includes git init)
- code netlify-deploy/
- yarn redwood generate page home /
- yarn redwood generate page my-page
- yarn rw dev (to start in local : http://localhost:8910/)

Git:

- git add . && git commit -m "C" && git push origin main
