# mfe-marketing

Microfrontend on React (Udemy - Stephen Grider)

Webpack 5 Module Federation
React 17 - from npm init

Dependencies
npm install webpack@5.68.0 webpack-cli@4.10.0 webpack-dev-server@4.7.4 faker@5.1.0 html-webpack-plugin@5.5.0

Modules:
Host: container

Remotes:

- marketing
- dashboard
- auth

Deployment:

- GitHub Actions - Workflows and Environment Secrets
- AWS S3 Bucket (files/objects - index.html, RemoteEntry.js, main.js, etc)
- AWS Cloudfront (domain)
  - invalidation
- AWS IAM to access S3 and Cloudfront
- GitHub Pull Requests - Dev to Deployment workflow
