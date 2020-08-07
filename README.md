# 1

yarn add tailwindcss postcss-cli autoprefixer -D

#

npx tailwind init --full

```
# postcss.config.js
module.exports = {
    plugins: [
        require('tailwindcss'),
        require('autoprefixer')
    ],
};
```

package.json
"b:css": "postcss src/styles/tailwind.css -o src/styles/main.css",


stylelint.config.js

