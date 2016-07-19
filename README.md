# Dartino API docs

This repo contains generated API documentation for the Dartino project. These
are published at http://api.dartino.org.

## Making changes

These docs are changed as part of the Dartino SDK promote process, see [the SDK
wiki on promoting](https://github.com/dartino/sdk/wiki/Pushing-out-a-new-dev-channel-release).

## Publishing changes

A Travis CI job automatically detect all pushes to this repo, and when those
happen deploys the contents of the `public` directory to Firebase Hosting.

[![Deployment status -](https://travis-ci.org/dartino/api.dartino.org.svg?branch=master](https://travis-ci.org/dartino/api.dartino.org)
