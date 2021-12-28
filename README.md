Create Vite App
npm init @vitejs/app project-name

Install Tailwind + dependencies
npm install -D tailwindcss@latest postcss@latest autoprefixer@latest

Install ESLint + Prettier
npm install --save-dev eslint prettier eslint-plugin-vue eslint-config-prettier

Install Vue Router
npm install vue-router@4

Install Vuex
npm install vuex@next --save

.eslintrc.js:
module.exports = {
extends: [
  'plugin:vue/vue3-essential',
  'prettier',
],
rules: {
  // override/add rules settings here, such as:
  'vue/no-unused-vars': 'error',
},
}

.prettierrc.js:
module.exports = {
    semi: false,
    tabWidth: 4,
    useTabs: false,
    printWidth: 80,
    endOfLine: 'auto',
    singleQuote: true,
    trailingComma: 'es5',
    bracketSpacing: true,
    arrowParens: 'always',
  }


  https://youtu.be/O8epzPrsADI