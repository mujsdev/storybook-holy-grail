# The Storybook Holy Grail
Note:  In case you're new to Storybook. [Learn more here](https://storybook.js.org/)


<br />

## **Repo contents**
---
This repo consists of the following so far:
1. Style guide
   * Colors
   * Typography
   * Icons
   * Box shadows
   * Border radii
   * Spacings
2. Components
   * Button

<br />

## **Getting started**
---
It only takes two (commands) to tango!

`yarn install`

`yarn storybook`

<br />

## **Initial project setup**
---
In case you're curious what commands were used to set up this project.

<br />

`yarn init -y`

Pretty self explanatory tbh (initializes the `package.json` file)

<br />

`yarn add -D react react-dom`

Installs the react and react-dom dependencies

<br />

`yarn add -D typescript @types/react`

Adds Typescript to the project. You know the vibes

<br /> 

`tsc --init`

Initializes the tsconfig.json

<br />

### **Adding SCSS and Tailwind CSS to your project**
---

`npx sb init --builder webpack5`

If you're not planning to use Sass in your project then  `npx sb init` works too. 

<br />

`yarn add -D sass style-loader css-loader sass-loader`

Adding Sass to the project

<br />

`yarn add -D tailwindcss postcss autoprefixer`

Adding Tailwind CSS to the project

<br />

`yarn add -D @storybook/addon-postcss`

Adding an addon for PostCSS for Tailwind CSS

<br />

### **Adding Fontawesome Icons**
---

`yarn add @fortawesome/fontawesome-svg-core`

<br />

Free icon styles (you can add either one or both)

`yarn add @fortawesome/free-solid-svg-icons`

`yarn add @fortawesome/free-regular-svg-icons`
