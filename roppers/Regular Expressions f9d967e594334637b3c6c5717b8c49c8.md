# Regular Expressions

## # Regular Expression

### Line Anchors ‘^’ and ’′ − − − − *Caret*()*orDollar*() metacharacters represents **start** and **end** of a line.

^sid - This will only find lines that will start with sid. sid$ - Find sid only at end of line. ^$ - finding empty lines.

## ### The Characters Class ‘[]’

Square brackets called Character Class.

Match the word *gray* but also find if it was spelled as *grey*

R.E => gr[ea]y

> Use of this [ ^ … ] instead of [ …. ] [ … ] => listing the characters you want to use. [ ^…. ] => listing the characters you don’t want to use.
> 

### The character class Metacharacter (’ - ’)

Dash( - ) indicates the range of characters.

[01234567890abcdefgiABCDEF] => [0-9a-iA-F]

## ### Matching any character with a Dot ( . )

The dot metacharacter is used for any character class that matches any character. The dot metacharacter is not a metacharacter when it’s inside of character class. The list of metacharacters is different inside and outside of character class.

## ### The Alternation Metacharacter ( | )

The pipe means **or**. The subexpressions are called alternatives.

## #### Matching Optional Items ( ? )

The question mark means **optional**. It is placed after a character that are allowed but not required at a certain point in an expression.

English => flavour American => flavor

R.E => flavou?r ==u is optional.==

### The Other quantifiers ( + *)

goal => go+al or goooooooooal(but not gal)

## #### The Interval Quantifiers *({})*

{min, max} => go { 1, 5 } al If nothing is present it’s { 0, 1 } #### The Escape Characters (  ) — The escape characters is used for their meaning like if you want to use ? in normal way use it like ?

## #### Using Parenthesis for Matching ( () )

Parenthesis are used to capture the characters that match the subexpression they surround.

https://( [^/]+ ) => Subexpression is [^/]+