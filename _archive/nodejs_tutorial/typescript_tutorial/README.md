# TypeScript Tutorial

## Resources
- https://dev.to/pranav89624/the-ultimate-typescript-learning-resource-stack-that-every-developer-needs-3alb



## Installation
```bash
npm install -g typescript
```

## Create first app
```typescript
function greeter(person) {
  return "Hello, " + person;
}
 
let user = "Jane User";
 
document.body.textContent = greeter(user);
```

## Transpiling
```bash
tsc greeter.ts
```