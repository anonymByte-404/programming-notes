<h1 style="color: #ecf0f1; background-color: #2c3e50; padding: 20px; text-align: center; border-radius: 10px; font-family: 'Arial', sans-serif;">Lesson 0: What is Programming?</h1>

<hr style="border: 1px solid #34495e;">

<h2 style="color: #3498db; background-color: #2c3e50; padding: 12px 20px; text-transform: uppercase; letter-spacing: 1px; border-radius: 8px;">🧠 Learning Objectives</h2>

<p style="color: #ecf0f1; font-size: 16px;">By the end of this lesson, you will be able to:</p>

<ul style="color: #ecf0f1; padding-left: 20px; font-size: 16px;">
  <li>Understand what programming is and why it is important.</li>
  <li>Recognize the core concepts behind writing code.</li>
  <li>Learn about different types of programming languages.</li>
  <li>Understand how programming shapes our everyday life and modern technology.</li>
  <li>Write your first simple program using TypeScript.</li>
</ul>

> [!TIP]
> For the best experience, use an IDE or editor that supports **Markdown styling** and offers **live preview** (like VS Code). It makes reading and editing this `.md` file much easier and more enjoyable!

<hr style="border: 1px solid #34495e;">

<h2 style="color: #e74c3c; background-color: #2c3e50; padding: 12px 20px; border-radius: 8px; text-transform: uppercase;">🖥️ What is Programming?</h2>

<h3 style="color: #8e44ad; font-size: 18px;">Definition</h3>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.6;">Programming, also known as coding or software development, is the process of creating a set of instructions that a computer can understand and execute. Through these instructions, a programmer tells a computer how to perform a task. The tasks can vary from calculating numbers, displaying information, controlling hardware, to running an entire website or managing a video game.</p>

<p style="color: #95a5a6; font-size: 16px; font-style: italic;"><strong>📝 Analogy:</strong> Imagine giving directions to a driver. You tell the driver to go straight, turn left, speed up, or slow down. Similarly, programming involves providing clear, step-by-step instructions to a computer (driver) to reach a specific destination (task).</p>

<hr style="border: 1px solid #34495e;">

<h3 style="color: #8e44ad; font-size: 18px;">How Does Programming Work?</h3>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.6;">The process of programming involves three main steps:</p>

<ol style="color: #ecf0f1; font-size: 16px; padding-left: 20px;">
  <li><strong>Writing Instructions:</strong> The programmer writes instructions in a programming language. These instructions can include calculations, decisions, or repetitions.</li>
  <li><strong>Translating Code:</strong> The computer doesn’t understand human languages directly, so the written code must be translated into machine code. This is done by a <strong>compiler</strong> or an <strong>interpreter</strong>.</li>
  <li><strong>Executing Instructions:</strong> Once translated, the computer follows the instructions and performs the tasks, like displaying information or making calculations.</li>
</ol>

<hr style="border: 1px solid #34495e;">

<h2 style="color: #2ecc71; background-color: #2c3e50; padding: 12px 20px; border-radius: 8px; text-transform: uppercase;">🔄 Why Is Programming Important?</h2>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.6;">Programming is at the core of nearly every technology we use today. From smartphones to social media platforms, every piece of technology involves some form of programming. Here are just a few examples:</p>

<ul style="color: #ecf0f1; font-size: 16px; list-style-type: circle; padding-left: 20px;">
  <li><strong>Websites:</strong> Platforms like Google, Facebook, and YouTube rely on complex programs to manage user interactions and display dynamic content.</li>
  <li><strong>Mobile Apps:</strong> Apps on your phone (e.g., Instagram, WhatsApp, and games) depend on code to handle everything from messaging to animations.</li>
  <li><strong>Artificial Intelligence:</strong> AI-driven services like virtual assistants (e.g., Siri, Google Assistant) and self-driving cars are all powered by intricate programs that interpret data and make decisions.</li>
  <li><strong>Gaming:</strong> The video games you enjoy are powered by code that dictates character movements, in-game physics, and more.</li>
</ul>

