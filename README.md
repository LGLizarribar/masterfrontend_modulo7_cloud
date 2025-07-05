# CLOUD EXERCISE 1

Cloud exercise consisting on the manual deployment of an app on Github pages

## Steps

### 1. Create a github repository

### 2. Add build and prebuild commands

### 3. Change vite.config.js file so it has base route as './'

### 4. Change router.ts so it creates a Hash history and add the history to the router

### 5. Build the project

```sh
npm run build
```

### 6. Checkout to a new "gh-pages" branch

```sh
git chekout -b "gh-pages"
```

### 7. Remove all files but the ones inside dist folder and extract them to the root path

### 8. Push the changes to the new branch

# CLOUD EXERCISE 2

Automate previous process with github actions so the build and deployment trigger on every merge to main branch

## Steps

### 1. Install gh-pages

```sh
npm install gh-pages --save-dev
```

### 2. Add prebuild and build commands in dev environment, add deploy command

### 3. Create ssh private key

### 4. Add created private key to Deploy Keys and actions secrets in github

### 5. Create workflow file with ssh key permits
