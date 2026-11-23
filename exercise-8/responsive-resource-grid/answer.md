# CSS Grid and media queries: my answers

## 1. Which element is the grid container on this page?
The parent element that has display: grid, e.g. .resource-grid.

## 2. Which elements are the grid items?
The direct children of the grid container, e.g. the .resource-card elements.

## 3. What does `1fr` mean in this grid?
1fr means one fraction of the available space. repeat(3, 1fr) makes 3 columns of equal width that share the space equally.


## 4. Why does the highlighted card need a reset in the phone media query?
On wide screens the highlighted card spans 2 columns (grid-column: span 2). On a phone there is only 1 column, so it must be reset (grid-column: auto;). Otherwise it would force an extra column and make the layout too wide.

## 5. Why must you test the same page at more than one width of the browser window?
Because the layout changes at different widths through media queries. Testing at wide, medium and phone widths shows that each layout works and nothing breaks or overflows.

## 6. Which change did you make? What changed in the browser, and which CSS property or media query caused it?
I changed grid-template-columns inside @media (max-width: 600px) from 3 columns to 1 column. When I made the browser window narrower, the cards moved from 3 in a row to 1 per row, stacked on top of each other.
