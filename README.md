## Lexical.cloud Data Generator

This repo generates json data from [Lexical.cloud data](https://github.com/lexical-cloud/lexical-cloud-docs/) based on the [Docsy theme](https://www.docsy.dev) for [Hugo](https://gohugo.io). The docsy theme, target content and generated site are distinct submodules of this project.

### Setup Env

It's easiest to launch the dev container for this project on GitHub Codespaces.

**OR**, follow the setup instructions below.

Install Prerequisite tools:

  * [Install Hugo](https://gohugo.io/getting-started/installing/)
  * [Check Docsy Prereqs](https://www.docsy.dev/docs/get-started/docsy-as-module/installation-prerequisites/)

#### Setup Project

Clone repository:
```
git clone <url-here>
cd ${PROJECT_DIR}
```

Then:
```
make setup
```

### Start Using

Run local server:
```
make run
```	

Generate static site:
```
make build
```

---

### Contributing

Most changes for the Lexical.cloud project will occur against the [lexical-cloud-docs](https://github.com/lexical-cloud/lexical-cloud-docs) repo.
Afterwards, those data contributions will be incorporated into this repository for rendering.

Customizations to that rendering require:
 * Fork this repository
 * Launch project in Github Codespaces (optional)
 * Create new branch from main
 * Checkout branch and make desired changes

Preview and test within Github Codespaces.

Contribute back changes:
 * Commit and push desired changes to branch on fork.
 * Send a pull request back to this repository.
 * Work with project admins on the PR process.

---

### License Summary

A CC BY-SA 4.0 license is intended for the content produced from this repo. See the [LICENSE](LICENSE) file. 

The Apache 2.0 license and relevant notices for the Docsy theme are also found in this repo. See [LICENSE-DOCY](LICENSE-DOCSY) and [NOTICES-DOCSY](NOTICES-DOCSY) files.

Each submodule of this repo has a license file included. See the LICENSE file in each repo. 
