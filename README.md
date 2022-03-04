# Microfrontend generator

This is a yeoman generator to be used inside of the Customer Portal project. It was made to assist developers to create components, use cases, stores and new microfrontends.

This generator works in linux, mac and windows.

## Setup

```bash
npm install -g yo
git clone https://github.com/lcoalves/generator-customer-portal.git
cd generator-customer-portal && yarn install && yarn link
```

## How to

### Create a new microfontend

Generates a new microfrontend with several defaults to ensure the single-spa contract and the project architecture are being followed.

The folder created contains a `.yo-rc` file. All of the other commands must be run inside of this generated folder.

```bash
yo customer-portal:mfe
```

### Create a new component

Generates a new component that abide to the project standards.

```bash
yo customer-portal:component
```

Dependending on the component type (reusable, page or page-specific), it creates the right files on the right folders.
