## Instructions

Install the dependencies
```
npm i
```

run the standard Next dev server:
```
npm run dev
```

navigate to `http://localhost:3000/api/hello` and see the hello world response

build the next-on-pages app:
```
npm run pages:build
```

and start wrangler pages dev:
```
npm run pages:dev
```

try to navigate to `http://localhost:8788/api/hello` and notice that the api route isn't getting loaded

remove the `i18n` config or rename the `[[...path]].tsx` file to `index.tsx` file to get the proper behavior