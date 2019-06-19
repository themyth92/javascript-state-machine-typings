## JS State Machine Typing
- [Javascript State Machine](https://github.com/jakesgordon/javascript-state-machine) Typing
- Copy from https://github.com/taoqf/javascript-state-machine with some small modification.

## Command
- `npm install @ts-typings/javascript-state-machine`
- Include custom types in your tsconfig. I.e:

```
"compilerOptions": {
  ...
  "baseUrl": "./",
  "paths": {
    "*": ["node_modules/@ts-typings/*"]
  }
}
```
