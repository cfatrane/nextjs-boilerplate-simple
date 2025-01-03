# Boilerplate Next Js (Simple) 14 + Eslint + Prettier + Tailwind

## Features 🛠️

- [**Husky** 🐶](https://typicode.github.io/husky/) : Automatically lint your commit messages, code, and run tests upon committing or pushing.
- [**ESlint**](https://eslint.org/) : Statically analyzes your code to quickly find problems. It is built into most text editors and you can run ESLint as part of your continuous integration pipeline.
- [**Prettier**](https://prettier.io/) : An opinionated code formatter. It enforces a consistent style by parsing your code and re-printing it with its own rules that take **the** maximum line length into account, wrapping code when necessary.
- [**Tailwind**](https://tailwindcss.com/) : A utility-first CSS framework that streamlines web development by providing a set of pre-designed utility classes.
- [**VSCode**](https://marketplace.visualstudio.com/vscode) : Configuration file and recommended extensions

## Suggestions ☝️

### Components

- [shadcn](https://ui.shadcn.com/)
- [MUI](https://mui.com/core/)
- [Next UI](https://nextui.org/)
- [Ant Design](https://ant.design/)
- [Aceternity UI](https://ui.aceternity.com/)
- [Preline UI](https://preline.co/index.html)

### State Management

- [Redux + Next](https://redux-toolkit.js.org/usage/nextjs)
- [Recoil](https://recoiljs.org/)
- [Zustand](https://github.com/pmndrs/zustand)

### Validation

- [Joi](https://joi.dev/)
- [Yup](https://github.com/jquense/yup)
- [Zod](https://zod.dev/)

### Internationalization

> [Next Js Documentation](https://nextjs.org/docs/pages/building-your-application/routing/internationalization)

- [next-int](https://next-intl.dev/)
- [react-intl](https://formatjs.github.io/)
- [react-i18next](https://react.i18next.com/)

## Getting Started 🤔

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

### Scripts

```bash
dev: "next dev",
build: "next build",
start "next start",
lint "next lint",
lint:fix "next lint --fix",
prepare "husky install",
```

## VSCode Extensions 💻

### [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)

The Better Comments extension will help you create more human-friendly comments in your code.
With this extension, you will be able to categorize your annotations into:

- Alerts
- Queries
- TODOs
- Highlights
- Commented out code can also be styled to make it clear the code shouldn't be there
- Any other comment styles you'd like can be specified in the settings

### [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)

Tailwind CSS IntelliSense enhances the Tailwind development experience by providing Visual Studio Code users with advanced features such as autocomplete, syntax highlighting, and linting.

### [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

Integrates ESLint into VS Code. If you are new to ESLint check the documentation.

The extension uses the ESLint library installed in the opened workspace folder. If the folder doesn't provide one the extension looks for a global install version. If you haven't installed ESLint either locally or globally do so by running npm install eslint in the workspace folder for a local install or `npm install -g eslint` for a global install.

On new folders you might also need to create an .eslintrc configuration file. You can do this by either using the VS Code command Create ESLint configuration or by running the eslint command in a terminal with `npx eslint --init`.

### [i18n Ally](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode)

General Features

- Supports multi-root workspaces
- Supports remote development
- Supports numerous popular frameworks
- Supports linked locale messages
- Uses i18n for the extension itself, of course. Translation List

### [SonarLint](https://marketplace.visualstudio.com/items?itemName=Lokalise.i18n-ally)

SonarLint by Sonar is a free IDE extension that empowers you to fix coding issues before they exist. More than a linter, SonarLint detects and highlights issues that can lead to bugs, vulnerabilities, and code smells as you create your code. It offers clear remediation guidance and educational help, so you can fix issues before the code is committed. SonarLint in VS Code supports analysis of JS/TS, Python, PHP, Java, C, C++, C#, Go, and IaC code locally in your IDE.

### [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)

ErrorLens turbo-charges language diagnostic features by making diagnostics stand out more prominently, highlighting the entire line wherever a diagnostic is generated by the language and also prints the message inline.

## Learn More 🧠

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
