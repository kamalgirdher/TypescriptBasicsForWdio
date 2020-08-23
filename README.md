# Typescript

<details><summary><b>Introduction</b></summary>
<p>

JavaScript was introduced as a language for the client side. The development of Node.js has marked JavaScript as an emerging server-side technology too. However, as JavaScript code grows, it tends to get messier, making it difficult to maintain and reuse the code. Moreover, its failure to embrace the features of Object Orientation, strong type checking and compile-time error checks prevents JavaScript from succeeding at the enterprise level as a full-fledged server-side technology. TypeScript was presented to bridge this gap.

Typescript is a superset of Javascript

![typescript](images/superset.png)


A TypeScript program contains:

* Modules
* Functions
* Variables
* Statements and Expressions
* Comments
</p>
</details>


<details><summary><b>Hello World! in Typescript</b></summary>
<p>

```
const msg:string = "Hello World!" 
console.log(msg)
```
</p>
</details>


<details><summary><b>Keywords in Typescript</b></summary>
<p>

| break | as | any | switch | case | if | throw |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| else | var | number | string | get | module | type |
| instanceof | typeof | public | private | enum | export | finally |
| for | while | void | null | super | this | new |
| in | return | true | false | any | extends | static | 
| let | package | implements | interface | function | new | try |
| yield | const | continue | do | catch |

</p>
</details>


<details><summary><b>Types in Typescript</b></summary>
<p>
TypeScript provides data types as a part of its optional Type System.

**Built-in types**

| Data type	| Keyword |
| :---: | :---: | 
| Number | number |
| String | string |
| Boolean | boolean |
| Void | void |
| Null | null |
| Undefined | undefined |

```
let a: number = 10;
let b: string = 'kamal';
let c: boolean = true;
```

**any**

The any data type is the super type of all types in TypeScript. It denotes a dynamic type. Using the any type is equivalent to opting out of type checking for a variable.

```
let d: any;
d= 'kamal';
```

</p>
</details>


<details><summary><b>Variables and Constants</b></summary>
<p>

We have 3 keywords for this in Typescript or Javascript.

| Keyword	|
| :---: |
| var |
| let |
| const |

**var** declarations are globally scoped or function scoped while **let** and **const** are block scoped. var variables can be updated and re-declared within its scope; let variables can be updated but not re-declared; const variables can neither be updated nor re-declared.

**without types**
```
var a = 'kamal';
const b = 10;
let c = 'kamal';
```

**with types**
```
var a: string = 'kamal';
const b:number = 10;
let c:string = 'kamal';
```

**if you don't know the type, use any**

```
let x: any;
x='kamal';
```

#### Scope

* Global Scope − Global variables are declared outside the programming constructs. These variables can be accessed from anywhere within your code.

* Class Scope − These variables are also called fields. Fields or class variables are declared within the class but outside the methods. These variables can be accessed using the object of the class. Fields can also be static. Static fields can be accessed using the class name.

* Local Scope − Local variables, as the name suggests, are declared within the constructs like methods, loops etc. Local variables are accessible only within the construct where they are declared.

```
var x = 12          //global variable 
class Kamal { 
   y = 13;             //class variable 
   
   testFunction():void { 
      var z = 14;    //local variable 
   } 
} 
```

</p>
</details>


<details><summary><b>Operators</b></summary>
<p>
</p>
</details>


<details><summary><b>Conditional Statements</b></summary>
<p>
</p>
</details>


<details><summary><b>Loops</b></summary>
<p>
</p>
</details>


<details><summary><b>Functions</b></summary>
<p>
</p>
</details>


<details><summary><b>Arrays</b></summary>
<p>
</p>
</details>


<details><summary><b>Classes & Objects</b></summary>
<p>
</p>
</details>


<details><summary><b>Modules</b></summary>
<p>
</p>
</details>