<hr style="border: 1px solid #34495e;">

<h3 style="color: #9b59b6; font-size: 18px;">Example: Your First Program in TypeScript</h3>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.6;">Let’s create a simple program that adds two numbers and prints the result. Here’s how we would write this in TypeScript:</p>

<pre style="background-color: #34495e; padding: 20px; border-radius: 5px;">
<code style="color: #ecf0f1;">// Simple Addition Program in TypeScript
function addTwoNumbers(a: number, b: number): number {
    return a + b;
}

let result: number = addTwoNumbers(5, 3);
console.log("The sum is:", result);
</code>
</pre>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.6;">In this TypeScript example:</p>
<ul style="color: #ecf0f1; font-size: 16px; padding-left: 20px;">
  <li>The <code>addTwoNumbers</code> function accepts two parameters, <code>a</code> and <code>b</code>, both of type <code>number</code>.</li>
  <li>The function returns the sum of these two numbers.</li>
  <li>The result is stored in the <code>result</code> variable, and then printed using <code>console.log()</code>.</li>
</ul>

<hr style="border: 1px solid #34495e;">

<h2 style="color: #3498db; background-color: #2c3e50; padding: 12px 20px; text-transform: uppercase; letter-spacing: 1px; border-radius: 8px;">🧑‍💻 Key Concepts in Programming</h2>

<h3 style="color: #8e44ad; font-size: 20px;">1. 🧠 What Are Programming Languages?</h3>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.6;">
  A <strong>programming language</strong> is a system of communication between humans and computers. It allows you to give instructions to a computer in a way it can understand and execute. Just like human languages, there are many programming languages, each designed for specific types of tasks—from websites to games to robots.
</p>

<p style="color: #bdc3c7;">
  You use these languages to create software, automate tasks, control devices, and more.
</p>

<hr style="border: 1px solid #34495e;">

<h4 style="color: #f39c12; font-size: 20px; margin-bottom: 20px;">💡 Types of Programming Languages</h4>

<table style="width: 100%; border-collapse: collapse; font-size: 16px; color: #ecf0f1; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
  <thead>
    <tr style="background-color: #8e44ad; color: white;">
      <th style="padding: 14px; border: 1px solid #7f8c8d; text-align: left;">Type</th>
      <th style="padding: 14px; border: 1px solid #7f8c8d; text-align: left;">Description</th>
      <th style="padding: 14px; border: 1px solid #7f8c8d; text-align: left;">Examples</th>
    </tr>
  </thead>
  <tbody>
    <tr style="background-color: #2c3e50;">
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><strong>High-Level</strong></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Easy to read and write, abstracted from hardware details.</td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Python, JavaScript, Java</td>
    </tr>
    <tr style="background-color: #34495e;">
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><strong>Low-Level</strong></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Closer to machine code; offers more control but harder to use.</td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">C, Assembly</td>
    </tr>
    <tr style="background-color: #2c3e50;">
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><strong>Compiled</strong></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Code is translated into machine code before running; fast and efficient.</td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">C++, Rust, Go</td>
    </tr>
    <tr style="background-color: #34495e;">
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><strong>Interpreted</strong></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Runs line-by-line via an interpreter; easier to test and debug.</td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Python, JavaScript, Ruby</td>
    </tr>
    <tr style="background-color: #2c3e50;">
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><strong>Object-Oriented</strong></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Uses classes and objects to organize code; good for large-scale applications.</td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Java, TypeScript, C++</td>
    </tr>
    <tr style="background-color: #34495e;">
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><strong>Functional</strong></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Focuses on pure functions and avoiding state changes; ideal for data and concurrency.</td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Haskell, F#, Lisp</td>
    </tr>
  </tbody>
</table>

<p style="color: #95a5a6; font-style: italic;">
  ⚙️ Many modern languages support multiple styles (multi-paradigm).
</p>

<hr style="border: 1px solid #34495e;">

<h4 style="color: #f39c12; font-size: 18px;">🔍 Comparing Code in Different Languages</h4>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.6;">
  Here’s how a simple program looks in different languages. Each one:
