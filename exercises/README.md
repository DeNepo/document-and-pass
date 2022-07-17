<!-- BEGIN TITLE -->
# Document and Pass
<!-- END TITLE -->

<!-- BEGIN TOC -->
> 7/17/2022, 6:24:12 PM

- [0-hello-world](#0-hello-world)
- [1-remove-from-array](#1-remove-from-array)
- [1-repeat-string](#1-repeat-string)
- [1-reverse-string](#1-reverse-string)
- [1-sum-all](#1-sum-all)
- [2-fibonacci](#2-fibonacci)
- [2-get-the-titles](#2-get-the-titles)
- [2-leap-years](#2-leap-years)
- [2-palindromes](#2-palindromes)
- [3-caesar](#3-caesar)
- [3-find-the-oldest](#3-find-the-oldest)
- [3-pig-latin](#3-pig-latin)
- [3-snake-case](#3-snake-case)
<!-- END TOC -->

<!-- BEGIN DOCS -->
---

## [./0-hello-world](./0-hello-world)

<a name="hello"></a>

## hello(thing) ⇒ <code>string</code>
A very simple function, it greets whatever you tell it to


**Returns**: <code>string</code> - a friendly greeting  

| Param | Type | Description |
| --- | --- | --- |
| thing | <code>string</code> | the thing to greet |

**Example**  
```js
const greeting = hello('World');
console.log(greeting); // 'Hello, World!'
```
**Test Report**
```
7/17/2022, 6:24:12 PM

DEPRECATION: Jasmine#onComplete is deprecated. Instead of calling onComplete, set the Jasmine instance's exitOnCompletion property to false and use the promise returned from the execute method.
    at <Jasmine>
    at Jasmine.onComplete (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/jasmine.js:474:12)
    at testExercise (/home/runner/work/document-and-pass/document-and-pass/scripts/test.js:69:11)
    at Object.<anonymous> (/home/runner/work/document-and-pass/document-and-pass/scripts/test.js:91:1)
    at Module._compile (internal/modules/cjs/loader.js:1085:14)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:1114:10)
Note: This message will be shown only once. Set the verboseDeprecations config property to true to see every occurrence.
Started
.F..F.

Failures:
1) Hello says hello world
.    Expected '' to equal 'Hello, World!'..

2) Hello says hello toys
.    Expected '' to equal 'Hello, toys!'..

2 specs, 2 failures
Finished in 0.007 seconds

```

[TOP](#Document-and-Pass)


---

## [./1-remove-from-array](./1-remove-from-array)

<a name="removeFromArray"></a>

## removeFromArray()

**Test Report**
```
7/17/2022, 6:24:12 PM

DEPRECATION: Jasmine#onComplete is deprecated. Instead of calling onComplete, set the Jasmine instance's exitOnCompletion property to false and use the promise returned from the execute method.
    at <Jasmine>
    at Jasmine.onComplete (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/jasmine.js:474:12)
    at testExercise (/home/runner/work/document-and-pass/document-and-pass/scripts/test.js:69:11)
    at /home/runner/work/document-and-pass/document-and-pass/scripts/test.js:84:5
    at module.exports.jasmineDone (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/reporters/completion_reporter.js:21:5)
    at <Jasmine>
Note: This message will be shown only once. Set the verboseDeprecations config property to true to see every occurrence.
Started
.F..F..F..F..F..F..F.

Failures:
1) removeFromArray removes a single value
.    Expected undefined to equal [ 1, 2, 4 ]..

2) removeFromArray removes multiple values
.    Expected undefined to equal [ 1, 4 ]..

3) removeFromArray ignores non present values
.    Expected undefined to equal [ 1, 2, 3, 4 ]..

4) removeFromArray ignores non present values, but still works
.    Expected undefined to equal [ 1, 3, 4 ]..

5) removeFromArray can remove all values
.    Expected undefined to equal [  ]..

6) removeFromArray works with strings
.    Expected undefined to equal [ 2, 'ho' ]..

7) removeFromArray only removes same type
.    Expected undefined to equal [ 1, 2 ]..

7 specs, 7 failures
Finished in 0.007 seconds

```

[TOP](#Document-and-Pass)


---

## [./1-repeat-string](./1-repeat-string)

<a name="repeatString"></a>

## repeatString()

**Test Report**
```
7/17/2022, 6:24:12 PM

DEPRECATION: Jasmine#onComplete is deprecated. Instead of calling onComplete, set the Jasmine instance's exitOnCompletion property to false and use the promise returned from the execute method.
    at <Jasmine>
    at Jasmine.onComplete (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/jasmine.js:474:12)
    at testExercise (/home/runner/work/document-and-pass/document-and-pass/scripts/test.js:69:11)
    at /home/runner/work/document-and-pass/document-and-pass/scripts/test.js:84:5
    at module.exports.jasmineDone (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/reporters/completion_reporter.js:21:5)
    at <Jasmine>
Note: This message will be shown only once. Set the verboseDeprecations config property to true to see every occurrence.
Started
.F..F..F..F..F..F..F.

Failures:
1) repeatString repeats the string
.    Expected undefined to equal 'heyheyhey'..

2) repeatString repeats the string many times
.    Expected undefined to equal 'heyheyheyheyheyheyheyheyheyhey'..

3) repeatString repeats the string 1 times
.    Expected undefined to equal 'hey'..

4) repeatString repeats the string 0 times
.    Expected undefined to equal ''..

5) repeatString returns ERROR with negative numbers
.    Expected undefined to equal 'ERROR'..

6) repeatString repeats the string a random amount of times
.    TypeError: Cannot read property 'match' of undefined.

7) repeatString works with blank strings
.    Expected undefined to equal ''..

7 specs, 7 failures
Finished in 0.007 seconds

```

[TOP](#Document-and-Pass)


---

## [./1-reverse-string](./1-reverse-string)

<a name="reverseString"></a>

## reverseString()

**Test Report**
```
7/17/2022, 6:24:12 PM

DEPRECATION: Jasmine#onComplete is deprecated. Instead of calling onComplete, set the Jasmine instance's exitOnCompletion property to false and use the promise returned from the execute method.
    at <Jasmine>
    at Jasmine.onComplete (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/jasmine.js:474:12)
    at testExercise (/home/runner/work/document-and-pass/document-and-pass/scripts/test.js:69:11)
    at /home/runner/work/document-and-pass/document-and-pass/scripts/test.js:84:5
    at module.exports.jasmineDone (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/reporters/completion_reporter.js:21:5)
    at <Jasmine>
Note: This message will be shown only once. Set the verboseDeprecations config property to true to see every occurrence.
Started
.F..F..F..F.

Failures:
1) reverseString reverses single word
.    Expected undefined to equal 'olleh'..

2) reverseString reverses multiple words
.    Expected undefined to equal 'ereht olleh'..

3) reverseString works with numbers and punctuation
.    Expected undefined to equal '!cba !321'..

4) reverseString works with blank strings
.    Expected undefined to equal ''..

4 specs, 4 failures
Finished in 0.004 seconds

```

[TOP](#Document-and-Pass)


---

## [./1-sum-all](./1-sum-all)

<a name="sumAll"></a>

## sumAll()

**Test Report**
```
7/17/2022, 6:24:12 PM

DEPRECATION: Jasmine#onComplete is deprecated. Instead of calling onComplete, set the Jasmine instance's exitOnCompletion property to false and use the promise returned from the execute method.
    at <Jasmine>
    at Jasmine.onComplete (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/jasmine.js:474:12)
    at testExercise (/home/runner/work/document-and-pass/document-and-pass/scripts/test.js:69:11)
    at /home/runner/work/document-and-pass/document-and-pass/scripts/test.js:84:5
    at module.exports.jasmineDone (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/reporters/completion_reporter.js:21:5)
    at <Jasmine>
Note: This message will be shown only once. Set the verboseDeprecations config property to true to see every occurrence.
Started
.F..F..F..F..F..F.

Failures:
1) sumAll sums numbers within the range
.    Expected undefined to equal 10..

2) sumAll works with large numbers
.    Expected undefined to equal 8002000..

3) sumAll works with larger number first
.    Expected undefined to equal 7626..

4) sumAll returns ERROR with negative numbers
.    Expected undefined to equal 'ERROR'..

5) sumAll returns ERROR with non-number parameters
.    Expected undefined to equal 'ERROR'..

6) sumAll returns ERROR with non-number parameters
.    Expected undefined to equal 'ERROR'..

6 specs, 6 failures
Finished in 0.006 seconds

```

[TOP](#Document-and-Pass)


---

## [./2-fibonacci](./2-fibonacci)

<a name="fibonacci"></a>

## fibonacci()

**Test Report**
```
7/17/2022, 6:24:12 PM

DEPRECATION: Jasmine#onComplete is deprecated. Instead of calling onComplete, set the Jasmine instance's exitOnCompletion property to false and use the promise returned from the execute method.
    at <Jasmine>
    at Jasmine.onComplete (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/jasmine.js:474:12)
    at testExercise (/home/runner/work/document-and-pass/document-and-pass/scripts/test.js:69:11)
    at /home/runner/work/document-and-pass/document-and-pass/scripts/test.js:84:5
    at module.exports.jasmineDone (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/reporters/completion_reporter.js:21:5)
    at <Jasmine>
Note: This message will be shown only once. Set the verboseDeprecations config property to true to see every occurrence.
Started
.F..F..F..F..F..F..F..F..F.

Failures:
1) fibonacci works
.    Expected undefined to equal 3..

2) fibonacci works
.    Expected undefined to equal 8..

3) fibonacci works
.    Expected undefined to equal 55..

4) fibonacci works
.    Expected undefined to equal 610..

5) fibonacci works
.    Expected undefined to equal 75025..

6) fibonacci doesn't accept negatives
.    Expected undefined to equal 'OOPS'..

7) fibonacci DOES accept strings
.    Expected undefined to equal 1..

8) fibonacci DOES accept strings
.    Expected undefined to equal 1..

9) fibonacci DOES accept strings
.    Expected undefined to equal 21..

9 specs, 9 failures
Finished in 0.008 seconds

```

[TOP](#Document-and-Pass)


---

## [./2-get-the-titles](./2-get-the-titles)

<a name="getTheTitles"></a>

## getTheTitles()

**Test Report**
```
7/17/2022, 6:24:12 PM

DEPRECATION: Jasmine#onComplete is deprecated. Instead of calling onComplete, set the Jasmine instance's exitOnCompletion property to false and use the promise returned from the execute method.
    at <Jasmine>
    at Jasmine.onComplete (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/jasmine.js:474:12)
    at testExercise (/home/runner/work/document-and-pass/document-and-pass/scripts/test.js:69:11)
    at /home/runner/work/document-and-pass/document-and-pass/scripts/test.js:84:5
    at module.exports.jasmineDone (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/reporters/completion_reporter.js:21:5)
    at <Jasmine>
Note: This message will be shown only once. Set the verboseDeprecations config property to true to see every occurrence.
Started
.F.

Failures:
1) getTheTitles gets titles
.    Expected undefined to equal [ 'Book', 'Book2' ]..

1 spec, 1 failure
Finished in 0.001 seconds

```

[TOP](#Document-and-Pass)


---

## [./2-leap-years](./2-leap-years)

<a name="leapYears"></a>

## leapYears()

**Test Report**
```
7/17/2022, 6:24:12 PM

DEPRECATION: Jasmine#onComplete is deprecated. Instead of calling onComplete, set the Jasmine instance's exitOnCompletion property to false and use the promise returned from the execute method.
    at <Jasmine>
    at Jasmine.onComplete (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/jasmine.js:474:12)
    at testExercise (/home/runner/work/document-and-pass/document-and-pass/scripts/test.js:69:11)
    at /home/runner/work/document-and-pass/document-and-pass/scripts/test.js:84:5
    at module.exports.jasmineDone (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/reporters/completion_reporter.js:21:5)
    at <Jasmine>
Note: This message will be shown only once. Set the verboseDeprecations config property to true to see every occurrence.
Started
.F..F..F..F..F..F.

Failures:
1) leapYears works with non century years
.    Expected undefined to equal true..

2) leapYears works with non century years
.    Expected undefined to equal false..

3) leapYears works with ridiculously futuristic non century years
.    Expected undefined to equal true..

4) leapYears works with century years
.    Expected undefined to equal false..

5) leapYears works with century years
.    Expected undefined to equal true..

6) leapYears works with century years
.    Expected undefined to equal false..

6 specs, 6 failures
Finished in 0.006 seconds

```

[TOP](#Document-and-Pass)


---

## [./2-palindromes](./2-palindromes)

<a name="palindromes"></a>

## palindromes()

**Test Report**
```
7/17/2022, 6:24:12 PM

DEPRECATION: Jasmine#onComplete is deprecated. Instead of calling onComplete, set the Jasmine instance's exitOnCompletion property to false and use the promise returned from the execute method.
    at <Jasmine>
    at Jasmine.onComplete (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/jasmine.js:474:12)
    at testExercise (/home/runner/work/document-and-pass/document-and-pass/scripts/test.js:69:11)
    at /home/runner/work/document-and-pass/document-and-pass/scripts/test.js:84:5
    at module.exports.jasmineDone (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/reporters/completion_reporter.js:21:5)
    at <Jasmine>
Note: This message will be shown only once. Set the verboseDeprecations config property to true to see every occurrence.
Started
.F..F..F..F..F.

Failures:
1) palindromes works with single words
.    Expected undefined to equal true..

2) palindromes works with punctuation
.    Expected undefined to equal true..

3) palindromes works with multiple words
.    Expected undefined to equal true..

4) palindromes works with multiple words
.    Expected undefined to equal true..

5) palindromes doesn't just always return true
.    Expected undefined to equal false..

5 specs, 5 failures
Finished in 0.005 seconds

```

[TOP](#Document-and-Pass)


---

## [./3-caesar](./3-caesar)

<a name="caesar"></a>

## caesar()

**Test Report**
```
7/17/2022, 6:24:12 PM

DEPRECATION: Jasmine#onComplete is deprecated. Instead of calling onComplete, set the Jasmine instance's exitOnCompletion property to false and use the promise returned from the execute method.
    at <Jasmine>
    at Jasmine.onComplete (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/jasmine.js:474:12)
    at testExercise (/home/runner/work/document-and-pass/document-and-pass/scripts/test.js:69:11)
    at /home/runner/work/document-and-pass/document-and-pass/scripts/test.js:84:5
    at module.exports.jasmineDone (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/reporters/completion_reporter.js:21:5)
    at <Jasmine>
Note: This message will be shown only once. Set the verboseDeprecations config property to true to see every occurrence.
Started
.F..F..F..F..F..F..F.

Failures:
1) caesar works with single letters
.    Expected undefined to equal 'B'..

2) caesar works with words
.    Expected undefined to equal 'Bbb'..

3) caesar works with phrases
.    Expected undefined to equal 'Mjqqt, Btwqi!'..

4) caesar works with negative shift
.    Expected undefined to equal 'Hello, World!'..

5) caesar wraps
.    Expected undefined to equal 'A'..

6) caesar works with large shift factors
.    Expected undefined to equal 'Ebiil, Tloia!'..

7) caesar works with large negative shift factors
.    Expected undefined to equal 'Ebiil, Tloia!'..

7 specs, 7 failures
Finished in 0.005 seconds

```

[TOP](#Document-and-Pass)


---

## [./3-find-the-oldest](./3-find-the-oldest)

<a name="findTheOldest"></a>

## findTheOldest()

**Test Report**
```
7/17/2022, 6:24:12 PM

DEPRECATION: Jasmine#onComplete is deprecated. Instead of calling onComplete, set the Jasmine instance's exitOnCompletion property to false and use the promise returned from the execute method.
    at <Jasmine>
    at Jasmine.onComplete (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/jasmine.js:474:12)
    at testExercise (/home/runner/work/document-and-pass/document-and-pass/scripts/test.js:69:11)
    at /home/runner/work/document-and-pass/document-and-pass/scripts/test.js:84:5
    at module.exports.jasmineDone (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/reporters/completion_reporter.js:21:5)
    at <Jasmine>
Note: This message will be shown only once. Set the verboseDeprecations config property to true to see every occurrence.
Started
.F..F..F.

Failures:
1) findTheOldest finds the oldest person!
.    TypeError: Cannot read property 'name' of undefined.

2) findTheOldest finds the oldest person if someone is still living
.    TypeError: Cannot read property 'name' of undefined.

3) findTheOldest finds the oldest person if the OLDEST is still living
.    TypeError: Cannot read property 'name' of undefined.

3 specs, 3 failures
Finished in 0.002 seconds

```

[TOP](#Document-and-Pass)


---

## [./3-pig-latin](./3-pig-latin)

<a name="translate"></a>

## translate()

**Test Report**
```
7/17/2022, 6:24:12 PM

DEPRECATION: Jasmine#onComplete is deprecated. Instead of calling onComplete, set the Jasmine instance's exitOnCompletion property to false and use the promise returned from the execute method.
    at <Jasmine>
    at Jasmine.onComplete (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/jasmine.js:474:12)
    at testExercise (/home/runner/work/document-and-pass/document-and-pass/scripts/test.js:69:11)
    at /home/runner/work/document-and-pass/document-and-pass/scripts/test.js:84:5
    at module.exports.jasmineDone (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/reporters/completion_reporter.js:21:5)
    at <Jasmine>
Note: This message will be shown only once. Set the verboseDeprecations config property to true to see every occurrence.
Started
.F..F..F..F..F..F..F..F..F.

Failures:
1) #translate translates a word beginning with a vowel
.    Expected undefined to equal 'appleay'..

2) #translate translates a word beginning with a consonant
.    Expected undefined to equal 'ananabay'..

3) #translate translates a word beginning with two consonants
.    Expected undefined to equal 'errychay'..

4) #translate translates two words
.    Expected undefined to equal 'eatay iepay'..

5) #translate translates a word beginning with three consonants
.    Expected undefined to equal 'eethray'..

6) #translate counts "sch" as a single phoneme
.    Expected undefined to equal 'oolschay'..

7) #translate counts "qu" as a single phoneme
.    Expected undefined to equal 'ietquay'..

8) #translate counts "qu" as a consonant even when its preceded by a consonant
.    Expected undefined to equal 'aresquay'..

9) #translate translates many words
.    Expected undefined to equal 'ethay ickquay ownbray oxfay'..

9 specs, 9 failures
Finished in 0.008 seconds

```

[TOP](#Document-and-Pass)


---

## [./3-snake-case](./3-snake-case)

<a name="snakeCase"></a>

## snakeCase()

**Test Report**
```
7/17/2022, 6:24:12 PM

DEPRECATION: Jasmine#onComplete is deprecated. Instead of calling onComplete, set the Jasmine instance's exitOnCompletion property to false and use the promise returned from the execute method.
    at <Jasmine>
    at Jasmine.onComplete (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/jasmine.js:474:12)
    at testExercise (/home/runner/work/document-and-pass/document-and-pass/scripts/test.js:69:11)
    at /home/runner/work/document-and-pass/document-and-pass/scripts/test.js:84:5
    at module.exports.jasmineDone (/home/runner/work/document-and-pass/document-and-pass/node_modules/jasmine/lib/reporters/completion_reporter.js:21:5)
    at <Jasmine>
Note: This message will be shown only once. Set the verboseDeprecations config property to true to see every occurrence.
Started
.F..F..F..F..F..F.

Failures:
1) snakeCase works with simple lowercased phrases
.    Expected undefined to equal 'hello_world'..

2) snakeCase works with Caps and punctuation
.    Expected undefined to equal 'hello_world'..

3) snakeCase works with longer phrases
.    Expected undefined to equal 'this_is_the_song_that_never_ends'..

4) snakeCase works with camel case
.    Expected undefined to equal 'snake_case'..

5) snakeCase works with kebab case
.    Expected undefined to equal 'snake_case'..

6) snakeCase works with WTF case
.    Expected undefined to equal 'snake_case_is_awesome'..

6 specs, 6 failures
Finished in 0.007 seconds

```

[TOP](#Document-and-Pass)

<!-- END DOCS -->
