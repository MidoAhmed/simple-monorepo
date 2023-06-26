## instalation

1. npm i
2. npm run watch
   modify any ts source file in any workspace under packages the changes are reflected

```js
.
├── README.md
├── package-lock.json
├── package.json
├── packages
│   ├── app
│   │   ├── package.json
│   │   ├── src
│   │   │   └── main.ts
│   │   ├── tsconfig.json
│   │   └── tsconfig.ref.json
│   └── core
│       ├── package.json
│       ├── src
│       │   └── index.ts
│       ├── tsconfig.json
│       └── tsconfig.ref.json
└── tsconfig.json
```

## Resources

1. https://2ality.com/2021/07/simple-monorepos.html
