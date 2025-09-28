# Website

1. Clone repo
2. Run npm install
3. Run npm update
4. Run npm audit fix --force

Works locally with
```
node node_modules/pug-cli/index.js views/ --out ./ && nodemon server-local.js
```
On Netlify, in deploy settings, use the build command
```
npm install && npm audit fix --force && npm run build && node node_modules/pug-cli/index.js views/ --out ./
```
 
