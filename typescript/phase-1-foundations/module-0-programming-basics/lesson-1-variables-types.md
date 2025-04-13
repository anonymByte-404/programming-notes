<h1 style="color: #ecf0f1; background-color: #2c3e50; padding: 20px; text-align: center; border-radius: 10px; font-family: 'Arial', sans-serif;">
  Lesson 1: Variables & Types
</h1>

<hr style="border: 1px solid #34495e;">

<h2 style="color: #3498db; background-color: #2c3e50; padding: 12px 20px; text-transform: uppercase; letter-spacing: 1px; border-radius: 8px; font-family: 'Segoe UI', sans-serif; font-size: 22px; margin-top: 40px;">
  🧠 What You’ll Learn
</h2>

<ul style="color: #ecf0f1; font-size: 17px; padding-left: 20px; line-height: 1.8; font-family: 'Segoe UI', sans-serif;">
  <li>What variables are and how they are used to store and manage data in your program</li>
  <li>Introduction to the basic data types in TypeScript, including <code>string</code>, <code>number</code>, <code>boolean</code>, <code>any</code>, <code>null</code>, and <code>undefined</code></li>
  <li>How to declare and initialize variables with appropriate types</li>
  <li>The significance of type annotations and how TypeScript uses type inference to detect types automatically</li>
  <li>Best practices for working with different types of data, such as strings, numbers, booleans, objects, and arrays</li>
  <li>Hands-on exercises to practice declaring, assigning, and using variables in TypeScript</li>
</ul>

> [!TIP]
> For the best experience, use an IDE or editor that supports **Markdown styling** and offers **live preview** (like VS Code). It makes reading and editing this `.md` file much easier and more enjoyable!

<hr style="border: 1px solid #34495e;">

<h2 style="color: #e67e22; background-color: #2c3e50; padding: 12px 20px; text-transform: uppercase; letter-spacing: 1px; border-radius: 8px; font-family: 'Segoe UI', sans-serif; font-size: 22px; margin-top: 40px;">
  🔧 What Is a Variable?
</h2>

<p style="color: #ecf0f1; font-size: 17px; line-height: 1.8; font-family: 'Segoe UI', sans-serif;">
  A <strong>variable</strong> is a symbolic name for a value stored in memory. You can imagine it as a labeled container or folder on your computer's desktop — you can open it, put something inside, or replace what's inside later. This container helps your program remember and reuse values like numbers, names, settings, or user inputs.
</p>

<p style="color: #ecf0f1; font-size: 17px; line-height: 1.8; font-family: 'Segoe UI', sans-serif;">
  In TypeScript, variables are declared using <code>let</code>, <code>const</code>, or the older <code>var</code>. Here’s what they mean:
</p>

<ul style="color: #ecf0f1; font-size: 17px; line-height: 1.8; font-family: 'Segoe UI', sans-serif; padding-left: 20px;">
  <li><strong><code>let</code></strong> — A flexible variable. You can <em>change</em> its value later.</li>
  <li><strong><code>const</code></strong> — A constant. Once you assign a value, it <em>cannot</em> be changed.</li>
  <li><strong><code>var</code></strong> — An older way of declaring variables (rarely used in modern TypeScript).</li>
</ul>

<h3 style="color: #1abc9c; font-size: 18px; margin-top: 20px;">📦 Declaring Variables in TypeScript</h3>
<p style="color: #ecf0f1; font-size: 17px; font-family: 'Segoe UI', sans-serif;">
  TypeScript is a statically typed language, which means you can specify the type of data a variable should hold using type annotations. This helps catch errors early.
</p>

<pre style="background-color: #2c3e50; padding: 16px; border-radius: 8px; overflow-x: auto; font-family: 'Courier New', monospace;">
<code style="color: #ecf0f1; font-size: 15px;">let name: string = "Alice";       // name is a string
const birthYear: number = 1995;   // birthYear is a number<br/>
console.log(`Hello, my name is ${name}, and I was born in ${birthYear}.`);
</code>
</pre>

<p style="color: #bdc3c7; font-size: 16px; font-family: 'Segoe UI', sans-serif;">
  In the example above:
