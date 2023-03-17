# Waimanu - Clean Shopify theme

### Before start checklist for Windows users:
- [ ] [Node.js](https://nodejs.org/en/download/) 14.17.0 or higher
- [ ] [Ruby+Devkit 3.0](https://rubyinstaller.org/downloads/), installed using RubyInstaller for Windows
(select the MSYS2 component and the MSYS2 base installation option)
- [ ] [Git](https://git-scm.com/downloads)
- [ ] [Bundler](https://bundler.io/) 2.3.8 or higher

### Installing Shopify CLI
To install Shopify CLI for themes, install the `@shopify/cli` and `@shopify/theme` Node.js packages globally using the command line.\
`npm install -g @shopify/cli @shopify/theme`


To verify that Shopify CLI is installed properly, run the following command:\
`shopify version`

### Installing theme on local machine
Run the following command to clone a Git repository to your local machine to use as the starting point for building a theme:\
`shopify theme init [name] --clone-url [repository]`\

`name` - The name that you want to give your theme. Cloned files are stored in a folder with this name.\
`repository` - Repository URL.
