String
==

## Airbnb

- Output list of strings representing a page of hostings given a list of CSV strings.
- Given a list of words, find the word pairs that when concatenated form a palindrome.
- Find the most efficient way to identify what character is out of place in a non-palindrome.
- Implement a simple regex parser which, given a string and a pattern, returns a boolean indicating whether the input matches the pattern. By simple, we mean that the regex can only contain special character: `*` (star), `.` (dot), `+` (plus). The star means that there will be zero or more of previous character in that place in the pattern. The dot means any character for that position. The plus means one or more of previous character in that place in the pattern.
- Find all words from a dictionary that are x edit distance away.

## Facebook

- Longest substring with `K` unique characters.
  - [Source](http://blog.gainlo.co/index.php/2016/04/12/find-the-longest-substring-with-k-unique-characters/)
- Given a set of random strings, write a function that returns a set that groups all the anagrams together.
  - [Source](http://blog.gainlo.co/index.php/2016/05/06/group-anagrams/)
- Given a string, find the longest substring without repeating characters. For example, for string `'abccdefgh'`, the longest substring is `'cdefgh'`.
  - [Source](http://blog.gainlo.co/index.php/2016/10/07/facebook-interview-longest-substring-without-repeating-characters/)
- Given a string, return the string with duplicate characters removed.
- How many string representations are there for an integer where `a->1, b->2, ... z->26`.
  - E.g. `126` can be `'az'` or `'abf'`.
- Write a function that receives a regular expression (allowed chars = from `'a'` to `'z'`, `'*'`, `'.'`) and a string containing lower case english alphabet characters and return `true` or `false` whether the string matches the regex.
  - E.g. `'ab*a'`, `'abbbbba'` => `true`.
  - E.g. `'ab*b.'`, `'aba'` => `true`.
  - E.g. `'abc*'`, `'acccc'` => `false`.
- Given a rectangular grid with letters, search if some word is in the grid.
- Given two strings representing integer numbers (`'123'` , `'30'`) return a string representing the sum of the two numbers: `'153'`.
- Given a really big file with a lots of Facebook posts, find the ten most-used words.
- A professor wants to see if two students have cheated when writing a paper. Design a function `hasCheated(String s1, String s2, int N)` that evaluates to `true` if two strings have a common substring of length `N`.
  - Follow up: Assume you don't have the possibility of using `String.contains()` and `String.substring()`. How would you implement this?
- Print all permutations of a given string.
- Parse a string containing numbers and `'+'`, `'-'` and parentheses. Evaluate the expression. `-2+(3-5)` should return `-4`.
- Output a substring with at most `K` unique characters.
  - E.g. `'aabc'` and `k` = 2 => `'aab'`.
- Ensure that there are a minimum of `N` dashes between any two of the same characters of a string.
  - E.g. `n = 2, string = 'ab-bcdecca'` => `'ab--bcdec--ca'`.
- Find the longest palindrome in a string.
- Give the count and the number following in the series.
  - E.g. `1122344`, next: `21221324`, next: `12112211121214`.
  - Count and say problem.
- Compress a string by grouping consecutive similar questions together:
  - E.g. `'aaabbbcc' => `'a3b3c2'`.
- You have a string consisting of open and closed parentheses, but parentheses may be imbalanced. Make the parentheses balanced and return the new string.
- Given a set of strings, return the smallest subset that contains prefixes for every string.
  - E.g. `['foo', 'foog', 'food', 'asdf']` => `['foo', 'asdf']`.
- Write a function that would return all the possible words generated when using a phone (pre-smartphone era) numpad to type.

## Google

- Given a dictionary and a word, find the minimum number of deletions needed on the word in order to make it a valid word.
  - [Source](http://blog.gainlo.co/index.php/2016/04/29/minimum-number-of-deletions-of-a-string/)
- How to check if a string contains an anagram of another string?
  - [Source](http://blog.gainlo.co/index.php/2016/04/08/if-a-string-contains-an-anagram-of-another-string/)