</p>
<ul style="color: #bdc3c7; font-size: 16px; font-family: 'Segoe UI', sans-serif; padding-left: 20px;">
  <li><code>name</code> is declared using <code>let</code>, so it can be updated later.</li>
  <li><code>birthYear</code> is declared using <code>const</code>, so it cannot be changed after being set.</li>
</ul>

<h3 style="color: #1abc9c; font-size: 18px; margin-top: 20px;">🔄 Reassigning Values with <code>let</code></h3>
<p style="color: #ecf0f1; font-size: 17px; font-family: 'Segoe UI', sans-serif;">
  Using <code>let</code>, you can change a variable's value as the program runs:
</p>

<pre style="background-color: #2c3e50; padding: 16px; border-radius: 8px; overflow-x: auto; font-family: 'Courier New', monospace;">
<code style="color: #ecf0f1; font-size: 15px;">let score: number = 0;<br />
score = 10;
score = score + 5;<br />
console.log("Final score is:", score); // Output: Final score is: 15
</code>
</pre>

<h3 style="color: #1abc9c; font-size: 18px; margin-top: 20px;">🚫 Reassigning a <code>const</code> Variable</h3>
<p style="color: #ecf0f1; font-size: 17px; font-family: 'Segoe UI', sans-serif;">
  Trying to change a <code>const</code> variable will cause an error:
</p>

<pre style="background-color: #2c3e50; padding: 16px; border-radius: 8px; overflow-x: auto; font-family: 'Courier New', monospace;">
<code style="color: #e74c3c; font-size: 15px;">const pi: number = 3.14;
pi = 3.14159; // ❌ Error: Cannot assign to 'pi' because it is a constant.
</code>
</pre>

<p style="color: #bdc3c7; font-size: 16px; font-family: 'Segoe UI', sans-serif;">
  Use <code>const</code> when you know the value won’t change (like configuration settings, math constants, etc.).
</p>

<h3 style="color: #1abc9c; font-size: 18px; margin-top: 20px;">🧠 Why Use Variables?</h3>
<p style="color: #ecf0f1; font-size: 17px; font-family: 'Segoe UI', sans-serif;">
  Variables make your code dynamic. Without them, every operation would be hard-coded and static. They allow your programs to:
</p>

<ul style="color: #ecf0f1; font-size: 17px; font-family: 'Segoe UI', sans-serif; padding-left: 20px;">
  <li>Store user input (e.g. name, age, email)</li>
  <li>Keep track of game scores or settings</li>
  <li>Store temporary results (like calculations)</li>
  <li>React to different scenarios (like winning or losing a game)</li>
</ul>

<p style="color: #2ecc71; font-size: 17px; font-family: 'Segoe UI', sans-serif; margin-top: 20px;">
  In short: <strong>variables are the building blocks</strong> of every program. Mastering how to use them is your first step toward becoming a great developer.
</p>

<hr style="border: 1px solid #34495e;">

<h2 style="color: #1abc9c; background-color: #2c3e50; padding: 12px 20px; text-transform: uppercase; letter-spacing: 1px; border-radius: 8px; font-family: 'Segoe UI', sans-serif; font-size: 22px; margin-top: 40px;">
  🗂️ Data Types in TypeScript
</h2>

<p style="color: #ecf0f1; font-size: 17px; line-height: 1.8; font-family: 'Segoe UI', sans-serif;">
  TypeScript is a statically typed language, which means that you define the type of data that a variable can hold when you declare it. This helps developers catch errors during the development process and makes the code more readable and maintainable. In TypeScript, data types are a critical feature because they help ensure that the program is working with the right type of data in the right context. Below is a detailed explanation of some of the most commonly used data types.
</p>

