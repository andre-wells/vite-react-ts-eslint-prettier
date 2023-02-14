# vite-react-ts-eslint-prettier

Project template with Vite, React JS, TypeScript, Eslint, Prettier

## Method

Below are the steps of setting up the project manually. These steps are documented to faciliate updating the template in the future.

### Create Vite React Application

```bash
yarn create vite
```

Follow the prompts

```bash
npx: installed 1 in 1.384s
√ Project name: ... vite-react-ts-eslint-prettier
√ Select a framework: » React
√ Select a variant: » TypeScript + SWC
```

### Add ESLint to project

Details available in this [blog post](https://dev.to/knowankit/setup-eslint-and-prettier-in-react-app-357b)

```bash
yarn add eslint --dev
yarn run eslint --init
```

Configure settings using the prompts.

```bash
yarn run v1.22.19
$ /home/andrew/100days/MeterReadr/web/node_modules/.bin/eslint --init
You can also run this command directly using 'npm init @eslint/config'.
✔ How would you like to use ESLint? · style
✔ What type of modules does your project use? · esm
✔ Which framework does your project use? · react
✔ Does your project use TypeScript? · No / Yes
✔ Where does your code run? · browser
✔ How would you like to define a style for your project? · guide
✔ Which style guide do you want to follow? · standard-with-typescript
✔ What format do you want your config file to be in? · JavaScript
Checking peerDependencies of eslint-config-standard-with-typescript@latest
The config that youve selected requires the following dependencies:

eslint-plugin-react@latest eslint-config-standard-with-typescript@latest @typescript-eslint/eslint-plugin@^5.0.0 eslint@^8.0.1 eslint-plugin-import@^2.25.2 eslint-plugin-n@^15.0.0 eslint-plugin-promise@^6.0.0 typescript@*
✔ Would you like to install them now? · No / Yes
✔ Which package manager do you want to use? · yarn
```

## Update Vite to use ESLint

Follow the instructions in [this blog](https://www.robinwieruch.de/vite-eslint/)
