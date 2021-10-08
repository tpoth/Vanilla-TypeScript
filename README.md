# Vanilla TypeScript Template

This project is a kickstart template to built upon your own Vanilla
TypeScript Project. All the necessary steps to get TypeScript (further
known as TS) running will be prebuild into the source tree of this
template. This includes the following features.

## Prerequisites

- node version ^14.17.5 (Created with this version, but not necesarrily a prereq)
- npm version  ^6.14.14 (Created with this version, but not necesarrily a prereq)
- typescript version ^4.3.5 (Created with this version, but not necesarrily a prereq)
- tsc version ...

## Features ...

... or should we call it a step by step guide for how to build the template
from scratch. If you follow these steps you cann create the template from the
ground up by yourself.

- `README.md`, this file. Can be used to describe your own project
- `.gitignore` with excludes for VS Code
- `npm init` to create a simple `package.json` file
- `npm install typescript --save-dev` to setup typescript as a development dependency
- Set `"tsc": "tsc"` inside the `"scripts"` node in the `package.json` file
- Run `npm run tsc -- --init` to initialize `tsconfig.json` file
- Change `"target": "ES2017"` inside the `"compilerOptions"` node in the `tsconfig.json` file
- Change `"module": "ES2020"` inside the `"compilerOptions"` node in the `tsconfig.json` file
- Uncomment `"sourceMap": true` inside the `"compilerOptions"` node in the `tsconfig.json` file
- Uncomment and Change `"outDir": "./dist"` inside the `"compilerOptions"` node in the `tsconfig.json` file
- Create an `./src` folder in the root of the project
- Create a file named `main.ts` in `./src` folder
- Put some sample code inside the `main.ts` file, find sample code in chapter `main.ts - Listing 1`
- Run `npm run tsc` to compile the code, compilation results will be written to the `./dist` folder in the root of the project

## package.json

```.gitignore
.vscode/*
!.vscode/settings.json
!.vscode/tasks.json
!.vscode/launch.json
!.vscode/extensions.json
*.code-workspace

# Local History for Visual Studio Code
.history/
```

## package.json

```json

```

## tsconfig.json

```json

```

## main.ts - Listing 1

```typescript
function add(x: number, y:number) {
    return x + y;
}
```
