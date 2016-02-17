#!/usr/bin/env node
var n1 = process.argv[3];
    n2 = process.argv[4];
var operator = process.argv[2];    
if (operator == 'add') {console.log (parseFloat(n1) + parseFloat(n2));}
if (operator == 'subtract') {console.log(n1 - n2);}
if (operator == 'multiply') {console.log(n1 * n2);}
if (operator == 'divide') {console.log(n1 / n2);}
