This template provides a minimal setup to get React Native Expo working with :

- Typescript
- Nativewind
- ESLint
- Prettier
- Husky
- CommitLint

To make it work :

1. Change the project name

2. Install packages

```shell
 npm install
```

3. Link with expo

```shell
 eas init --id <your-id>
```

4. Configure the project

```shell
 eas build:configure
```

5. Build a first time

```shell
 eas build
```

5. a. Build before push for android

```shell
 npx husky add .husky/pre-push "npm run build:android"
```

5. b. build before push for ios

```shell
 npx husky add .husky/pre-push "npm run build:ios"
```
