# Responsive portfolio grid: my answers

## 1. Which element became the grid container?
Grid container the parent element that has display: grid,e.g..resource-grid.

## 2. Which elements became the grid items?
grid items:the direct children of that container,e.g. the .card or .resource-grid.elemets

## 3. Which rule makes the columns for wide screens?
Clear The grid-template-columns: repeat(3, 1fr); rule on .portfolio-grid. It makes 3 equal columns on wide screens.

## 4. Which rule changes the layout for a browser window of medium width?
The @media (max-width: 820px) rule. Inside it, grid-template-columns: repeat(2, 1fr); changes the grid to 2 columns

## 5. Which rule stops the featured card from making the phone layout too wide?
The @media (max-width: 560px) rule with .featured-card { grid-column: auto; }. The featured card spans 2 columns on wide screens, so on a phone it has to go back to 1 column.
