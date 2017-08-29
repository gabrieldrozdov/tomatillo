# Hello!
*Tomatillo* is a responsive multimedia Bootstrap portfolio template that I made for my personal website. The template displays a series of thumbnails (implemented as columns) and allows for sorting via type.

## Design
My implementation doesn't hide portfolio items when sorting. Since I work with a variety of art forms, I want my portfolio to emphasize what my current area of focus is. Thus, *Tomatillo* dims and greys filtered items without hiding them, which provides a visual representation of a timeline of work.

*Tomatillo* also utilizes subtle animations to make the grid-based format more interesting. Each portfolio element features hover and active animations, which paired with the colored column backgrounds creates the façade of a color overlay (which will be implemented at a later date).

In the current build, *Tomatillo* uses the stock Bootstrap v4.0.0-beta CSS and Javascript files, while all custom CSS and Javascript is contained in the index.html file.

## Features

- Responsive column-based design
- Interactive elements with subtle animations
- Sorting by item type
- Dropdown sorting menu
- Contact and résumé links
- Social media profile links


## Glitches

- Sortable categories are still clickable when navbar is closed
- Sortable categories row should be hidden when navbar is closed
- Portfolio items' shadows are covered by white borders


## Planned Changes

- Color+text overlays for portfolio items
- Better implementation of social media account links (currently at bottom of page, should be at top)
- Better code optimization
- Action box for portfolio items (currently, items only link away from page)
- Auto-hiding navbar
