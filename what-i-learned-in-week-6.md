## What I learned in week 6

### Monday
Loops!


Every `loop` needs to have the following
* Setup
* Continuation Check
* Change - need to use `let` for variables

Example:

``` javascript
        let num = 1;  //change

        while (num < 10){  //setup
        console.log('hola');

        num = num + 1; //check
}
 ```

 For indices, you'll generally want to start at 0 as thats where coding starts counting.  A common variable for index is `i` as in `let i = 0`

 #### Wednesday

 *String Interpolation*

Allows easier use with strings so you don't have to use '+' and spaces '  ' to put together multiple strings.
 ``` javascript 
console.log(`${firstname} ${lastname} is an ${role} a ${scool}.`)

console.log(`He will be ${age +1} years old.`)
```
Where {variable} will be defined before.  You can even call functions within the {}'s.  **Note**:  Need to use back ticks ``

******
``` javascript
num +=1 is the same as num = num + 1 and also num ++  (Bump)
num -=   (num --)
num *=

```

### Thursday

`includes` feature -

```javascript 
const = 'hello
greeting.includes('h')

if (greeting.includes('h')){
    consol.log('yes')
} else {
    console.log('no')
}
```

#### Arrays
Allow you to have a list of things and choose from them.

```javascript
let greetings = ['hello', 'yo', 'heya'] ;
greeting [0]; //hello
greeting [1]; //yo
````

Can add to an array by making indexof[end number]= added value
or you can use 
* array-name.push() which will automatically put it to the end   
* array-name.pop() will delete it from the end  
* array-name.shift() will delete from the start
* array-name.unshift() will add to the front