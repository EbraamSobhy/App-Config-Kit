# Variables
APP_NAME=<project-name>
PACKAGE_MANAGER=npm

# Default target
.DEFAULT_GOAL := help

# Install dependencies
i:
	$(PACKAGE_MANAGER) install

# Start development server
d:
	$(PACKAGE_MANAGER) run dev

# Build production files
b:
	$(PACKAGE_MANAGER) run build

# Preview production build
p:
	$(PACKAGE_MANAGER) run preview

# Run lint
l:
	$(PACKAGE_MANAGER) run lint

# Run tests (if configured)
t:
	$(PACKAGE_MANAGER) run test

# Clean node_modules and build output
c:
	rm -rf node_modules dist

# Reinstall everything
r: clean install

# Create production build and serve preview
s: build preview

# Help menu
help:
	@echo "Available commands:"
	@echo "  make i        - Install dependencies"
	@echo "  make d        - Start Vite dev server"
	@echo "  make b        - Build for production"
	@echo "  make p        - Preview production build"
	@echo "  make l        - Run linter"
	@echo "  make t        - Run tests"
	@echo "  make c        - Remove node_modules and dist"
	@echo "  make r        - Clean and reinstall dependencies"
	@echo "  make s        - Build and preview app"