</p>

<ul style="color: #ecf0f1; font-size: 16px; line-height: 1.6;">
  <li>Defines a <code>name</code> variable</li>
  <li>Displays: <code>Hello, Alex!</code></li>
</ul>

<div style="background-color: #2c3e50; padding: 20px; border-radius: 12px; margin-top: 20px;">

  <h5 style="color: #1abc9c; font-size: 18px;">TypeScript</h5>
  <pre style="color: #ecf0f1; font-size: 16px;"><code>let name: string = "Alex";
console.log(`Hello, ${name}!`);</code></pre>

  <h5 style="color: #1abc9c; font-size: 18px;">JavaScript</h5>
  <pre style="color: #ecf0f1; font-size: 16px;"><code>let name = "Alex";
console.log(`Hello, ${name}!`);</code></pre>

  <h5 style="color: #1abc9c; font-size: 18px;">Python</h5>
  <pre style="color: #ecf0f1; font-size: 16px;"><code>name = "Alex"
print(f"Hello, {name}!")</code></pre>

  <h5 style="color: #1abc9c; font-size: 18px;">C++</h5>
<pre style="color: #ecf0f1; font-size: 16px;"><code>#include &lt;iostream&gt;
#include &lt;string&gt;<br />
using namespace std;<br/>
int main() {
&nbsp;&nbsp;string name = "Alex";
&nbsp;&nbsp;cout &lt;&lt; "Hello, " &lt;&lt; name &lt;&lt; "!" &lt;&lt; endl;
&nbsp;&nbsp;return 0;
}</code></pre>

  <h5 style="color: #1abc9c; font-size: 18px;">Go</h5>
  <pre style="color: #ecf0f1; font-size: 16px;"><code>package main
import "fmt"<br />
func main() {
&nbsp;&nbsp;name := "Alex"
&nbsp;&nbsp;fmt.Printf("Hello, %s!\n", name)
}</code></pre>
</div>

<p style="color: #95a5a6; font-size: 15px; font-style: italic; margin-top: 10px;">
  🔁 The syntax is different, but the logic is the same. Once you understand the core ideas, switching between languages becomes easier.
</p>

<hr style="border: 1px solid #34495e;">

<h4 style="color: #f39c12; font-size: 18px;">🎯 Why This Course Uses TypeScript</h4>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.6;">
  We’re starting with <strong>TypeScript</strong> because:
</p>

<ul style="color: #ecf0f1; font-size: 16px; padding-left: 20px; list-style-type: disc; line-height: 1.6;">
  <li>It builds on JavaScript (the most-used language worldwide)</li>
  <li>It adds <strong>types</strong> to help avoid errors before running your code</li>
  <li>It’s widely used for both front-end and back-end development</li>
  <li>It teaches great structure and professional coding habits</li>
</ul>

<p style="color: #bdc3c7;">
  TypeScript is powerful, scalable, and easy to transition into more advanced languages later.
</p>

<hr style="border: 1px solid #34495e;">
<h3 style="color: #8e44ad; font-size: 22px; margin-top: 30px;">🔢 2. Variables</h3>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.8; margin-bottom: 20px;">
  A <strong>variable</strong> is a named container in memory that stores data your program can access and manipulate.
  Think of it like a labeled box that can hold values—whether that's a number, a string of text, a list, or even more complex data like objects.
  Variables help make your programs dynamic, reusable, and easier to read and maintain.
</p>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.8; margin-bottom: 20px;">
  In TypeScript, variables are declared using <code>let</code>, <code>const</code>, or <code>var</code> (though <code>var</code> is outdated and rarely used).
  You also explicitly define the <strong>type</strong> of data the variable will store — like <code>string</code>, <code>number</code>, or <code>boolean</code>.
</p>

<h4 style="color: #f39c12; font-size: 18px; margin-bottom: 10px;">🧪 Example (TypeScript):</h4>

<pre style="background-color: #2c3e50; color: #ecf0f1; padding: 20px; border-radius: 8px; font-size: 15px; line-height: 1.6; overflow-x: auto;">
<code>// Declaring variables in TypeScript
let userName: string = "Alice";
let userAge: number = 25;

