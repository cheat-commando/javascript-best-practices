Make it understandable
    Use short, camelCase names for variables

Avoid global variables

Comment as much as needed, but not more

Declare variable at the top

Declare objects and arrays with "const"

Use "===" for comparison instead of "=="

Don't omit the curly braces

Place scripts at the bottom of your web page; let everything else load first.

Declare variables outside the For statement

Do this (or something similar) to create a string rather than a For loop:
    var arr = ['item 1', 'item 2', 'item 3', ...];
    var list = '<ul><li>' + arr.join('</li><li>') + '</li></ul>';

Use Template Literals