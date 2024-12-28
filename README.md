# JavaScript Loose Comparison Pitfalls with null and undefined

This repository demonstrates a common JavaScript error stemming from the loose comparison operators (==) when dealing with null and undefined values.  Loose comparison can lead to unexpected behavior when you intend to distinguish between null, undefined, and other falsy values like 0, NaN, and false.

The `bug.js` file contains the erroneous code.  The `bugSolution.js` file provides the corrected version using strict equality (===).