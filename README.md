# Uncommon HTML Error: Typo in getElementById

This repository demonstrates a subtle error that can occur in JavaScript when interacting with the HTML DOM.  The error is a simple typo in the `getElementById` function.

## The Bug

The `bug.html` file contains a typo in the JavaScript code.  Instead of `getElementById`, it uses `getElementByIdx`. This incorrect method will not throw an error but will simply fail to update the content of the div.

## The Solution

The `bugSolution.html` file corrects the typo and shows the correct way to update the div's content.

## How to reproduce

1. Clone this repo.
2. Open `bug.html` in your web browser.  Observe that the div remains empty.
3. Open `bugSolution.html` in your web browser. The div will now display the updated text.
