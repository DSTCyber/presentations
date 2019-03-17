# Optimizing away JavaScript obfuscation

## Abstract

JavaScript code can be hard enough to read and understand, even when it’s been 
well engineered. Now imagine that you’re a malware analyst who needs to
understand some malicious JavaScript that has been purposefully obfuscated;
what do you do? One approach is to add instrumentation and do a dynamic
analysis, but in doing so we may miss important details. Another approach is to
perform a static analysis and try to undo the obfuscation. This talk is about
the latter, and explores how we can borrow techniques from compiler theory and
functional programming to build a deobfuscator for malicious JavaScript.

## Venue

[CSides Canberra](http://www.bsidesau.com.au/csides.html), August 2018

## Authors

* Adrian Herrera
