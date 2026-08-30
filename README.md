# Awesome Hasura with stars

# ![Awesome Hasura](asset/awesome-hasura.svg)

> A curated list of awesome things related to the [hasura](https://hasura.io) ecosystem.

## Contents

* [Hasura](#hasura)
* [Tools and Extensions](#tools-and-extensions)
* [Tutorials](#tutorials)
* [Templates and Examples](#templates-and-examples)
* [Managed Services](#managed-services)
* [Blogs](#blogs)

## Hasura

Blazing fast, instant realtime GraphQL APIs on Postgres with fine grained access control, also trigger webhooks on database events.

* [Offical Website](https://hasura.io/)
* [Docs](https://docs.hasura.io/1.0/graphql/manual/index.html)
* [GitHub](https://github.com/hasura/graphql-engine) ⭐ 32,107 | 🐛 2,374 | 🌐 TypeScript | 📅 2026-08-19
* [Discord](https://discord.gg/hasura)
* [Blog](https://blog.hasura.io/)
* [YouTube](https://www.youtube.com/channel/UCZo1ciR8pZvdD3Wxp9aSNhQ)
* [Twitter](https://twitter.com/hasurahq)

## Tools and Extensions

* [Hasura Auth](https://github.com/nhost/hasura-auth) ⚠️ Archived - Authentication for Hasura. Email+Password, Magic Link, Providers (Google, GitHub, Facebook, etc).
* [Hasura Storage](https://github.com/nhost/hasura-storage) ⚠️ Archived - Storage for Hasura. Built on top of S3.
* [React Admin Hasura Adapter](https://github.com/Steams/ra-data-hasura-graphql) ⭐ 212 | 🐛 40 | 🌐 JavaScript | 📅 2023-01-05 - [react-admin](https://marmelab.com/react-admin/) data provider for Hasura GraphQL (build admin interfaces with very little code)
* [Hasura Connect](https://github.com/Flutterando/hasura_connect) ⚠️ Archived - A client library to talk to Hasura from Flutter/Dart apps
* [graphql-codegen-hasura](https://github.com/ahrnee/graphql-codegen-hasura) ⭐ 156 | 🐛 33 | 🌐 TypeScript | 📅 2023-01-06 - code-generator plugins for hasura/apollo-gql/typescript development
* [hasura-cli](https://github.com/jjangga0214/hasura-cli) ⭐ 91 | 🐛 9 | 🌐 TypeScript | 📅 2024-09-10 - Hasura CLI as an npm package
* [Hasura JWT Auth](https://github.com/sander-io/hasura-jwt-auth) ⭐ 84 | 🐛 2 | 🌐 PLpgSQL | 📅 2019-08-27 - Hasura JWT auth using PostgreSQL
* [Hasura Auto Tracker](https://github.com/axis-tech/hasura-auto-tracker) ⚠️ Archived - Configure Hasura to track tables, views and functions using configuration driven process.
* [hasura-supertokens](https://github.com/offscriptio/hasura-supertokens) ⭐ 45 | 🐛 10 | 🌐 TypeScript | 📅 2023-01-17 - A webhook implementation to connect Hasura with [Supertokens](https://supertokens.io/) for role-based authentication.
* [hql-tag](https://github.com/product-ride/hql-tag) ⭐ 42 | 🐛 23 | 🌐 JavaScript | 📅 2023-01-06 - A Hasura wrapper on graphql-tag that helps in writing clean & elegant queries
* [Hasura Helm chart](https://github.com/platyplus/platyplus/tree/master/charts/hasura) ⭐ 37 | 🐛 5 | 🌐 TypeScript | 📅 2022-07-26 - Deploy Hasura on a [Kubernetes](https://kubernetes.io/) cluster with [Helm](https://helm.sh/).
* [fastify-hasura](https://github.com/ManUtopiK/fastify-hasura) ⭐ 31 | 🐛 10 | 🌐 JavaScript | 📅 2025-01-01 - A Fastify plugin to have fun with Hasura.
* [hasura-orm](https://github.com/timeshift92/hasura-orm) ⭐ 26 | 🐛 0 | 🌐 TypeScript | 📅 2021-06-08 - orm based request generator
* [hasura-sdk](https://github.com/aaronhayes/hasura-sdk) ⭐ 24 | 🐛 21 | 🌐 TypeScript | 📅 2023-01-06 - A node wrapper for Hasura's schema and metadata API's, written in TypeScript.
* [hasura-om](https://github.com/mrspartak/hasura-om) ⭐ 22 | 🐛 28 | 🌐 JavaScript | 📅 2023-03-04 - Fragment based orm request generator with built in auto-table lookup and base fragment builder. Also comes with a query/mutation/subscribe libraries built in
* [Hasura Squasher](https://github.com/domasx2/hasura-squasher) ⭐ 21 | 🐛 6 | 🌐 TypeScript | 📅 2022-01-15 - CLI utility to squash Hasura Migrations
* [HasuraConfigurator](https://github.com/beepsoft/hasuraconf) ⭐ 19 | 🐛 6 | 🌐 Kotlin | 📅 2024-08-30 - Configure a Hasura server based on Java JPA (Hibernate) annotations
* [hasura-metadata-patcher](https://github.com/puzl-ee/hasura-metadata-patcher) ⭐ 14 | 🐛 2 | 🌐 Python | 📅 2021-12-19 - CLI tool to patch Hasura `metadata.json` file with needed objects or with another Hasura metadata file. You can use it to deploy complex CI/CD flows for applications, which are using Hasura on a backend.
* [Hasura permissions viewer](https://github.com/socialgouv/hasura-permissions-viewer) ⭐ 12 | 🐛 5 | 🌐 JavaScript | 📅 2025-11-27 - Generate an HTML summary of hasura permissions
* [Hasura Segment Source](https://github.com/aaronhayes/hasura-segment-source) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2019-12-20 - The easiest way to connect Hasura and Segment!
* [xsura](https://github.com/joaom182/xsura) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2021-09-15 Migrate data smoothly between two Hasura servers
* [Hasura Change Summary](https://github.com/marketplace/actions/hasura-change-summary) - GitHub Action to generate readable Hasura metadata change summaries.

## Built with Hasura

* [MLCraft](https://github.com/mlcraft-io/mlcraft) ⭐ 624 | 🐛 9 | 🌐 JavaScript | 📅 2025-02-07 Low-code metrics store and an Open Source alternative to Looker
* [Pet finder project with Flutter + Firebase + Hasura](https://github.com/comerc/pet_finder) ⭐ 67 | 🐛 1 | 🌐 Dart | 📅 2023-12-17 Pet finder project with Flutter + Firebase + Hasura

## Tutorials

* [Learn](https://learn.hasura.io)
* [Production Checklist](https://docs.hasura.io/1.0/graphql/manual/deployment/production-checklist.html)
* [Lucky Hasura Docker](https://github.com/KCErb/lucky-hasura-docker) ⭐ 15 | 🐛 0 | 🌐 Shell | 📅 2020-10-10 - Guide / Tutorial / Boilerplate for using [Lucky](https://luckyframework.org/) for business logic and Hasura for GraphQL in Docker. Includes production-ready monitoring and automatic deployment / DB management.

## Templates and Examples

* [Hasura Community](https://github.com/hasura/graphql-engine/tree/master/community) ⭐ 32,107 | 🐛 2,374 | 🌐 TypeScript | 📅 2026-08-19 - Community Contributed boilerplates, example apps, and todos.
* [Rust Hasura](https://github.com/ronanyeah/rust-hasura) ⭐ 141 | 🐛 0 | 🌐 Rust | 📅 2022-04-19 - Boilerplate/example of using Rust as a Remote Schema. It features login, signup, JWT, hashed passwords and typesafe requests.
* [NextJS - Auth0 - Hasura](https://github.com/vgrafe/nextjs-auth0-hasura) ⚠️ Archived - Template project with NextJs, Auth0, Hasura and Apollo.
* [Hasura Starter](https://github.com/jjangga0214/hasura-starter) ⭐ 51 | 🐛 0 | 🌐 PLpgSQL | 📅 2020-02-22 - A boilerplate, cheatsheet, and guide for beginners.
* [hasura-node-monolith-example](https://github.com/zenflow/hasura-node-monolith-example) ⭐ 30 | 🐛 6 | 🌐 TypeScript | 📅 2023-03-04 - Example of a monolithic web application using Hasura GraphQL Engine + Node.js + Next.js
* [Pulumi AWS EKS Deployment Sample](https://github.com/aaronhayes/pulumi-hasura-aws-eks-example) ⭐ 19 | 🐛 8 | 🌐 TypeScript | 📅 2022-06-25 - A guide for deploying Hasura to AWS EKS using [Pulumi](https://www.pulumi.com/).
* [Hasura Super App](https://hasura.io/reference-app/) - The official full-featured Hasura reference app using Next.js, TypeScript, Apollo Client.

## Managed Services

* [Nhost](https://nhost.io/) - Open Source Firebase Alternative with GraphQL. Includes: Hasura, Postgres, Authentication, Storage, Serverless Functions.
* [Hasura Cloud](https://hasura.io/cloud) - Fully managed, production ready GraphQL API as a service to help you build modern apps faster. Get started in 30 seconds!

## Blogs

* [Migrating from Firebase to Hasura](https://medium.com/@clapie.florent/how-i-scale-firebase-by-migrating-to-graphql-and-speed-up-my-development-by-10x-200b4a3068a0?sk=cf4a748bfa93d061ad84fd194d5e87bb)
* [Resetting Hasura Migrations](https://blog.hasura.io/resetting-hasura-migrations/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-30._
