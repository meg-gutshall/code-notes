# Intro to Code Efficiency

## Big O Notation

* O\(1\) --&gt; constant
* O\(n\) --&gt; linear
* O\(log n\) --&gt; logarithmic
* O\(n\*\*2\) --&gt; quadratic

The entire complexity is made up of terms and only the most significant term is tracked. We always measure by the worst-case scenario.

**Big-O Algorithm Complexity Cheat Sheet**

{% embed url="https://www.bigocheatsheet.com/" %}

## Array Complexity

* Access \(read\): constant
* Search: linear
* Insertion \(write\): linear \(worst-case scenario\)
  * Adding onto the end: constant \(best-case scenario\)
* Deletion: linear \(worst-case scenario\)
  * Removing from the end: constant \(best-case scenario\)

## Hashmap Complexity

When two key-value pairs are stored in the same space, it's called a collision—not good.

* Access \(read\): N/A
* Search: constant
* Insertion \(write\): constant
* Deletion: constant

## Repl.it

{% embed url="https://repl.it/@daniel\_dawson/CodeEfficiency\#index.js" %}



