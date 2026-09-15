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