<table style="width: 100%; border-collapse: collapse; font-size: 16px; color: #ecf0f1; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); margin-top: 20px; font-family: 'Arial', sans-serif;">
  <thead>
    <tr style="background-color: #8e44ad; color: white;">
      <th style="padding: 14px; border: 1px solid #7f8c8d; text-align: left;">Type</th>
      <th style="padding: 14px; border: 1px solid #7f8c8d; text-align: left;">Description</th>
      <th style="padding: 14px; border: 1px solid #7f8c8d; text-align: left;">Example</th>
    </tr>
  </thead>
  <tbody>
    <tr style="background-color: #2c3e50;">
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><strong>string</strong></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">
        Represents a sequence of characters, such as text. Strings are surrounded by quotes (either single or double). In TypeScript, strings are immutable, meaning their values cannot be changed once they are created.
      </td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><code>"hello world"</code></td>
    </tr>
    <tr style="background-color: #34495e;">
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><strong>number</strong></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">
        Represents both integers and floating-point numbers. TypeScript uses the JavaScript Number type to represent all numeric values, which can be either integers or decimals.
      </td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><code>42, 3.14</code></td>
    </tr>
    <tr style="background-color: #2c3e50;">
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><strong>boolean</strong></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">
        Represents a logical value, either <code>true</code> or <code>false</code>. Typically used in control flow (like <code>if</code> statements) to evaluate conditions.
      </td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><code>true, false</code></td>
    </tr>
    <tr style="background-color: #34495e;">
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><strong>any</strong></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">
        A flexible type that can hold any kind of value, bypassing the strict typing of TypeScript. It is generally used when you are working with dynamic content or libraries that are not typed, but should be used sparingly to avoid losing the benefits of type safety.
      </td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><code>let value: any = 42;</code></td>
    </tr>
    <tr style="background-color: #2c3e50;">
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><strong>undefined</strong></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">
        Represents a variable that has been declared but not yet assigned a value. In TypeScript, a variable that is not assigned a value is considered to be <code>undefined</code>.
      </td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><code>let x: undefined;</code></td>
    </tr>
    <tr style="background-color: #34495e;">
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><strong>null</strong></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">
        Represents an intentional absence of any value. A variable of type <code>null</code> explicitly has no value. Unlike <code>undefined</code>, which is set by the JavaScript engine when a variable is not initialized, <code>null</code> must be manually assigned.
      </td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><code>let y: null = null;</code></td>
    </tr>
    <tr style="background-color: #2c3e50;">
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><strong>object</strong></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">
        Represents a collection of key-value pairs, where each key is a string and each value can be any type. Objects are used to store structured data and are one of the most commonly used data types in JavaScript and TypeScript.
      </td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><code>{ name: "Alice", age: 25 }</code></td>
    </tr>
    <tr style="background-color: #34495e;">
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><strong>array</strong></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">
        An ordered list of elements that are all of the same type. Arrays are commonly used to store collections of data, such as numbers or strings.
      </td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><code>[1, 2, 3], ["apple", "banana"]</code></td>
    </tr>
  </tbody>
</table>

<p style="color: #ecf0f1; font-size: 17px; line-height: 1.8; font-family: 'Segoe UI', sans-serif;">
  Understanding and properly using data types in TypeScript is essential for writing robust and maintainable code. Each type has its own specific use cases, and the more familiar you become with them, the better you will be at avoiding errors and optimizing your code.
</p>

<hr style="border: 1px solid #34495e;">

<h2 style="color: #9b59b6; background-color: #2c3e50; padding: 12px 20px; text-transform: uppercase; letter-spacing: 1px; border-radius: 8px; font-family: 'Segoe UI', sans-serif; font-size: 22px; margin-top: 40px;">
  🧪 Type Inference & Type Annotations
</h2>

<p style="color: #ecf0f1; font-size: 17px; line-height: 1.8; font-family: 'Segoe UI', sans-serif;">
  In TypeScript, every value has a <strong>type</strong>. A type describes what kind of data something is — for example, a <code>string</code> (text), a <code>number</code>, or a <code>boolean</code> (true/false). TypeScript uses these types to help you catch mistakes before your code runs.
</p>

<h3 style="color: #1abc9c; font-size: 18px; margin-top: 20px;">📌 What Are Type Annotations?</h3>
<p style="color: #ecf0f1; font-size: 17px; font-family: 'Segoe UI', sans-serif;">
  <strong>Type annotations</strong> are when you tell TypeScript what type a variable should have. This helps prevent bugs by making sure the variable only holds the right kind of data.
</p>

<pre style="background-color: #2c3e50; padding: 16px; border-radius: 8px; overflow-x: auto; font-family: 'Courier New', monospace;">
<code style="color: #ecf0f1; font-size: 15px;">let age: number = 16;           // age must always be a number
let isStudent: boolean = true; // isStudent can only be true or false
let name: string = "Olivia";   // name must be a string of text
</code>
</pre>

