<h1>Fibonacci and Factorial Calculator</h1>

<p>This project provides functions to calculate Fibonacci sequence and factorial.</p>

<h2>Installation</h2>

<p>You can install this package via npm:</p>

<pre><code>npm install complex-package-minhhnob</code></pre>

<h2>Usage</h2>

<h3>Importing the Library</h3>

<p>To use the <code>fibonacci-factorial-calculator</code> in your project, you need to import it first:</p>

<pre><code>const calculator = require('fibonacci-factorial-calculator');</code></pre>

<h3>Functions</h3>

<h4><code>calculateFibonacci(n)</code></h4>

<p>This function calculates the Fibonacci sequence up to the given number <code>n</code>.</p>

<h5>Parameters:</h5>

<ul>
  <li><code>n</code>: The number up to which the Fibonacci sequence should be calculated.</li>
</ul>

<p>Example:</p>

<pre><code>const fibonacciSequence = calculator.calculateFibonacci(5);
console.log(fibonacciSequence); // Output: [0, 1, 1, 2, 3, 5]</code></pre>

<h4><code>calculateFactorial(n)</code></h4>

<p>This function calculates the factorial of the given number <code>n</code>.</p>

<h5>Parameters:</h5>

<ul>
  <li><code>n</code>: The number for which the factorial should be calculated.</li>
</ul>

<p>Example:</p>

<pre><code>const factorial = calculator.calculateFactorial(5);
console.log(factorial); // Output: 120</code></pre>

<h2>License</h2>

<p>This project is licensed under the MIT License - see the <a href="./LICENSE">LICENSE</a> file for details.</p>

<h2>Contributing</h2>

<p>Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. Please make sure to update tests as appropriate.</p>
