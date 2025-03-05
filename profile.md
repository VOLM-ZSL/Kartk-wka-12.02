# nr indeksu: 17
## Typescript
```
class Person {
    constructor(private name: string, private age: number) {}

    greet(): void {
        console.log(`Hello, my name is ${this.name} and I am ${this.age} years old.`);
    }

    static species: string = "Homo sapiens";

    get Name(): string {
        return this.name;
    }

    set Name(newName: string) {
        this.name = newName;
    }
}

const person = new Person("Alice", 25);
person.greet();
```