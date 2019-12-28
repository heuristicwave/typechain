## Note



**Install**

- TSLint
- yarn



**modules**

```shell
yarn add tsc-watch --dev
```



##### ? param option check

```typescript
const name = "HeuristicWave",
  age = 7,
  gender = "male";

const sayHi = (name, age, gender?) => {
  console.log(`Hello ${name}, you are ${age}, you are a ${gender}`);
};

sayHi(name, age, gender); // this func check params

export {};	// module export
```



##### ? params type check

```typescript
const sayHi = (name: string, age: number, gender: string): void => {
    return `Hello ${name}, you are ${age}, you are a ${gender}!`;
  };
  
(sayHi("Heuri", 7, "male");
  
export {};

/// return value : string
const sayHi = (name: string, age: number, gender: string): string => {
    return `Hello ${name}, you are ${age}, you are a ${gender}!`;
  };
  
console.log(sayHi("Heuri", 7, "male"));
  
export {};
```

