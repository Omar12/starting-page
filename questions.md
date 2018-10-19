# Questions

## Describe the Call Stack
The Call Stack is a data structure that keeps track of the execution context. It pushes the currently executing context and pops it when its done executing (LIFO). It keeps what function is currently being run and where to return to after an execution context is popped off the stack.

Imported: Yes

## Briefly describe a Closure
A function defined in another function

Imported: Yes

## What is a closure

Imported: No

## Explain the differences between imperative and declarative programming.

These two types of programming can roughly be summarized as:
* Imperative: how to achieve something
* Declarative: what should be achieved

Imperative

<pre class="code">
const numbers = [1, 2, 3, 4, 5] 
const numbersDoubled = [] 
for (let i = 0; i < numbers.length; i++) { 
  numbersDoubled[i] = numbers[i] * 2 
}
</pre>

Declarative

<pre class="code">
const numbers = [1, 2, 3, 4, 5] 
const numbersDoubled = numbers.map(n => n * 2)
</pre>

Imported: Yes