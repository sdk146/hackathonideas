<br/>

<div align="center" style="margin: 30px;">
<a href="https://refine.dev/">
<picture  style="display: inline-block;" >
  <source media="(prefers-color-scheme: dark)" srcset="https://refine.ams3.cdn.digitaloceanspaces.com/readme/refine-white-logo.png">
  <img alt="refine logo" src="https://refine.ams3.cdn.digitaloceanspaces.com/readme/refine-dark-logo.png">
</picture>

<br />
<br />
</a>

<div align="center">
    <a href="https://refine.dev">Home Page</a> |
    <a href="https://discord.gg/refine">Discord</a> |
    <a href="https://refine.dev/examples/">Examples</a> |
    <a href="https://refine.dev/blog/">Blog</a> |
    <a href="https://refine.dev/docs/">Documentation</a>
</div>
</div>

<br />

<div align="center"><strong>Build your <a href="https://reactjs.org/">React</a>-based CRUD applications, without constraints.</strong><br>An open-source, headless web application framework developed with flexibility in mind.

<br />
<br />

[![Discord](https://img.shields.io/discord/837692625737613362.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/refine)
[![Twitter Follow](https://img.shields.io/twitter/follow/refine_dev?style=social)](https://twitter.com/refine_dev)

<a href="https://www.producthunt.com/posts/refine-3?utm_source=badge-top-post-badge&utm_medium=badge&utm_souce=badge-refine&#0045;3" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/top-post-badge.svg?post_id=362220&theme=light&period=daily" alt="refine - 100&#0037;&#0032;open&#0032;source&#0032;React&#0032;framework&#0032;to&#0032;build&#0032;web&#0032;apps&#0032;3x&#0032;faster | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

</div>

<div align="center">

[![Awesome](https://github.com/refinedev/awesome-refine/raw/main/images/badge.svg)](https://github.com/refinedev/awesome-refine)
[![Maintainability](https://api.codeclimate.com/v1/badges/99a65a191bdd26f4601c/maintainability)](https://codeclimate.com/github/pankod/refine/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/99a65a191bdd26f4601c/test_coverage)](https://codeclimate.com/github/pankod/refine/test_coverage)
[![npm version](https://img.shields.io/npm/v/@refinedev/core.svg)](https://www.npmjs.com/package/@refinedev/core)
[![](https://img.shields.io/github/commit-activity/m/refinedev/refine)](https://github.com/refinedev/refine/commits/master)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.0-4baaaa.svg)](CODE_OF_CONDUCT.md)

</div>

<br/>

[![how-refine-works](https://refine.ams3.cdn.digitaloceanspaces.com/website/static/img/diagram.jpg)](https://refine.dev)

## What is refine?

**refine** is a meta **React** framework that enables the rapid✨ development of a wide range of web applications.

From internal tools to admin panels, B2B apps, and dashboards, it serves as a comprehensive solution for building any type of **CRUD** application.

refine's internal hooks and components simplify the development process and eliminate repetitive tasks by providing industry-standard solutions for crucial aspects of a project, including **authentication**, **access control**, **routing**, **networking**, **state management**, and **i18n**.

**refine** is _headless by design_, thereby offering unlimited styling and customization options.

## What do you mean by "headless" ?

Instead of being limited to a set of pre-styled components, **refine** provides collections of helper `hooks`, `components`, `providers`, and more. Since business logic and the UI are completely decoupled, you can customize the UI without constraints.

It means that **refine** just works _seamlessly_ with any _custom designs_ or _UI frameworks_. Thanks to it's headless architecture, you can use popular CSS frameworks like [TailwindCSS](https://tailwindcss.com/) or even create your own styles from scratch.

refine also provides integrations with [Ant Design](https://ant.design/), [Material UI](https://mui.com/material-ui/getting-started/overview/), [Mantine](https://mantine.dev/), and [Chakra UI](https://chakra-ui.com/) to get you started quickly. These libraries are a set of components that are nicely integrated with the headless `@refinedev/core` package.

### Headless in Routing

For the routing, refine's headless approach shines too. It doesn't tie you to a single routing method or library. Instead, it offers a simple routing interface with built-in integrations for popular libraries.

This means you can use refine seamlessly on different platforms like React Native, Electron, Next.js, Remix, etc. without any extra setup steps.

## 🔥 Try refine

refine's [browser-based app scaffolder](https://refine.dev/#playground) lets you create refine app by making step-by-step selections directly in your browser

You can choose the libraries and frameworks you want to work with, and the tool will generate a downloadable boilerplate code for you.

This allows you to preview, modify, and download the project immediately, thereby streamlining the development process.

<br/>

<div align="center">
<a href="https://refine.dev/#playground" target="_blank">
<img src="https://refine.ams3.cdn.digitaloceanspaces.com/blog/2023-07-25-refine-primereact/create-refine-project.gif"    />
</a>
</div>

## Use cases

**refine** shines on _data-intensive⚡_ applications like **admin panels**, **dashboards** and **internal tools**. Thanks to the built-in **SSR support**, **refine** can also power _customer-facing_ applications like **storefronts**.

You can take a look at some live examples that can be built using **refine** from scratch:

-   [Fully-functional CRM Application](https://example.crm.refine.dev/)
-   [Fully-functional Admin Panel](https://s.refine.dev/readme-admin-panel)
-   [Win95 Style Admin panel 🪟](https://win95.refine.dev/)
-   [Medium Clone - Real World Example](https://s.refine.dev/readme-medium-clone)
-   [Multitenancy Example](https://multi-tenancy-strapi.refine.dev/)
-   [Storefront](https://s.refine.dev/readme-ssr-storefront)

[👉 Refer to most popular real use case examples](https://refine.dev/docs/examples/)

[👉 More **refine** powered different usage scenarios can be found here](https://refine.dev/docs/examples#other-examples)

## Key Features

⚙️ Zero-config, **one-minute setup** with a **single CLI command**

🔌 Connectors for **15+ backend services** including [REST API](https://github.com/refinedev/refine/tree/master/packages/simple-rest), [GraphQL](https://github.com/refinedev/refine/tree/master/packages/graphql), [NestJs CRUD](https://github.com/refinedev/refine/tree/master/packages/nestjsx-crud), [Airtable](https://github.com/refinedev/refine/tree/master/packages/airtable), [Strapi](https://github.com/refinedev/refine/tree/master/packages/strapi), [Strapi v4](https://github.com/refinedev/refine/tree/master/packages/strapi-v4), [Strapi GraphQL](https://github.com/refinedev/refine/tree/master/packages/strapi-graphql), [Supabase](https://github.com/refinedev/refine/tree/master/packages/supabase), [Hasura](https://github.com/refinedev/refine/tree/master/packages/hasura), [Appwrite](https://github.com/refinedev/refine/tree/master/packages/appwrite), [Nestjs-Query](https://github.com/refinedev/refine/tree/master/packages/nestjs-query), [Firebase](https://firebase.google.com/), and [Directus](https://directus.io/).

🌐 **SSR support** with **Next.js** or **Remix**

🔍 Auto-generated **CRUD** UIs from **your API data structure**

⚛ Perfect **state management** & **mutations** with **React Query**

🔀 **Advanced routing** with any router library of your choice

🔐 Providers for seamless **authentication** and **access control** flows

⚡ Out-of-the-box support for **live / real-time applications**

📄 Easy **audit logs** & **document versioning**

💬 Support for any **i18n** framework

💪 Future-proof, **robust architecture**

⌛️ Built-in CLI with time-saving features

💻 refine [Devtools](https://github.com/refinedev/refine/blob/master/packages/devtools/README.md) - dive deeper into your app and provide useful insights

✅ Full **test coverage**

## Quick Start

The fastest way to get started with **refine** is by using the `create refine-app` CLI tool or the [browser-based app scaffolder](https://refine.dev/#playground).

For this example, we'll use the CLI tool. Simply run the following command to create a new **refine** project configured with [Ant Design](https://ant.design/) as the default UI framework:

```
npm create refine-app@latest -- -o refine-antd
```

Once the setup is complete, navigate to the project folder and start your project with:

```
npm run dev
```

<br/>

Your **refine** application will be accessible at [http://localhost:5173](http://localhost:5173):

<a href="http://localhost:5173">![Welcome on board](https://refine.ams3.cdn.digitaloceanspaces.com/website/static/img/welcome.png)</a>

<br/>

Let's consume a public `fake REST API` and add two resources (_blog_posts_ and _categories_) to our project. Replace the contents of `src/App.tsx` with the following code:

```tsx title="src/App.tsx"
import { Refine } from "@refinedev/core";
import {
    notificationProvider,
    ErrorComponent,
    ThemedLayout,
} from "@refinedev/antd";
import routerProvider, { NavigateToResource } from "@refinedev/react-router-v6";
import dataProvider from "@refinedev/simple-rest";

import { BrowserRouter, Routes, Route, Outlet } from "react-router-dom";

import { AntdInferencer } from "@refinedev/inferencer/antd";

import "@refinedev/antd/dist/reset.css";

const App: React.FC = () => {
    return (
        <BrowserRouter>
            <Refine
                routerProvider={routerProvider}
                dataProvider={dataProvider("https://api.fake-rest.refine.dev")}
                notificationProvider={notificationProvider}
                resources={[
                    {
                        name: "blog_posts",
                        list: "/blog-posts",
                        show: "/blog-posts/show/:id",
                        create: "/blog-posts/create",
                        edit: "/blog-posts/edit/:id",
                        meta: { canDelete: true },
                    },
                    {
                        name: "categories",
                        list: "/categories",
                        show: "/categories/show/:id",
                    },
                ]}
            >
                <Routes>
                    <Route
                        element={
                            <ThemedLayout>
                                <Outlet />
                            </ThemedLayout>
                        }
                    >
                        <Route index element={<NavigateToResource />} />
                        <Route path="blog-posts">
                            <Route index element={<AntdInferencer />} />
                            <Route
                                path="show/:id"
                                element={<AntdInferencer />}
                            />
                            <Route path="create" element={<AntdInferencer />} />
                            <Route
                                path="edit/:id"
                                element={<AntdInferencer />}
                            />
                        </Route>
                        <Route path="categories">
                            <Route index element={<AntdInferencer />} />
                            <Route
                                path="show/:id"
                                element={<AntdInferencer />}
                            />
                        </Route>
                        <Route path="*" element={<ErrorComponent />} />
                    </Route>
                </Routes>
            </Refine>
        </BrowserRouter>
    );
};

export default App;
```

<br/>

🚀 Thanks to the **refine Inferencer package**, it guesses the configuration to use for the `list`, `show`, `create`, and `edit` pages based on the data fetched from the API and generates the pages automatically.

Now, you should see the output as a table populated with `blog_posts` & `category` data:

![First example result](https://refine.ams3.cdn.digitaloceanspaces.com/website/static/img/readme-quick-start-2.png)

<br/>

You can get the auto-generated page codes by clicking the `Show Code` button on each page. Afterward, simply pass the pages to the `resources` array by replacing them with the Inferencer components.

## Next Steps

👉 Jump to [Tutorial](https://refine.dev/docs/tutorial/introduction/index/) to continue your work and turn the example into a full-blown CRUD application.

👉 Visit the [Learn the Basics page](https://refine.dev/docs/getting-started/overview/) to get informed about the fundamental concepts.

👉 Read more on [Advanced Tutorials
](https://refine.dev/docs/advanced-tutorials/) for different usage scenarios.

👉 See the real-life [Finefoods Demo](https://refine.dev/demo/) project.

👉 Play with interactive [examples.](https://refine.dev/docs/examples/)

## Stargazers

[![Stargazers repo roster for refinedev/refine](https://reporoster.com/stars/refinedev/refine)](https://github.com/refinedev/refine/stargazers)

## Contribution

[👉 Refer to the contribution docs for more information.](https://refine.dev/docs/contributing/#ways-to-contribute)

If you have any doubts related to the project or want to discuss something, then join our [Discord server](https://discord.gg/refine).

## Our ♥️ Contributors

<a href="https://github.com/refinedev/refine/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=refinedev/refine" />
</a>

## License

Licensed under the MIT License, Copyright © 2021-present Refinedev
