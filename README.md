<h1>Random Number Generator (1 to 100)</h1> 

<h2>Description</h2> 

This project includes a simple JavaScript function to generate a random integer between 1 and 100. The function leverages JavaScript's Math.random() and Math.floor() methods to ensure the output is both random and uniformly distributed.

<h3>How It Works</h3>

Math.random(): Generates a random decimal number between 0 (inclusive) and 1 (exclusive).

Scaling: The generated number is multiplied by 100, extending the range to 0 (inclusive) and 100 (exclusive).

Math.floor(): Rounds the number down to the nearest whole number, producing a range of integers between 0 and 99.

Offset: Adding 1 ensures the final range shifts from 0-99 to 1-100 (inclusive).

<h2>Usage</h2>

You can use this function in various applications where random numbers are required, such as:

Games: Generating random events or outcomes.

Simulations: Creating randomized scenarios.

Testing: Providing sample data for development purposes.

<h2>Applications</h2>

This function can be applied in a variety of use cases, including but not limited to:

Probability simulations.

Simple games or dice-like mechanics.

<h3>Requirements</h3>

JavaScript Environment: Any environment that supports JavaScript, such as Node.js or modern web browsers.



Generating test data for applications.

