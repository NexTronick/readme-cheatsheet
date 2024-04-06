# Cheatsheet

<details>
<summary>Table of Content</summary>

- [Markdown Formatting](#markdown-formatting)
- [Git Commands](#git-commands)
- [Package Management (npm)](#package-management-npm)
- [Virtual Environment (Python)](#virtual-environment-python)
- [Docker](#docker)

</details>
:
`
<details>
<summary>Table of Content</summary>

- [Markdown Formatting](#markdown-formatting)
- [Git Commands](#git-commands)
- [Package Management (npm)](#package-management-npm)
- [Virtual Environment (Python)](#virtual-environment-python)
- [Docker](#docker)

</details>

`
## Markdown Formatting

- **Bold Text**: `**Bold Text**`
- *Italic Text*: `*Italic Text*`
- [Link](https://example.com): `[Link](https://example.com)`
- `Inline Code`: \`Inline Code\`
- ```Code Block```: \`\`\`Code Block\`\`\`

## Git Commands

- Initialize a repository: `git init`
- Clone a repository: `git clone <repository-url>`
- Add changes to the staging area: `git add <file>`
- Commit changes: `git commit -m "Commit message"`
- Push changes to a remote repository: `git push <remote> <branch>`
- Pull latest changes from a remote repository: `git pull <remote> <branch>`
- Create a new branch: `git branch <branch>`
- Switch to a branch: `git checkout <branch>`
- Merge branches: `git merge <branch>`

## Package Management (npm)

- Initialize a new project: `npm init`
- Install a package: `npm install <package>`
- Install a package as a development dependency: `npm install <package> --save-dev`
- Uninstall a package: `npm uninstall <package>`
- Update a package: `npm update <package>`
- Run a script defined in package.json: `npm run <script-name>`

## Virtual Environment (Python)

- Create a virtual environment: `python -m venv <env-name>`
- Activate a virtual environment:
  - Windows: `<env-name>\Scripts\activate.bat`
  - Unix/Mac: `source <env-name>/bin/activate`
- Deactivate a virtual environment: `deactivate`

## Docker

- Build a Docker image: `docker build -t <image-name> .`
- Run a Docker container: `docker run <image-name>`
- List all running containers: `docker ps`
- Stop a running container: `docker stop <container-id>`
- Remove a container: `docker rm <container-id>`
- List all Docker images: `docker images`
- Remove a Docker image: `docker rmi <image-name>`
