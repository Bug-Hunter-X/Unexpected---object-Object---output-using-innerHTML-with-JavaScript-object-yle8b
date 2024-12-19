# Uncommon HTML Error: Unexpected '[object Object]' with innerHTML

This repository demonstrates a subtle error in HTML and JavaScript interaction when using `innerHTML` with a JavaScript object instead of a string.  The error results in the output '[object Object]' in the browser instead of the intended content of the object.

The bug is explained in detail, with a solution provided to fix the issue.

## Bug Report

The bug occurs when attempting to set the `innerHTML` property of an HTML element to a JavaScript object.

## Solution

The solution involves correctly converting the JavaScript object to a string before setting it as the `innerHTML` of the HTML element.  This can be done using JSON.stringify().