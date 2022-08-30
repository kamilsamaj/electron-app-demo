# electron-app-demo

Simple Electron app used to demonstrate the packaging for various operating systems.

## Packaging

This application uses the fancy `electron-forge` utility to package for a given operating system.
Please note that packaging for a different platform is possibly but difficult - it's better to do
it natively, for example through the GitHub Flows, etc.

To create a package for your OS and architecture, run:

```shell
npm run make
```

https://www.electronjs.org/docs/latest/tutorial/tutorial-packaging
