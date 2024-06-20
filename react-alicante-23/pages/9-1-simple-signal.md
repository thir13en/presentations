# Anatomy of a Signal

```ts
const [count, setCount] = createSignal(0);

// read a value
console.log(count()); // 0

// set a value
setCount(5);
console.log(count()); //5

```
This syntax has slight varitions in the different frameworks, for example in vue we declare them as `ref`