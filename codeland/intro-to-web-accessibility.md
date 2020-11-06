---
description: First session on 07/24/20
---

# Intro to Web Accessibility

> **Navdeep Singh \(presenter\)**
>
> **Ibukunoluwa Salau \(proctor\)**

Workshop activities: 

{% embed url="https://workshop-a11y.vercel.app/" %}

## Screen Readers

### VoiceOver Commands

VoiceOver built into Mac. Familiarize yourself with the commands.

## Why Focus on Accessibility?

### Accessibility by the numbers



### Accessibility helps everybody

Permanent, temporary, and situational

## WCAG 2.0

### Four principles:

* **P**erceivable
* **O**perable
* **U**nderstandable
* **R**obust

### Conformance Levels

* **A**
* **AA**
* **AAA**

## Basic Steps

1. Focus
   1. Website **must** be keyboard accessible
2. Semantics
   1. Proper use of HTML elements
3. Styling

## Activity 1

{% embed url="https://workshop-a11y.vercel.app/1.focus-semantics" %}

{% embed url="https://workshop-a11y-solution.vercel.app/1.focus-semantics" %}

### Another Activity

**DOM order matters to screen readers!!**

## **Activity 2**

_Links -- Styling_

### **ARIA**

**A**ccessible **R**ich **I**nternet **A**pplications

ARIA is used appropriately to enhance accessibility when HTML is not sufficient.

`aria-labellebby` correlates to an `id` attribute in an HTML heading element

`aria-describedby` correlates to an `id` attribute in an HTML element that describes the image

ARIA works by changing and augmenting the standard DOM accessibility tree.

## Activity 3

_Links -- Accessible Forms_

### Using ARIA in Forms

Checkbox fields require a `<fieldset>` element with a `<legend>` element nested inside. `legend` is the prompt. The checkbox options are also nested inside the `fieldset`.

The `aria-required="true"` attribute \(nested inside `div.form-group > input`\). Can only use this in HTML5 with corresponding specific JavaScript.

## Activity 4

_Links -- Fancy Select Dropbox_

The `tabindex="0"` attribute makes any element focusable. The `tabindex="-1"` attribute will skip that element.

## Activity 5

_Links -- Custom Checkbox Toggle Switch_

It's actually a **checkbox** that's hidden on the page by the toggle element's overflow. Super cool!

## Activity 6

_Links -- Accordion_

Remember the value of JavaScript in implementing accessibility \(especially with buttons\).

## Activity 7

_Links -- Skip to Content_

Enables screen readers to skip over the menu links and just go to the content.

Put it as the first link -- Remember, the DOM order matters to screen readers!

## Activity 8

_Links -- Roving with_ `tabindex`

A user may have to tab through the entire site before they can get to a modal.

