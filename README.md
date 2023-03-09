# railwelding-design
Design for railwelding

### Creating steps:

```bash
npm init -y
npm install -D tailwindcss
npx tailwindcss init
```


```bash
mkdir src
touch src/input.css
```

add to package.json:

```javascript
"scripts": {
  "start": "npx tailwindcss -i ./src/input.css -o ./css/main.css --watch"
},
```

Live Server for VSCode:
```bash
ext install ritwickdey.LiveServer
```

```bash
npm run start
```