<p style="color: #bdc3c7; font-size: 16px; font-family: 'Segoe UI', sans-serif;">
  If you try to assign the wrong type of value, TypeScript will show an error:
</p>

<pre style="background-color: #2c3e50; padding: 16px; border-radius: 8px; overflow-x: auto; font-family: 'Courier New', monospace;">
<code style="color: #e74c3c; font-size: 15px;">let score: number = "ten"; // ❌ Error: Type 'string' is not assignable to type 'number'
</code>
</pre>

<h3 style="color: #1abc9c; font-size: 18px; margin-top: 20px;">⚡ What Is Type Inference?</h3>
<p style="color: #ecf0f1; font-size: 17px; font-family: 'Segoe UI', sans-serif;">
  TypeScript is smart! If you don’t write a type, it will try to guess it based on the value you assign. This is called <strong>type inference</strong>.
</p>

<pre style="background-color: #2c3e50; padding: 16px; border-radius: 8px; overflow-x: auto; font-family: 'Courier New', monospace;">
<code style="color: #ecf0f1; font-size: 15px;">let city = "New York";  // TypeScript infers 'city' is a string
let year = 2024;        // TypeScript infers 'year' is a number
let isLoggedIn = false; // TypeScript infers 'isLoggedIn' is a boolean
</code>
</pre>

<p style="color: #bdc3c7; font-size: 16px; font-family: 'Segoe UI', sans-serif;">
  Even though we didn’t specify the type, TypeScript already knows what kind of value each variable holds.
</p>

<h3 style="color: #1abc9c; font-size: 18px; margin-top: 20px;">🧠 Why Does This Matter?</h3>
<ul style="color: #ecf0f1; font-size: 17px; font-family: 'Segoe UI', sans-serif; padding-left: 20px;">
  <li><strong>Fewer bugs:</strong> TypeScript helps catch type mistakes before you run your program.</li>
  <li><strong>Better autocomplete:</strong> Knowing the type helps your code editor offer smarter suggestions.</li>
  <li><strong>Improved readability:</strong> Adding type annotations makes your code easier to understand later.</li>
</ul>

<h3 style="color: #1abc9c; font-size: 18px; margin-top: 20px;">🔍 Type Inference vs Type Annotation</h3>

<table style="width: 100%; border-collapse: collapse; margin-top: 10px; font-family: 'Segoe UI', sans-serif; font-size: 16px;">
  <thead>
    <tr style="background-color: #34495e; color: #ecf0f1;">
      <th style="padding: 10px; border: 1px solid #7f8c8d;">Feature</th>
      <th style="padding: 10px; border: 1px solid #7f8c8d;">Type Inference</th>
      <th style="padding: 10px; border: 1px solid #7f8c8d;">Type Annotation</th>
    </tr>
  </thead>
  <tbody>
    <tr style="color: #ecf0f1;">
      <td style="padding: 10px; border: 1px solid #7f8c8d;">Type is guessed?</td>
      <td style="padding: 10px; border: 1px solid #7f8c8d;">✅ Yes</td>
      <td style="padding: 10px; border: 1px solid #7f8c8d;">❌ No (you define it)</td>
    </tr>
    <tr style="color: #ecf0f1;">
      <td style="padding: 10px; border: 1px solid #7f8c8d;">Syntax</td>
      <td style="padding: 10px; border: 1px solid #7f8c8d;"><code>let name = "Lucy";</code></td>
      <td style="padding: 10px; border: 1px solid #7f8c8d;"><code>let name: string = "Lucy";</code></td>
    </tr>
    <tr style="color: #ecf0f1;">
      <td style="padding: 10px; border: 1px solid #7f8c8d;">More control?</td>
      <td style="padding: 10px; border: 1px solid #7f8c8d;">🚫 Limited</td>
      <td style="padding: 10px; border: 1px solid #7f8c8d;">✅ Full</td>
    </tr>
  </tbody>
</table>

<p style="color: #2ecc71; font-size: 17px; font-family: 'Segoe UI', sans-serif; margin-top: 20px;">
  In summary: <strong>Use inference</strong> when the type is obvious. <strong>Use annotations</strong> when you want to be explicit or work with more complex data.
</p>

<hr style="border: 1px solid #34495e;">

