# Install in your frontend app
```bash
git clone https://github.com/EbraamSobhy/Frontend-Config-Kit.git
```

## Get a specific module

Use [degit](https://github.com/Rich-Harris/degit) to copy a single folder without cloning the whole repo:

```bash
# CI workflow
npx degit yourname/Frontend-Config-Kit/.github/workflows ./github/workflows

# Build (Makefile)
npx degit yourname/Frontend-Config-Kit/build ./build

# Deploy (Vercel config)
npx degit yourname/Frontend-Config-Kit/deploy ./deploy

# Docker setup
npx degit yourname/Frontend-Config-Kit/docker ./docker

# Git helpers
npx degit yourname/Frontend-Config-Kit/git ./git

# Everything
npx degit yourname/Frontend-Config-Kit ./frontend-config-kit
```
