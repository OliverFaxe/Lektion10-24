# Lektion10-24
## 2024-10-14 JavaScript Intro

### Variables

 `var` har en `function scope`. Deklarerar man var i toppen av js file så är det globalt i hela filen. Medans om man deklarerar var i en function lever den bara i den funktionen. Undvik att använda var eftersom det är "outdated" och finns bättre sätt som `let` och `const`

 `const` betyder constant och kan inte bli Reassigned. const har en `block scope` Deklarerar man const i toppen av js file så är det globalt i hela filen. Medans om man deklarar en const inom {} måsvingar, lever den bara där.

 `let` är till största del samma som const, Men kan bli Reassigned.

### Comparison Operators
    För att bestäma våra conditions behöver vi verktyg för det. De kallas för `comparison operators`. 
    
     > Greater than
     < Less than
     >= Greater than OR equal
     <= Less than OR equal
     == Equal (NOT strict)
     === Equal (AND strict) - Föredras i JavaScript
     != Not Equal (NOT strict)
     !== Not Equal (AND strict)

### Logical Operators
    
    && Logical AND
    || Logical OR
    ! Logical NOT
    

### If Statements
 En if statement är ett sätt att få applikationen bestämma vilken riktning att gå. Beroende på vilka situationer vi bestämmer. Oftast har en app många situationer i olika kombinationer.

En Statement är ett set av instruktioner som datorn ska följa.

#### Exempel på if else statement

```js
if (condition) {
    // code to be executed if the condition is true.
} else {
    // code to be executed if the condition is false.
}
```

`if` är nyckelordet som säger till compiler att `om` en check är deklarerad. Antigen `true` eller `false`. Om bara if så är det för att skapa en väg om det är true.

`else` läggs till för att göra en annan väg om statement är false.

#### Exempel på if else if statement

 ```js
 const age = 16;
 if (age >= 18) {
        console.log("You can take your drivers license");
    }
 else if (age >= 16) {
    console.log("You can practice for a drivers license but not get it yet");
 }
     else { 
        console.log("You will have to take the bike");
        }
 ```

### Nested If Statements

```js
if (condition) {
    if (condition) {
        // code to run if nested check is true
    }
    // code that always run if original condition is true
}
```

### Truthy and Falsy values