<h2 style="color: #e74c3c; background-color: #2c3e50; padding: 12px 20px; text-transform: uppercase; letter-spacing: 1px; border-radius: 8px; font-family: 'Segoe UI', sans-serif; font-size: 22px; margin-top: 40px;">
  🔒 let vs const vs var — Simple Guide to Understanding Variables
</h2>

<p style="color: #ecf0f1; font-size: 17px; line-height: 1.8; font-family: 'Segoe UI', sans-serif;">
  When you're coding, you often need to store data in variables. In modern JavaScript (and TypeScript), there are three main ways to do this: <code>let</code>, <code>const</code>, and <code>var</code>. Each one has a different purpose. Let's break them down in a simple way:
</p>

<h3 style="color: #f39c12; font-size: 20px;">🎯 What Do They Do?</h3>

<ul style="color: #ecf0f1; font-size: 17px; padding-left: 20px; line-height: 1.8;">
  <li><strong><code>const</code></strong>: This is used for values that should never change. Once you set a value with <code>const</code>, you can't change it. Great for things that are fixed, like the number of users allowed in your app.</li>
  <li><strong><code>let</code></strong>: This is used when the value might change later. For example, if you're counting the number of users who logged in, you'll use <code>let</code> because the number will change over time.</li>
  <li><strong><code>var</code></strong>: This is an older way of declaring variables. It’s similar to <code>let</code>, but it works differently. We usually avoid using <code>var</code> now because it can cause unexpected problems.</li>
</ul>

<h3 style="color: #1abc9c; font-size: 20px;">🧠 Why Does This Matter?</h3>

<p style="color: #ecf0f1; font-size: 17px;">
  Choosing the right keyword makes your code easier to understand and helps prevent mistakes. Here’s why:
</p>

<ul style="color: #ecf0f1; font-size: 17px; padding-left: 20px; line-height: 1.8;">
  <li><code>const</code> helps protect your data from being accidentally changed.</li>
  <li><code>let</code> is flexible and perfect for values that need to change, like counters or user inputs.</li>
  <li><code>var</code> can cause confusion and bugs, so it’s better to stick with <code>let</code> and <code>const</code>.</li>
</ul>

<h3 style="color: #3498db; font-size: 20px;">📦 Example: How to Use Them</h3>

<p style="color: #ecf0f1; font-size: 17px;">Here are some simple examples to show how <code>let</code>, <code>const</code>, and <code>var</code> work:</p>

<pre style="background-color: #2c3e50; padding: 16px; border-radius: 8px; overflow-x: auto; font-family: 'Courier New', monospace;">
<code style="color: #ecf0f1; font-size: 15px;">// Using const
const MAX_USERS = 100;
MAX_USERS = 120; // ❌ Error! You can't change a constant value<br />
// Using let
let currentUserCount = 45;
currentUserCount = 50; // ✅ Works! We can change the value of 'let'<br />
// Using var
var globalCounter = 10;
globalCounter = 15; // ✅ Works! We can change the value of 'var'<br />
console.log("MAX_USERS:", MAX_USERS); // Error if reassigned
console.log("Current user count:", currentUserCount); // 50
console.log("Global counter:", globalCounter); // 15
</code>
</pre>

<h3 style="color: #9b59b6; font-size: 20px;">🔍 Let’s Talk About Scope</h3>

<p style="color: #ecf0f1; font-size: 17px;">
  One big difference is where the variable can be used (its "scope"). Let’s see how <code>let</code> and <code>var</code> behave in a loop:
</p>

<pre style="background-color: #2c3e50; padding: 16px; border-radius: 8px; overflow-x: auto; font-family: 'Courier New', monospace;">
<code style="color: #ecf0f1; font-size: 15px;">// Using var in a loop
for (var i = 0; i < 5; i++) {
    console.log(i);
}
console.log(i); // ✅ Works! 'i' can be used outside the loop (because of 'var')<br />
// Using let in a loop
for (let j = 0; j < 5; j++) {
    console.log(j);
}
console.log(j); // ❌ Error! 'j' is not accessible outside the loop (because of 'let')
</code>
</pre>

<p style="color: #ecf0f1; font-size: 17px;">
  - <code>var</code> makes the variable available outside the loop, which can sometimes be confusing.
  - <code>let</code> keeps the variable inside the loop, which is safer and avoids bugs.
