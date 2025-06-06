# Ji Shi_540114366_Quiz-8
## Technique Inspiration
My inspiration comes from an arcade game called Battle City, where the game map is also made up of regular squares, with tanks, obstacles, bases and other elements distributed in these squares. It is very similar to the grid layout constructed with color blocks and lines in Mondrian's works.

![An image of Battle city](https://static.tvtropes.org/pmwiki/pub/images/battle_city.jpg)

The colors used by Mondrian in his works are very vivid and bright. He mainly uses three primary colors: red, yellow, and blue. It reminds me that most of Google's app logo designs also use this color palette.

![An image of Google apps logo design](https://t4.ftcdn.net/jpg/05/89/22/37/240_F_589223719_UYrXFIOsMxs3RRMnxqIQIiUvkmPuDLnG.jpg)

## Coding Technique
My idea is to first draw 10 thick horizontal and vertical lines, but randomly place them on the canvas, then divide these lines into squares of different colors, and finally draw 20 rectangles of limited size that appear randomly in the entire picture.
I want to use random(colors, weights) to set a weight for each color, so that I can assign colors to color blocks according to the set probability.

![An gif of random color design](https://happycoding.io/tutorials/p5js/images/random-29.gif)
