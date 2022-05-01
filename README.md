
## Create the Svelte project

```
npm init svelte skd-cards-dev
```
Adding:

- Typescript
- ESLint
- Prettier

## Add and install latest Tailwindcss
```
npx svelte-add@latest tailwindcss

npm install
```
## Install Daisy UI

```
npm install daisyui
```

Add Daisy UI to Tailwindcss: `tailwind.config.cjs`

```
plugins: [require('daisyui')]
```