</p>

<h3 style="color: #2ecc71; font-size: 20px;">🔒 const with Objects and Arrays</h3>

<p style="color: #ecf0f1; font-size: 17px;">
  With <code>const</code>, you can’t change the reference to an object or array, but you can change what’s inside it. Here’s an example:
</p>

<pre style="background-color: #2c3e50; padding: 16px; border-radius: 8px; overflow-x: auto; font-family: 'Courier New', monospace;">
<code style="color: #ecf0f1; font-size: 15px;">const user = { name: "Alice", age: 25 };<br />
// ✅ Changing properties is allowed
user.age = 26;<br />
// ❌ Reassigning the entire object is not allowed
user = { name: "Bob", age: 30 }; // Error! You can't change the reference
</code>
</pre>

<p style="color: #ecf0f1; font-size: 17px;">
  You can change the content inside the object, but you can’t point the constant to a completely new object. This is an important distinction to keep in mind when using <code>const</code> with complex data structures like objects and arrays.
</p>

<h3 style="color: #e74c3c; font-size: 20px;">⚡ Key Takeaways</h3>

<ul style="color: #ecf0f1; font-size: 17px; padding-left: 20px; line-height: 1.8;">
  <li><code>const</code>: Use when the value should never change. It’s like a "locked" variable.</li>
  <li><code>let</code>: Use when the value might change over time. It’s flexible and can be updated.</li>
  <li><code>var</code>: Avoid using it! It’s old and can cause confusion because of its unpredictable scope.</li>
  <li><code>const</code> and <code>let</code> are the safer, more modern choices. Use <code>const</code> whenever possible, and use <code>let</code> when you need flexibility.</li>
</ul>

<h3 style="color: #3498db; font-size: 20px;">🔎 Comparison Table</h3>

<table style="width: 100%; border-collapse: collapse; font-size: 16px; color: #ecf0f1; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); margin-top: 20px; font-family: 'Arial', sans-serif;">
  <thead>
    <tr style="background-color: #8e44ad; color: white;">
      <th style="padding: 14px; border: 1px solid #7f8c8d; text-align: left;">Keyword</th>
      <th style="padding: 14px; border: 1px solid #7f8c8d; text-align: left;">When to Use</th>
      <th style="padding: 14px; border: 1px solid #7f8c8d; text-align: left;">Can Be Reassigned?</th>
      <th style="padding: 14px; border: 1px solid #7f8c8d; text-align: left;">Scope</th>
      <th style="padding: 14px; border: 1px solid #7f8c8d; text-align: left;">Use in Loops</th>
    </tr>
  </thead>
  <tbody>
    <tr style="background-color: #2c3e50;">
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><strong>const</strong></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">For values that should never change (e.g., constants like max users).</td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">No, cannot be reassigned.</td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Block scope, accessible only within the block where it's defined.</td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Safe to use in loops; content of objects or arrays can change, but the reference cannot.</td>
    </tr>
    <tr style="background-color: #34495e;">
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><strong>let</strong></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">For values that may change (e.g., counters, user input).</td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Yes, can be reassigned.</td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Block scope, accessible only within the block where it's defined.</td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Perfect for use in loops; value can change during the loop.</td>
    </tr>
    <tr style="background-color: #2c3e50;">
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><strong>var</strong></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Old way of declaring variables (avoid using). Used in functions for scoping.</td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Yes, can be reassigned.</td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Function scope, accessible throughout the entire function.</td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Can be used in loops, but its scope is less predictable because it’s function-scoped.</td>
    </tr>
  </tbody>
</table>

<hr style="border: 1px solid #34495e;">
<h2 style="color: #e74c3c; background-color: #2c3e50; padding: 12px 20px; text-transform: uppercase; letter-spacing: 1px; border-radius: 8px; font-family: 'Segoe UI', sans-serif; font-size: 22px; margin-top: 40px;"> 🌍 What is Scope?</h2>
<p style="color: #ecf0f1; font-size: 17px; line-height: 1.8; font-family: 'Segoe UI', sans-serif;"> 
In programming, <strong>scope</strong> refers to the <strong>context</strong> or <strong>area</strong> in which a variable is accessible or can be used. The scope determines where a variable can be accessed, modified, or even deleted. In JavaScript and TypeScript, we primarily deal with three types of scopes: <strong>global scope</strong>, <strong>function scope</strong>, and <strong>block scope</strong>.
</p>

