# Portfolio image hero: my answers

## 1. Which image goes in the HTML, and why?
the content image in html,using an<img> tag with descriptive alt text.it carries real meaning (like a photo of your or a project screenshot)so it should be accessible to screen reader and indexable by search engines

## 2. Which image goes in the CSS, and why?
the decorative image such as a backround texture or hero backdrop.use backround-image,sinceit added no information and screen reader should skip it.

## 3. Which CSS property stops the content image from stretching?
(usually object-fit: cover ,or contains)typically paired with width 100% and height: auto or afixed height

## 4. Which element makes the boundary for the positioned label?
the nearset ancestors with position: relative, usually the hero wrappers.the label uses position: absolute znd is placed relative to that wrappers.

## 5. What did you do to keep the text easy to read?
I placed the text on a semi-transparent white card (rgba(255, 255, 255, 0.93)) with padding, so the background image doesn't show through the words. I also used dark, high-contrast text colors, a large heading size (2.75rem), and a comfortable line-height.
