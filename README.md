# Data Structure and Algorithms - TypeScript [![Build & Test](https://github.com/AliSawari/js-data-structure/actions/workflows/node.js.yml/badge.svg)](https://github.com/AliSawari/js-data-structure/actions/workflows/node.js.yml)

**Implemented most useful and important Data Structures used in Software Development, All With TypeScript 🌟** 

## Table of Contents
- [Introduction](#data-structure-with-typeScript)
- [Examples](#examples)


## List of Implemented Data Structures 
- [x] Linked Lists
- [ ] Stacks
- [ ] Queues
- [ ] Trees



## Data Structure with TypeScript

the benefits of using the Type system from TypeScript is the ability to create new types alongside the class
definitions, which allows you to implement the Data Structure types easily and correctly.

I've tried to be as close as possible to the real use cases of Data Structures in Real life and 
in the classic definitions.

## Examples

here's a quick type definition of Linked List. 

```ts

type LinkedListType = {
  length: number
  head: NodeType | null
  tail: NodeType | null
  push?(value:any): LinkedListType
  pop?(): NodeType | unknown
  shift?(): NodeType | unknown
  unshift?(value:any): LinkedListType
  get?(index:number): NodeType | unknown
  set?(index: number, value:any): boolean
  insert?(index: number, value:any): void
  remove?(value:any): NodeType | unknown
  reverse?(): void
  log?(): void
}

```

you can see that each property or method has a declared type. the `value` of a linked list however can be different, thats why `any` would make sense. A Generic type will be implemented soon.

### Run 

build
```bash
npm run build
```

Run
```bash
npm start
```


### Testing

