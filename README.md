# Awesome Hasura
# ![Awesome Hasura](asset/awesome-hasura.svg)

> A curated list of awesome things related to the [hasura](https://hasura.io) ecosystem.

## Contents

- [Hasura](#hasura)
- [Tools and Extensions](#tools-and-extensions)
- [Tutorials](#tutorials)
- [Templates and Examples](#templates-and-examples)
- [Managed Services](#managed-services)
- [Blogs](#blogs)

## Hasura

Blazing fast, instant realtime GraphQL APIs on Postgres with fine grained access control, also trigger webhooks on database events.

- [Offical Website](https://hasura.io/)
- [Docs](https://docs.hasura.io/1.0/graphql/manual/index.html)
- [GitHub](https://github.com/hasura/graphql-engine)
- [Discord](https://discord.gg/hasura)
- [Blog](https://blog.hasura.io/)
- [YouTube](https://www.youtube.com/channel/UCZo1ciR8pZvdD3Wxp9aSNhQ)
- [Twitter](https://twitter.com/hasurahq)

## Tools and Extensions

- [Hasura Backend Plus](https://github.com/elitan/hasura-backend-plus) - Auth + Storage for Hasura.
- [Hasura JWT Auth](https://github.com/sander-io/hasura-jwt-auth) - Hasura JWT auth using PostgreSQL
- [Hasura Auto Tracker](https://github.com/axis-tech/hasura-auto-tracker) - Configure Hasura to track tables, views and functions using configuration driven process.
- [Hasura Squasher](https://github.com/domasx2/hasura-squasher) - CLI utility to squash Hasura Migrations
- [Hasura Segment Source](https://github.com/aaronhayes/hasura-segment-source) - The easiest way to connect Hasura and Segment!
- [hasura-cli](https://github.com/jjangga0214/hasura-cli) - Hasura CLI as an npm package
- [Hasura Connect](https://github.com/Flutterando/hasura_connect) - A client library to talk to Hasura from Flutter/Dart apps
- [graphql-codegen-hasura](https://github.com/ahrnee/graphql-codegen-hasura) - code-generator plugins for hasura/apollo-gql/typescript development
- [HasuraConfigurator](https://github.com/beepsoft/hasuraconf) - Configure a Hasura server based on Java JPA (Hibernate) annotations
- [React Admin Hasura Adapter](https://github.com/Steams/ra-data-hasura-graphql) - [react-admin](https://marmelab.com/react-admin/) data provider for Hasura GraphQL (build admin interfaces with very little code) 
- [hasura-orm](https://github.com/timeshift92/hasura-orm) - orm based request generator 
- [hasura-om](https://github.com/mrspartak/hasura-om) - Fragment based orm request generator with built in auto-table lookup and base fragment builder. Also comes with a query/mutation/subscribe libraries built in
- [hql-tag](https://github.com/product-ride/hql-tag) - A Hasura wrapper on graphql-tag that helps in writing clean & elegant queries
- [hasura-sdk](https://github.com/aaronhayes/hasura-sdk) - A node wrapper for Hasura's schema and metadata API's, written in TypeScript. 
- [hasura-metadata-patcher](https://github.com/puzl-ee/hasura-metadata-patcher) - CLI tool to patch Hasura `metadata.json` file with needed objects or with another Hasura metadata file. You can use it to deploy complex CI/CD flows for applications, which are using Hasura on a backend.
- [Hasura Helm chart](https://github.com/platyplus/platyplus/tree/master/charts/hasura) - Deploy Hasura on a [Kubernetes](https://kubernetes.io/) cluster with [Helm](https://helm.sh/).
- [hasura-supertokens](https://github.com/offscriptio/hasura-supertokens) - A webhook implementation to connect Hasura with [Supertokens](https://supertokens.io/) for role-based authentication.
- [xsura](https://github.com/joaom182/xsura) Migrate data smoothly between two Hasura servers
- [fastify-hasura](https://github.com/ManUtopiK/fastify-hasura) - A Fastify plugin to have fun with Hasura.

## Built with Hasura
- [MLCraft](https://github.com/mlcraft-io/mlcraft) Low-code metrics store and an Open Source alternative to Looker

## Tutorials

- [Learn](https://learn.hasura.io)
- [Production Checklist](https://docs.hasura.io/1.0/graphql/manual/deployment/production-checklist.html)
- [Lucky Hasura Docker](https://github.com/KCErb/lucky-hasura-docker) - Guide / Tutorial / Boilerplate for using [Lucky](https://luckyframework.org/) for business logic and Hasura for GraphQL in Docker. Includes production-ready monitoring and automatic deployment / DB management.

## Templates and Examples

- [Hasura Super App](https://hasura.io/reference-app/) - The official full-featured Hasura reference app using Next.js, TypeScript, Apollo Client.
- [Hasura Community](https://github.com/hasura/graphql-engine/tree/master/community) - Community Contributed boilerplates, example apps, and todos.
- [NextJS - Auth0 - Hasura](https://github.com/vgrafe/nextjs-auth0-hasura) - Template project with NextJs, Auth0, Hasura and Apollo.
- [Rust Hasura](https://github.com/ronanyeah/rust-hasura) - Boilerplate/example of using Rust as a Remote Schema. It features login, signup, JWT, hashed passwords and typesafe requests.
- [Hasura Starter](https://github.com/jjangga0214/hasura-starter) - A bolerplate, cheatsheet, and guide for beginners.
- [Pulumi AWS EKS Deployment Sample](https://github.com/aaronhayes/pulumi-hasura-aws-eks-example) - A guide for deploying Hasura to AWS EKS using [Pulumi](https://www.pulumi.com/).
- [Hasura Starter](https://github.com/jjangga0214/hasura-starter) - A bolierplate, cheatsheet, and guide for beginners.
- [hasura-node-monolith-example](https://github.com/zenflow/hasura-node-monolith-example) - Example of a monolithic web application using Hasura GraphQL Engine + Node.js + Next.js

## Managed Services

- [nHost](https://nhost.io/) - Hasura as a Service!
- [Hasura Cloud](https://hasura.io/cloud) - Fully managed, production ready GraphQL API as a service to help you build modern apps faster. Get started in 30 seconds!

## Blogs

- [Migrating from Firebase to Hasura](https://medium.com/@clapie.florent/how-i-scale-firebase-by-migrating-to-graphql-and-speed-up-my-development-by-10x-200b4a3068a0?sk=cf4a748bfa93d061ad84fd194d5e87bb)
- [Resetting Hasura Migrations](https://blog.hasura.io/resetting-hasura-migrations/)