console.log(`${userName} is ${userAge} years old.`);
</code>
</pre>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.8;">Here’s a breakdown of what’s going on:</p>
<ul style="color: #ecf0f1; font-size: 16px; padding-left: 20px; line-height: 1.8;">
  <li><code>userName</code> is declared using <code>let</code> and stores a <code>string</code> value: <code>"Alice"</code>.</li>
  <li><code>userAge</code> is also declared using <code>let</code> and stores a <code>number</code> value: <code>25</code>.</li>
  <li><code>console.log()</code> prints a message to the console using <strong>template literals</strong> (backticks <code>`</code>) with embedded expressions <code>${}</code>.</li>
</ul>

<h4 style="color: #f39c12; font-size: 18px; margin-top: 25px;">🧠 Pro Tips</h4>

<ul style="color: #ecf0f1; font-size: 16px; padding-left: 20px; line-height: 1.8;">
  <li>Use <code>const</code> when the variable value shouldn't change (e.g., constants).</li>
  <li>Use <code>let</code> when you need a mutable variable that might change later.</li>
  <li>Always prefer explicit typing in TypeScript — it helps prevent bugs and improves readability.</li>
  <li>Variable names should be descriptive and use <strong>camelCase</strong> (e.g., <code>userEmail</code>).</li>
</ul>

<hr style="border: 1px solid #34495e;">

<h3 style="color: #8e44ad; font-size: 22px; margin-top: 30px;">🛠️ 3. Functions</h3>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.8; margin-bottom: 20px;">
  A <strong>function</strong> is one of the core building blocks in programming. It's a named block of code designed to perform a specific task. 
  Think of it like a machine: you give it input (parameters), it processes them (logic), and optionally gives back an output (return value).
</p>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.8;">
  Why are functions important?
</p>
<ul style="color: #ecf0f1; font-size: 16px; padding-left: 20px; line-height: 1.8; margin-bottom: 20px;">
  <li><strong>Reusability:</strong> Write once, use many times.</li>
  <li><strong>Readability:</strong> Functions help break your code into logical chunks.</li>
  <li><strong>Maintainability:</strong> Easier to update or fix specific tasks.</li>
  <li><strong>Abstraction:</strong> You can hide complex logic behind a simple function call.</li>
</ul>

<h4 style="color: #f39c12; font-size: 18px; margin-bottom: 10px;">🧪 Basic Function Example (TypeScript):</h4>
<pre style="background-color: #2c3e50; color: #ecf0f1; padding: 20px; border-radius: 8px; font-size: 15px; line-height: 1.6; overflow-x: auto;">
<code>function greet(name: string): void {
  console.log(`Hello, ${name}!`);
}<br />
greet("Alice");</code>
</pre>

<h4 style="color: #f39c12; font-size: 18px; margin-top: 30px;">📚 Function Anatomy</h4>
<table style="width: 100%; border-collapse: collapse; font-size: 16px; color: #ecf0f1; margin-top: 10px;">
  <thead>
    <tr style="background-color: #8e44ad; color: white;">
      <th style="padding: 12px; border: 1px solid #7f8c8d;">Component</th>
      <th style="padding: 12px; border: 1px solid #7f8c8d;">Explanation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><code>function</code></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Keyword to declare a function</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><code>greet</code></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">The name of the function</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><code>(name: string)</code></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Parameter named <code>name</code> with a type of <code>string</code></td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><code>: void</code></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Specifies that this function returns nothing</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><code>console.log()</code></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Prints a message to the console using template literals</td>
    </tr>
  </tbody>
</table>

<h4 style="color: #f39c12; font-size: 18px; margin-top: 30px;">🌐 Code Comparison in Other Languages</h4>

<h5 style="color: #1abc9c; font-size: 18px;">Python</h5>
<pre style="background-color: #2c3e50; color: #ecf0f1; padding: 20px; border-radius: 8px; font-size: 15px;">
<code>def greet(name: str) -> None:
&nbsp;&nbsp;print(f"Hello, {name}!")<br />
greet("Alice")</code>
</pre>

<h5 style="color: #1abc9c; font-size: 18px;">JavaScript</h5>
<pre style="background-color: #2c3e50; color: #ecf0f1; padding: 20px; border-radius: 8px; font-size: 15px;">
<code>function greet(name) {
&nbsp;&nbsp;console.log(`Hello, ${name}!`);
}<br />
greet("Alice");</code>
</pre>

<h5 style="color: #1abc9c; font-size: 18px;">C++</h5>
<pre style="background-color: #2c3e50; color: #ecf0f1; padding: 20px; border-radius: 8px; font-size: 15px;">
<code>#include &lt;iostream&gt;
#include &lt;string&gt;<br />
using namespace std;<br />
void greet(string name) {
&nbsp;&nbsp;cout &lt;&lt; "Hello, " &lt;&lt; name &lt;&lt; "!" &lt;&lt; endl;
}<br />
int main() {
&nbsp;&nbsp;greet("Alice");
&nbsp;&nbsp;return 0;
}</code>
</pre>

<h5 style="color: #1abc9c; font-size: 18px;">Java</h5>
<pre style="background-color: #2c3e50; color: #ecf0f1; padding: 20px; border-radius: 8px; font-size: 15px;">
<code>public class Main {
&nbsp;&nbsp;public static void greet(String name) {
&nbsp;&nbsp;&nbsp;&nbsp;System.out.println("Hello, " + name + "!");
&nbsp;&nbsp;}<br />
&nbsp;&nbsp;public static void main(String[] args) {
&nbsp;&nbsp;&nbsp;&nbsp;greet("Alice");
&nbsp;&nbsp;}
}</code>
</pre>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.8; margin-top: 20px;">
  As you can see, the concept of a function is present in all major programming languages, though syntax and type usage may vary. 
  Mastering how functions work is essential to becoming an effective developer!
</p>

<hr style="border: 1px solid #34495e;">

<h3 style="color: #8e44ad; font-size: 22px; margin-top: 30px;">🔁 4. Loops</h3>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.8; margin-bottom: 20px;">
  A <strong>loop</strong> is a control structure that allows you to execute a block of code repeatedly. 
  It's perfect when you want to automate repetitive tasks, such as processing items in a list or counting from one number to another.
</p>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.8;">
  Why use loops?
</p>
<ul style="color: #ecf0f1; font-size: 16px; padding-left: 20px; line-height: 1.8; margin-bottom: 20px;">
  <li><strong>Efficiency:</strong> Automates repetitive tasks.</li>
  <li><strong>Flexibility:</strong> Loop through arrays, objects, ranges, or any iterable data.</li>
  <li><strong>Dynamic behavior:</strong> Can stop or continue based on conditions.</li>
</ul>

<h4 style="color: #f39c12; font-size: 18px; margin-bottom: 10px;">📄 Basic <code>for</code> Loop Example (TypeScript):</h4>
<pre style="background-color: #2c3e50; color: #ecf0f1; padding: 20px; border-radius: 8px; font-size: 15px; line-height: 1.6; overflow-x: auto;">
<code>for (let i: number = 0; i < 5; i++) {
&nbsp;&nbsp;console.log("Iteration:", i);
}</code>
</pre>

<h4 style="color: #f39c12; font-size: 18px; margin-top: 30px;">🔍 Loop Anatomy Breakdown</h4>
<table style="width: 100%; border-collapse: collapse; font-size: 16px; color: #ecf0f1; margin-top: 10px;">
  <thead>
    <tr style="background-color: #8e44ad; color: white;">
      <th style="padding: 12px; border: 1px solid #7f8c8d;">Part</th>
      <th style="padding: 12px; border: 1px solid #7f8c8d;">Explanation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><code>let i: number = 0</code></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Start: initialize the loop counter</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><code>i &lt; 5</code></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Condition: run while this is true</td>
    </tr>
    <tr>
      <td style="padding: 12px; border: 1px solid #7f8c8d;"><code>i++</code></td>
      <td style="padding: 12px; border: 1px solid #7f8c8d;">Update: increase <code>i</code> after each loop</td>
    </tr>
  </tbody>
</table>

<h4 style="color: #f39c12; font-size: 18px; margin-top: 30px;">🌐 Code Comparison in Other Languages</h4>

<h5 style="color: #1abc9c; font-size: 18px;">Python</h5>
<pre style="background-color: #2c3e50; color: #ecf0f1; padding: 20px; border-radius: 8px; font-size: 15px;">
<code>for i in range(5):
&nbsp;&nbsp;print("Iteration:", i)</code>
</pre>

<h5 style="color: #1abc9c; font-size: 18px;">JavaScript</h5>
<pre style="background-color: #2c3e50; color: #ecf0f1; padding: 20px; border-radius: 8px; font-size: 15px;">
<code>for (let i = 0; i < 5; i++) {
&nbsp;&nbsp;console.log("Iteration:", i);
}</code>
</pre>

<h5 style="color: #1abc9c; font-size: 18px;">C++</h5>
<pre style="background-color: #2c3e50; color: #ecf0f1; padding: 20px; border-radius: 8px; font-size: 15px;">
<code>#include &lt;iostream&gt;<br />
using namespace std;<br />
int main() {
&nbsp;&nbsp;for (int i = 0; i < 5; i++) {
&nbsp;&nbsp;&nbsp;&nbsp;cout &lt;&lt; "Iteration: " &lt;&lt; i &lt;&lt; endl;
&nbsp;&nbsp;}
&nbsp;&nbsp;return 0;
}</code>
</pre>

<h5 style="color: #1abc9c; font-size: 18px;">Java</h5>
<pre style="background-color: #2c3e50; color: #ecf0f1; padding: 20px; border-radius: 8px; font-size: 15px;">
<code>public class Main {
&nbsp;&nbsp;public static void main(String[] args) {
&nbsp;&nbsp;&nbsp;&nbsp;for (int i = 0; i < 5; i++) {
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.out.println("Iteration: " + i);
&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;}
}</code>
</pre>

<h4 style="color: #f39c12; font-size: 18px; margin-top: 30px;">✨ Other Common Loops in TypeScript</h4>

<pre style="background-color: #2c3e50; color: #ecf0f1; padding: 20px; border-radius: 8px; font-size: 15px;">
<code>// While loop
let count: number = 0;
while (count < 5) {
&nbsp;&nbsp;console.log("While Count:", count);
&nbsp;&nbsp;count++;
}<br />
// For-of loop
const fruits: string[] = ["🍎", "🍌", "🍇"];
for (const fruit of fruits) {
&nbsp;&nbsp;console.log("Fruit:", fruit);
}<br />
// For-in loop (used for objects)
const user: { [key: string]: string | number } = { name: "Alice", age: 25 };
for (const key in user) {
&nbsp;&nbsp;console.log(key, "=", user[key]);
}</code>
</pre>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.8; margin-top: 20px;">
  Loops are fundamental to programming and appear in almost every language. Learning the different types helps you choose the most efficient loop for a task—whether it’s counting, iterating through collections, or conditional repetition.
</p>

<hr style="border: 1px solid #34495e;">

<h3 style="color: #8e44ad; font-size: 20px; margin-top: 30px;">5. 🧠 Conditionals</h3>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.8;">
  <strong>Conditionals</strong> let your program make decisions. They control the flow of execution depending on whether certain conditions are <code>true</code> or <code>false</code>.
  In TypeScript, there are several tools you can use to write conditional logic effectively:
</p>

<ul style="color: #ecf0f1; font-size: 16px; padding-left: 20px; line-height: 1.8;">
  <li><strong>if / else</strong> – for basic logic checks.</li>
  <li><strong>else if</strong> – for multiple branching conditions.</li>
  <li><strong>switch</strong> – for matching a value against many possible options.</li>
  <li><strong>ternary operator</strong> – a shorthand for simple conditions.</li>
  <li><strong>logical operators</strong> – combine or negate conditions using <code>&&</code>, <code>||</code>, and <code>!</code>.</li>
</ul>

<hr style="border: none; border-top: 1px solid #7f8c8d;">

<h4 style="color: #f39c12; font-size: 16px; margin-top: 15px;">🔹 Example: Basic If/Else</h4>

<pre style="background-color: #2c3e50; padding: 18px; border-radius: 8px;">
<code style="color: #ecf0f1;">let temperature: number = 30;<br />
if (temperature > 25) {
&nbsp;&nbsp;console.log("It's hot outside!");
} else {
&nbsp;&nbsp;console.log("It's cool outside.");
}
</code>
</pre>

<p style="color: #ecf0f1; font-size: 16px;">Checks a single condition and takes action based on the result.</p>

<h4 style="color: #f39c12; font-size: 16px; margin-top: 20px;">🔹 Else If Chain</h4>

<pre style="background-color: #2c3e50; padding: 18px; border-radius: 8px;">
<code style="color: #ecf0f1;">let score: number = 82;<br />
if (score >= 90) {
&nbsp;&nbsp;console.log("Grade: A");
} else if (score >= 80) {
&nbsp;&nbsp;console.log("Grade: B");
} else if (score >= 70) {
&nbsp;&nbsp;console.log("Grade: C");
} else {
&nbsp;&nbsp;console.log("Grade: D or lower");
}
</code>
</pre>

<p style="color: #ecf0f1; font-size: 16px;">
  Useful when checking a range of values, like grading systems, price ranges, etc.
</p>

<h4 style="color: #f39c12; font-size: 16px; margin-top: 20px;">🔹 Ternary Operator (Shorthand)</h4>

<pre style="background-color: #2c3e50; padding: 18px; border-radius: 8px;">
<code style="color: #ecf0f1;">let age: number = 20;
let canVote: string = age >= 18 ? "Yes" : "No";
console.log("Can vote?", canVote);
</code>
</pre>

<p style="color: #ecf0f1; font-size: 16px;">
  Great for assigning a value based on a condition in one line.
</p>

<h4 style="color: #f39c12; font-size: 16px; margin-top: 20px;">🔹 Logical Operators</h4>

<pre style="background-color: #2c3e50; padding: 18px; border-radius: 8px;">
<code style="color: #ecf0f1;">let isLoggedIn: boolean = true;
let isAdmin: boolean = false;<br />
if (isLoggedIn && isAdmin) {
&nbsp;&nbsp;console.log("Welcome, Admin!");
} else if (isLoggedIn && !isAdmin) {
&nbsp;&nbsp;console.log("Welcome, user!");
} else {
&nbsp;&nbsp;console.log("Please log in.");
}
</code>
</pre>

<p style="color: #ecf0f1; font-size: 16px;">
  Use <code>&&</code> (AND), <code>||</code> (OR), and <code>!</code> (NOT) to build compound logic.
</p>

<h4 style="color: #f39c12; font-size: 16px; margin-top: 20px;">🔹 Switch Statement</h4>

<pre style="background-color: #2c3e50; padding: 18px; border-radius: 8px;">
<code style="color: #ecf0f1;">let day: string = "Monday";<br />
switch (day) {
&nbsp;&nbsp;case "Monday":
&nbsp;&nbsp;&nbsp;&nbsp;console.log("Start of the work week.");
&nbsp;&nbsp;&nbsp;&nbsp;break;
&nbsp;&nbsp;case "Friday":
&nbsp;&nbsp;&nbsp;&nbsp;console.log("Almost the weekend!");
&nbsp;&nbsp;&nbsp;&nbsp;break;
&nbsp;&nbsp;case "Saturday":
&nbsp;&nbsp;case "Sunday":
&nbsp;&nbsp;&nbsp;&nbsp;console.log("Weekend time!");
&nbsp;&nbsp;&nbsp;&nbsp;break;
&nbsp;&nbsp;default:
&nbsp;&nbsp;&nbsp;&nbsp;console.log("Just another weekday.");
}
</code>
</pre>

<p style="color: #ecf0f1; font-size: 16px;">
  <strong>switch</strong> is useful when comparing a variable against many exact values. Don’t forget the <code>break</code> statements to avoid "fall-through".
</p>

<hr style="border: none; border-top: 1px solid #7f8c8d;">

<h4 style="color: #f39c12; font-size: 16px; margin-top: 20px;">💡 Best Practices</h4>

<ul style="color: #ecf0f1; font-size: 16px; padding-left: 20px; line-height: 1.8;">
  <li>Use <code>if/else</code> for ranges or boolean expressions.</li>
  <li>Use <code>switch</code> when checking one variable against multiple known values.</li>
  <li>Use <code>ternary</code> for simple true/false assignments—but avoid nesting them.</li>
  <li>Keep your conditional logic readable and avoid deep nesting.</li>
</ul>

<hr style="border: 1px solid #34495e;">
<h2 style="color: #e74c3c; background-color: #2c3e50; padding: 12px 20px; border-radius: 8px; text-transform: uppercase;">📚 Summary</h2>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.8;">
  In this lesson, you took your very first steps into the world of programming! 🚀 We explored what programming is, why it’s such a powerful tool in today’s world, and how it enables everything from websites to mobile apps to AI.
</p>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.8;">
  You also learned some of the most essential building blocks of code:
</p>

<ul style="color: #ecf0f1; font-size: 16px; padding-left: 20px; line-height: 1.8;">
  <li><strong>Variables</strong> – for storing and working with data</li>
  <li><strong>Functions</strong> – for organizing reusable blocks of logic</li>
  <li><strong>Loops</strong> – for repeating actions efficiently</li>
  <li><strong>Conditionals</strong> – for making decisions in your code</li>
</ul>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.8; margin-top: 10px;">
  And best of all, you wrote your first working program in <strong>TypeScript</strong>! 🎉 Whether you're aiming to build websites, apps, or games, these fundamentals are your stepping stones.
</p>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.8;">
  Keep practicing, experimenting, and building! The more you code, the more it all starts to click. 🧠💡
</p>

<hr style="border: 1px solid #34495e;">

<h2 style="color: #3498db; background-color: #2c3e50; padding: 12px 20px; border-radius: 8px; text-transform: uppercase;">🔍 Check Your Knowledge</h2>

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.8;">Time to test your understanding! Answer the following questions to see how well you've grasped the concepts:</p>

<ul style="color: #ecf0f1; font-size: 16px; padding-left: 20px; line-height: 1.8;">
  <li><strong>What is programming, and why is it important?</strong> (Think about the role programming plays in creating modern technology.)
    <!-- Programming is the process of writing instructions that a computer can execute. It's important because it powers everything from websites and apps to smart devices and cars. -->
  </li>

  <li><strong>What is a variable?</strong> (Explain how variables are used to store data in your program.)
    <!-- A variable is a named container used to store data in memory so that it can be reused and manipulated throughout the program. -->
  </li>

  <li><strong>Can you explain the purpose of loops?</strong> (What problem do loops solve in programming?)
    <!-- Loops allow you to repeat code multiple times without rewriting it. This is useful for tasks like iterating through arrays or performing an action until a condition is met. -->
  </li>

  <li><strong>How do conditionals affect the flow of a program?</strong> (What happens when a condition is true or false?)
    <!-- Conditionals enable decision-making in code. If a condition is true, one block of code runs; if false, a different block (or nothing) runs. This helps control the program’s logic and outcomes. -->
  </li>
</ul>

> [!NOTE]
> Stuck on a question? You can check the source code of this `.md` file — the answers are included as hidden comments for your reference!

<p style="color: #ecf0f1; font-size: 16px; line-height: 1.8; margin-top: 10px;">
  You’re doing an awesome job! 🏆 The more you practice and review, the closer you'll get to mastering these concepts. Keep it up, and remember: learning is a journey — keep experimenting, coding, and challenging yourself! 🚀
</p>

<hr style="border: 1px solid #34495e;">
