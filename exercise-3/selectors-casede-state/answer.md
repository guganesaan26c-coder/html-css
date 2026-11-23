# CSS selectors and which rule wins: my answers

## 1. When must you use a class selector, and not an element selector?
when some element of a type should be styled not all of them 

## 2. What does the space mean in `.material-shelf p`?
The selector .material-shelf p means: find each <The selects every p inside.material-shelf any depth   


## 3. What does `>` mean in `.quick-nav > a`?
selects only direct children.your instructor confirmed this one.there a stray> 

## 4. Why must a button link have a `:hover` style and a `:focus` style?
:hover shows mouse users that the link is interactive. :focus does the same for keyboard users who tab to it. Without both, one group can't tell where they are or that the link can be selected.

## 5. If `a` and `.quick-nav > a` both set `color` on a navigation link, which selector wins in the stylesheet of this lesson?`.quick-nav > a` wins. It has a class selector plus an element selector, so its specificity is higher than the plain element selector a, and its color is applied.
