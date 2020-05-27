# Starter for React Native applications written in TypeScript

A basic Starter for React Native + TypeScript development with setup for Eslint, Prettier, Styled-components and more.

---

__👌  The follwing is setup out of the box:__
- Consistent coding styles using [EditorConfig](https://editorconfig.org/)
- Linting via [eslint](https://eslint.org/), [typescript-eslint](https://github.com/typescript-eslint/typescript-eslint) and [prettier](https://prettier.io/)
- Styles via [Styled Components](https://styled-components.com/)
- Routes via [React Navigation](https://reactnavigation.org/)

## 🚀 Getting Started

Assuming [Node.js](https://nodejs.org/en/) is installed, run the following commands to install the project:

```
$ git clone https://github.com/diogorodrigues/react-native-typescript-starter.git your-project-name

cd your-project-name

rm -rf .git
yarn install
yarn android | ios
```

Please, read the documentation to apply the [correct settings for React Navigation](https://reactnavigation.org/). It will depend on the OS you are working on.

## Main files

|  Name | Description |
| :------------ | :------------ |
| src | Contains your source code that will be compiled to the dist dir |
| src/routes | Contains your routes. |
| src/pages | Contains your pages. |
| src/components | Contains your components. |
| src/index.tsx | Entry point to your app |
| .editorconfig | EditorConfig settings |
| .eslintrc.json | Eslint Settings |
| prettier.config.js | Prettier settings |
