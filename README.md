This is a starter [Next.js](https://nextjs.org/) template project.

- Next.js
- React
- Tailwind CSS
- Typescript
- ESLint (code quality) + Prettier (code formatting)

## Philosophy

This is an opinionated template that jump starts a project with all you need. Next.js with React and Typescript for JavaScript. Tailwind for styling already with an utility for fixing className props. There are also a handful of ESLint rules turned on (some recommended by ESLint, some recommended by Typescript ESLint and some selected by me for import sorting, code style I prefer and so on).

## Getting Started

Install the packages

```bash
npm install

```

Open the project in VScode and install the required extensions

- ESLint
- Prettier - Code formatter
- Tailwind CSS IntelliSense

To help with faster development, some other extensions are recommended

- ES7+React/Redux/React-Native snippets
- Turbo Console Log

Some VScode settings that should be enabled

```
"css.lint.unknownAtRules": "ignore",
"editor.defaultFormatter": "esbenp.prettier-vscode",
"editor.codeActionsOnSave": {
    "source.fixAll": true
},
"editor.formatOnSave": true,
```

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Installed packages explanation

- `eslint-config-next` - Default Nextjs ESLint config from Next.js
- `eslint-config-prettier` - Disable ESLint rules that exist on prettier
- `eslint-plugin-simple-import-sort` - ESLint plugin for sorting imports and exports
- `prettier` - Code formatting. All the default rules are present and some changed
- `prettier-plugin-tailwindcss` - Sort Tailwind classes automatically
- `eslint-plugin-simple-import-sort` - Automatically sort file imports
- `tailwind-merge and clsx` - Fix issues with classNames props

## Learn More

To learn more about the used stack:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [React Official Site](https://react.dev/) - learn about React
- [Typescript Documentation](https://www.typescriptlang.org/) - learn about Typescript
- [Tailwind CSS Documentation](https://tailwindcss.com/docs/installation) - learn about Tailwind CSS
- [ESLint Documentation](https://eslint.org/docs/head/) - learn about ESLint, its configuration and rules
- [Prettier Official Site](https://prettier.io/) - learn about Prettier and its opinionated code formatting rules

## Get in contact

All feedback is appreciated. Please contact me for any opinion, suggestion or discussions about this repo. You are welcome to fork, PR or use this repo for your convenience.
