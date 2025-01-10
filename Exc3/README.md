Из коробки это не собирается.

```bash
rm -rf node_modules
rm package-lock.json
npm install --legacy-peer-deps
npm run build
npm run serve
```

После этого открыть [http://localhost:3000](http://localhost:3000)


При этом, использовать `pnpm` **Нельзя**