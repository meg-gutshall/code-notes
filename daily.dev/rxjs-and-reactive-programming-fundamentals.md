---
description: 01/26/2020
---

# RxJS & Reactive Programming Fundamentals

## Abstract

### RxJS & Reactive Programming Fundamentals

#### \_\_[_Ben Lesh_](https://twitter.com/BenLesh)_, Software Engineer at Citadel & Author of RxJS_

[RxJS](https://rxjs.dev/guide/overview) is one of the hottest libraries in web development today. We will walk through understanding reactive programming, the components of RxJS, common operators and Observables, and how to create an Observable from scratch.

## Overview

* Four major reactive algorithms
  * push
  * pull
  * push-pull
  * pull-push

### Reactive Push

* The consumer is given the value by the producer as soon as it's ready
* ...
* Examples:
  * Promises
  * Observerables \(RxJS, Svelte, Relay, et al.\)
  * Event emitters\*

### Reactive Pull

* The consumer must proactively request the value fr
* Examples:
  * Iterables \(Sets, Maps, Arrays...
  * Enumerables
  * Computed properties\*

### Reactive Push-Pull

* The producer notifies the consumer that there is a new value waiting.
* The consumer them must request the new value from the producer.
* Examples:
  * Ember's Object Model\*
  * MobX\*

### Reactive Pull-Push

* The consumer requests a future from the producer \(like a promise to a future value\).
* The producer gives the consumer the new value as soon as it's ready.
* Examples:
  * AsyncIterators
  * Async Generators \(async function\*\)
  * IxJS

## Push vs. Pull

Not all reactive algorithms are created equal

### Pull

* Pros:
  * Simple
  * Synchronous
  * Consumer controls the rate
* Cons:
  * Doesn't handle async well

### Push

* Pros:
  * Still pretty simple
  * Synchronous or Asynchronous
  * Producer controls the rate
* Cons:
  * Consumer has no control over the rate of new values

## Hybrid Approaches

* Great for high-volume systems that require back-pressure control, perhaps at the cost of _some_ complexity

### Push-Pull

* Pros:
  * Synchronous or Asynchronous
  * Producer and 
* Cons:
  * 

### Pull-Push

* Pros:
  * Synchronous or Asynchronous
* Cons:
  * 



