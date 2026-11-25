# Bootstrap landing page: my answers

## 1. Which Bootstrap classes did you use for the navbar?
navbar, navbar-expand-lg, bg-white, border-bottom, sticky-top, container, navbar-brand, navbar-toggler, navbar-toggler-icon, collapse, navbar-collapse, navbar-nav, nav-item, nav-link

## 2. Which value on the navbar button points to the menu?
data-bs-target="#lessonMenu". It matches the menu's id="lessonMenu".

## 3. Which grid classes changed the layout of the hero section?
row, align-items-center, g-4 and col-lg-6. On narrow screens the two columns stack, and on wide screens they sit side by side.

## 4. Which card classes did you use?
row, row-cols-1, row-cols-sm-2, col, card, h-100, card-body, card-title, card-text

## 5. Which styles did you put in `custom.css`, and not as Bootstrap utility classes in the HTML?
put the gradient background (.pattern-intro), the small uppercase label style (.lab-label), and the panel and card styling (.practice-panel, .topic-card) in custom.css, because Bootstrap utility classes can't make these custom designs
