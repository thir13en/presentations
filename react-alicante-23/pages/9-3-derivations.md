# Derivations

This is how we can react to any get event of the signal.
```ts
const [firstName, setFirstName] = createSignal("John");
const [lastName, setLastName] = createSignal("Smith");
// derivations
const fullName = () => {
  console.log("Creating/Updating fullName");
  return `${firstName()} ${lastName()}` // runs on setting of the underlying signals on when reading it
};
// reactions
createEffect(() => console.log("My name is", fullName()));
createEffect(() => console.log("Your name is not", fullName()));
setFirstName("Jacob");
```
```shell
Creating/Updating fullName
My name is John Smith
Creating/Updating fullName
Your name is not John Smith
Creating/Updating fullName
My name is Jacob Smith
Creating/Updating fullName
Your name is not Jacob Smith
```