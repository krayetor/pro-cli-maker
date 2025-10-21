# Project CLI Maker 

A simple command-line tool to quickly scaffold a new web project. It creates a new folder and populates it with `.gitignore file`,`index.html`, `style.css` and `script.js`.

## Usage

First, install the tool globally from npm:

```bash
npm install -g @krayetor/project-cli-maker
```

Then, run the command from any folder:

```bash
create-project <project-name>
```

Example

```bash
create-project my-new-website
```

This will create the following folder structure:

```bash
my-new-wwebite/
├── .gitignore
├── index.html
├── style.css
└── script.js
```