<h3 style="color: #f39c12; font-size: 20px;">🎯 Types of Scope</h3>
<ul style="color: #ecf0f1; font-size: 17px; padding-left: 20px; line-height: 1.8;">
  <li><strong>Global Scope</strong>: A variable declared outside of any function or block is in the global scope. It can be accessed from anywhere in your program.</li>
  <li><strong>Function Scope</strong>: A variable declared inside a function using <code>var</code> is in function scope. It can only be accessed from within that function.</li>
  <li><strong>Block Scope</strong>: A variable declared inside a block (like a loop or an if statement) using <code>let</code> or <code>const</code> is in block scope. It can only be accessed within the block where it is declared.</li>
</ul>

<p style="color: #95a5a6; font-style: italic;">
Think of scope like a room in a house. If a variable is in the <strong>global scope</strong>, it’s like placing an item in the living room that everyone in the house can access. If a variable is in a <strong>function scope</strong>, it’s like placing an item in the kitchen that only the people cooking can access. If a variable is in the <strong>block scope</strong>, it’s like placing an item in a bedroom that can only be accessed when you're inside the bedroom (like during a specific task).
</p>

<h3 style="color: #1abc9c; font-size: 20px;">🔍 Scope in Action</h3>
<p style="color: #ecf0f1; font-size: 17px;">
Here’s an example of how scope works with variables declared using <code>let</code>, <code>const</code>, and <code>var</code>:
</p>
<pre style="background-color: #2c3e50; padding: 16px; border-radius: 8px; overflow-x: auto; font-family: 'Courier New', monospace;">
<code style="color: #ecf0f1; font-size: 15px;">// Global scope
let globalVariable: string = "I'm global!";  <br/>
function testScope() {
&nbsp;&nbsp;// Function scope (using var)
&nbsp;&nbsp;var functionScopeVariable: string = "I'm inside a function!";<br /> 
&nbsp;&nbsp;if (true) {
&nbsp;&nbsp;&nbsp;&nbsp;// Block scope (using let)
&nbsp;&nbsp;&nbsp;&nbsp;let blockScopeVariable: string = "I'm inside a block!";
&nbsp;&nbsp;&nbsp;&nbsp;console.log(blockScopeVariable);  // ✅ Works inside the block
&nbsp;&nbsp;}
&nbsp;&nbsp;console.log(functionScopeVariable);  // ✅ Works inside the function
&nbsp;&nbsp;console.log(globalVariable);         // ✅ Works everywhere (global scope)
}<br />
testScope();<br/>
console.log(globalVariable);  // ✅ Works because it's in the global scope
console.log(functionScopeVariable); // ❌ Will throw an error, because var is function scoped
console.log(blockScopeVariable);    // ❌ Will throw an error, because let is block scoped
</code>
</pre>

<p style="color: #ecf0f1; font-size: 17px;">
In this example:
<ul style="color: #ecf0f1; font-size: 17px;">
  <li><code>globalVariable</code> is in the global scope, so it can be accessed anywhere in the program.</li>
  <li><code>functionScopeVariable</code> is declared using <code>var</code>, so it's function-scoped. This means it can only be accessed inside the function, and trying to access it outside the function will cause an error.</li>
  <li><code>blockScopeVariable</code> is declared using <code>let</code>, so it's block-scoped. It can only be accessed inside the block (in this case, inside the <code>if</code> statement).</li>
</ul>
</p>

<h3 style="color: #3498db; font-size: 20px;">📌 Why Does Scope Matter?</h3>
<ul style="color: #ecf0f1; font-size: 17px; padding-left: 20px; line-height: 1.8;">
  <li><strong>Prevents Errors:</strong> Limiting the scope of a variable reduces the chances of accidentally changing a variable that shouldn’t be modified. For example, you can't accidentally modify a variable in a block that’s used in a different part of your program.</li>
  <li><strong>Improves Code Organization:</strong> By restricting the use of variables to specific areas (functions or blocks), your code becomes cleaner and easier to understand. Each piece of code has its own local area of responsibility.</li>
  <li><strong>Helps with Memory Management:</strong> Variables in local scope are cleared from memory when their scope ends (e.g., when a function finishes executing), which helps keep your program more efficient.</li>
