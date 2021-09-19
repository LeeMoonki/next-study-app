# next-study-app

The project is for studying next.js. Hence this project should be placed next by the next.js project.

## rough process
1. developing in `next.js/packages/next`
2. run `yarn pre` or `yarn prepublish` in this project or `next.js/packages/next`
3. run `yarn cn` to reinstall the local next
4. run `yarn build` to use the local next for building
5. the `yarn build:trace-console` build with console tracing

## etc
- In some reason, I could not import the new directory in build.ts. The answer of this issue from vercel is clearing the yarn cache. But it did not work. So I temporarily insert studying code in exist direcories.
