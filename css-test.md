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
 
 # Line Wrap Formatting (with ZWNJ's) test
 
 This test uses the `Zero Width Non Joiner` character (`\u200C`) after the `A`'s, and two modified spaces before the `D`'s.
 
 ```css
#########  A:‌ B C
#########  ︎︎D E F
:###  ##:  A:‌ B C
:###  ##:  ︎︎D E F
`##. .##´  A:‌ B C
`##. .##´  ︎︎D E F
³#:. .:#³  A:‌ B C
³#:. .:#³ ︎︎ D E F
.#######.  A:‌ B C
.#######.  ︎︎D E F
 ```
