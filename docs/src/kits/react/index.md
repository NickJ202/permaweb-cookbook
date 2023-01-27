# React Starter Kits

React is a popular library used for building user interfaces. Alongside other popular 
tools such as create-react-app, a React project can be compiled into a bundle. This bundle
can be uploaded as a transaction to the permaweb where it will serve as a single page application.

React Starter Kit Guides:

* [Vite](./vite.md) - Utilize Vite to build a React permaweb app
* [Create React App](./create-react-app.md) - Utilize Create React App to build a React permaweb app

Components:

* [Wallet Provider](./wallet-provider.md) - Wrap a React permaweb app in an Arweave Wallet Provider, see [repository](https://github.com/NickJ202/arweave-wallet-adapter) for source code and examples


::: info Permaweb Application Constraints
* 100% Front-end application (No Server-Side Backend)
* Applications are served from a sub-path (https://[gateway]/[TX_ID])
:::
