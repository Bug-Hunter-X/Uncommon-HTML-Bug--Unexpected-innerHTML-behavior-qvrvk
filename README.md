# Uncommon HTML Bug: Unexpected innerHTML behavior

This repository demonstrates an uncommon bug related to the usage of `innerHTML` in HTML.  The bug arises from an incorrect and inefficient method of appending content to an element.

## Bug Description

The provided HTML code attempts to append a new paragraph to an existing `div` element using `innerHTML`. While seemingly simple, this approach can lead to unpredictable behavior and performance issues, especially with larger or more complex content.  The issue lies in the way this code modifies the existing `innerHTML` directly.

## Bug Solution

The solution provided utilizes `insertAdjacentHTML`, a more robust and efficient way of adding content to elements.  This method minimizes potential issues associated with directly modifying the innerHTML property and offers better performance.

## How to reproduce
1. Clone this repository
2. Open `bug.html` in your web browser.