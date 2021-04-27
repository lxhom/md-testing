# Last Character (no Invis-chars) test

```css
######### A: B C
######### A: B C
:###  ##: A: B C
:###  ##: A: B C
`##. .##´ A: B C
`##. .##´ A: B C
³#:. .:#³ A: B C
³#:. .:#³ A: B C
.#######. A: B C
.#######. A: B C
 ```
 
# Last Character (with Modified Space) test

This test uses a Space with two `Variation Selector-15` modifiers (`\u0200\uFE0E\uFE0E`) before the `A`'s.

```css
######### ︎︎A: B C
######### ︎︎A: B C
:###  ##: ︎︎A: B C
:###  ##: ︎︎A: B C
`##. .##´ ︎︎A: B C
`##. .##´ ︎︎A: B C
³#:. .:#³ ︎︎A: B C
³#:. .:#³ ︎︎A: B C
.#######. ︎︎A: B C
.#######. ︎︎A: B C
 ```
 
 Same test again but without the `A`'s.
 
```css
######### ︎︎:B C
######### ︎︎:B C
:###  ##: ︎︎:B C
:###  ##: ︎︎:B C
`##. .##´ ︎︎:B C
`##. .##´ ︎︎:B C
³#:. .:#³ ︎︎:B C
³#:. .:#³ ︎︎:B C
.#######. ︎︎:B C
.#######. ︎︎:B C
 ```
 
 # Line Wrap Formatting (with ZWNJ's) test
 
 This test is the same as above, but it uses the `::` to make the text green.
 
 ```css
######### ︎︎A:: B C
######### ︎︎::B C
:###  ##: ︎︎A:: B C
:###  ##: ︎︎::B C
`##. .##´ ︎︎A:: B C
`##. .##´ ︎︎::B C
³#:. .:#³ ︎︎A:: B C
³#:. .:#³ ︎︎::B C
.#######. ︎︎A:: B C
.#######. ︎︎:: B C
 ```