</ul>

<hr style="border: 1px solid #34495e;">

<h2 style="color: #f39c12; background-color: #2c3e50; padding: 12px 20px; text-transform: uppercase; letter-spacing: 1px; border-radius: 8px; font-family: 'Segoe UI', sans-serif; font-size: 22px; margin-top: 40px;">
  📚 Summary
</h2>

<p style="color: #ecf0f1; font-size: 17px; line-height: 1.8; font-family: 'Segoe UI', sans-serif;">
  In this lesson, we covered the foundational concept of <strong>variables</strong> and how they are essential for storing and managing data within our programs. We delved into various <strong>data types</strong> in TypeScript, including <code>string</code>, <code>number</code>, <code>boolean</code>, and others, understanding their specific uses and characteristics.
</p>

<p style="color: #ecf0f1; font-size: 17px; line-height: 1.8; font-family: 'Segoe UI', sans-serif;">
  We explored how to properly declare variables, assign values, and the importance of using the right data types to ensure our programs are both <strong>efficient</strong> and <strong>error-free</strong>. Mastering these basic concepts allows for more flexible, dynamic, and maintainable code. As you continue to write more complex programs, these foundational skills will serve as the building blocks for more advanced concepts.
</p>

<hr style="border: 1px solid #34495e;">

<h2 style="color: #3498db; background-color: #2c3e50; padding: 12px 20px; border-radius: 8px; text-transform: uppercase;">🔍 Check Your Knowledge</h2>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.8;">Time to test your understanding! Answer the following questions to see how well you've grasped the concepts:</p>

<ul style="color: #ecf0f1; font-size: 16px; padding-left: 20px; line-height: 1.8;">
  <li><strong>What is a variable in programming, and why is it important?</strong> (Think about how variables help store and manage data in a program.)
    <!-- A variable is a named container used to store data in memory. It allows programs to store, modify, and reuse values throughout the execution. -->
  </li>

  <li><strong>What is the difference between <code>string</code> and <code>number</code> types in TypeScript?</strong> (Consider what kinds of values each type can hold.)
    <!-- <code>string</code> represents a sequence of characters, while <code>number</code> can represent both integer and floating-point numbers. -->
  </li>

  <li><strong>What is the <code>boolean</code> data type used for, and how do you use it?</strong> (Think about how you would store true/false values in your program.)
    <!-- The <code>boolean</code> data type is used to store values of true or false, which are commonly used for conditions and logic in programming. -->
  </li>

  <li><strong>What does the <code>any</code> type mean in TypeScript, and when might you use it?</strong> (Consider the advantages and drawbacks of using <code>any</code>.)
    <!-- The <code>any</code> type allows you to store any type of value, essentially bypassing TypeScript’s type system. It should be used cautiously as it removes type safety. -->
  </li>

  <li><strong>How does <code>undefined</code> differ from <code>null</code> in TypeScript?</strong> (Think about the difference in meaning and usage between these two types.)
    <!-- <code>undefined</code> means a variable has been declared but not assigned a value, while <code>null</code> represents an intentional absence of value. -->
  </li>

  <li><strong>What is an <code>object</code> type, and how would you define one in TypeScript?</strong> (Consider the structure of objects and how they are used in code.)
    <!-- An <code>object</code> type in TypeScript is a collection of key-value pairs, where the keys are strings (or other types) and the values can be any type. -->
  </li>

  <li><strong>What is the difference between an <code>array</code> and an <code>object</code> in TypeScript?</strong> (Think about how each is structured and used in a program.)
    <!-- An <code>array</code> is an ordered collection of values, whereas an <code>object</code> is an unordered collection of key-value pairs. -->
  </li>
</ul>

> [!NOTE]
> Stuck on a question? You can check the source code of this `.md` file — the answers are included as hidden comments for your reference!

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.8; margin-top: 10px;">
  You’re doing an awesome job! 🏆 The more you practice and review, the closer you'll get to mastering these concepts. Keep it up, and remember: learning is a journey — keep experimenting, coding, and challenging yourself! 🚀
</p>

<hr style="border: 1px solid #34495e;">
