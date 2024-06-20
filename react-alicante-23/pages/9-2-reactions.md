# Reactions

This is how we can react to any set event of the signal running our own custom business logic

```ts
console.log("1. Create Signal");
const [count, setCount] = createSignal(0);

console.log("2. Create Reaction");
createEffect(() => console.log("The count is", count())); // runs on creation (eager)

console.log("3. Set count to 5");
setCount(5);

console.log("4. Set count to 10");
setCount(10);
```
```shell
1. Create Signal
2. Create Reaction
The count is 0
3. Set count to 5
The count is 5
4. Set count to 10
The count is 10
```