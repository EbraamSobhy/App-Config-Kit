# Install in your new app
```bash
git clone https://github.com/EbraamSobhy/App-Config-Kit.git
```

## Get a specific module

Use [degit](https://github.com/Rich-Harris/degit) to copy a single folder without cloning the whole repo:

```bash
# CI workflow
npx degit EbraamSobhy/App-Config-Kit/.github/workflows ./github/workflows

# Build (Makefile)
npx degit EbraamSobhy/App-Config-Kit/build ./build

# Deploy (Vercel config)
npx degit EbraamSobhy/App-Config-Kit/deploy ./deploy

# Docker setup
npx degit EbraamSobhy/App-Config-Kit/docker ./docker

# Git (git commands)
npx degit EbraamSobhy/App-Config-Kit/git ./git
```

### Moving your files into your project root after you've degit'd or cloned the template into a temp folder and now want the actual files (not the container folders) sitting at root.
```bash
# Github Actions
mv .github/workflows/ci.yml .github/workflows/ci.yml   # already correct

# Build
mv build/Makefile ./Makefile

# Deploy
mv deploy/vercel.json ./vercel.json
mv deploy/vercel.md ./vercel.md

# Docker
mv docker/.dockerignore ./.dockerignore
mv docker/docker-compose.yml ./docker-compose.yml
mv docker/Dockerfile ./Dockerfile

# Git
mv git/git.sh ./git.sh
```
