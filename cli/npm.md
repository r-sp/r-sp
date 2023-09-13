# npm

npm is the package manager for the Node JavaScript platform. It puts modules in place so that node can find them, and manages dependency conflicts intelligently.

It is extremely configurable to support a wide variety of use cases. Most commonly, it is used to publish, discover, install, and develop node programs.

Run `npm help` to get a list of available commands.

- [CLI Commands](https://docs.npmjs.com/cli/v9/commands)
- [Configuring npm](https://docs.npmjs.com/cli/v9/configuring-npm)
- [Using npm](https://docs.npmjs.com/cli/v9/using-npm)

---

## Commands

```sh
npm install
npm install --production
npm install --save-dev typescript
npm install --save-exact typescript

npm update
npm update --dev
npm update -g
npm update typescript

npm remove typescript
npm run index.ts
npx create-react-app my-app

npm list
npm list -g --depth 0
npm view
npm outdated
```
