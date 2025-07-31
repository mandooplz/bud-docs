---
sidebar_position: 1
---

# Introduction to TypeScript

TypeScript is a strongly typed programming language that builds on JavaScript, giving you better tooling at any scale. It adds optional types to JavaScript that support tools for large-scale JavaScript applications for any browser, for any host, on any OS. TypeScript compiles to plain JavaScript.

## Basic Syntax

Here is a simple "Hello, World!" program in TypeScript:

```typescript
let message: string = 'Hello, World!';
console.log(message);
```

### Variables and Data Types

TypeScript adds type annotations to variables.

```typescript
let isDone: boolean = false;
let decimal: number = 6;
let hex: number = 0xf00d;
let color: string = "blue";
let list: number[] = [1, 2, 3];
```

### Control Flow

The control flow syntax is the same as in JavaScript.

```typescript
// If-else statement
let num: number = 5;
if (num > 0) {
    console.log("Number is positive.");
} else {
    console.log("Number is not positive.");
}

// For loop
for (let i = 0; i < 5; i++) {
    console.log(i);
}
```
