---
description: Create Next.js apps in one command with create-next-app.
title: Create Next App
---

# Create Next App

The easiest way to get started with Next.js is by using `create-next-app`. This CLI tool enables you to quickly start building a new Next.js application, with everything set up for you. You can create a new app using the default Next.js template, or by using one of the [official Next.js examples](https://github.com/vercel/next.js/tree/canary/examples). To get started, use the following command:

```bash
npx create-next-app@latest
# or
yarn create next-app
# or
pnpm create next-app
```

You can create a [TypeScript project](https://github.com/vercel/next.js/blob/canary/docs/basic-features/typescript.md) with the `--ts, --typescript` flag:

```bash
npx create-next-app@latest --ts
# or
yarn create next-app --typescript
# or
pnpm create next-app --ts
```

### Options

`create-next-app` comes with the following options:

- **--ts, --typescript** - Initialize as a TypeScript project.
- **-e, --example [name]|[github-url]** - An example to bootstrap the app with. You can use an example name from the [Next.js repo](https://github.com/vercel/next.js/tree/canary/examples) or a GitHub URL. The URL can use any branch and/or subdirectory.
- **--example-path [path-to-example]** - In a rare case, your GitHub URL might contain a branch name with a slash (e.g. bug/fix-1) and the path to the example (e.g. foo/bar). In this case, you must specify the path to the example separately: `--example-path foo/bar`
- **--use-npm** - Explicitly tell the CLI to bootstrap the app using npm
- **--use-pnpm** - Explicitly tell the CLI to bootstrap the app using pnpm

Note: To bootstrap using `yarn` we recommend running `yarn create next-app`

### Why use Create Next App?

`create-next-app` allows you to create a new Next.js app within seconds. It is officially maintained by the creators of Next.js, and includes a number of benefits:

- **Interactive Experience**: Running `npx create-next-app@latest` (with no arguments) launches an interactive experience that guides you through setting up a project.
- **Zero Dependencies**: Initializing a project is as quick as one second. Create Next App has zero dependencies.
- **Offline Support**: Create Next App will automatically detect if you're offline and bootstrap your project using your local package cache.
- **Support for Examples**: Create Next App can bootstrap your application using an example from the Next.js examples collection (e.g. `npx create-next-app --example api-routes`).
- **Tested**: The package is part of the Next.js monorepo and tested using the same integration test suite as Next.js itself, ensuring it works as expected with every release.

## Related

For more information on what to do next, we recommend the following sections:

<div class="card">
  <a href="/docs/basic-features/pages.md">
    <b>Pages:</b>
    <small>Learn more about what pages are in Next.js.</small>
  </a>
</div>

<div class="card">
  <a href="/docs/basic-features/built-in-css-support.md">
    <b>CSS Support:</b>
    <small>Use the built-in CSS support to add custom styles to your app.</small>
  </a>
</div>

<div class="card">
  <a href="/docs/api-reference/cli.md">
    <b>CLI:</b>
    <small>Learn more about the Next.js CLI.</small>
  </a>
</div>