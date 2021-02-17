
# Regular expressions
* Regular expressions are a language of their own.

* Usage Examples Extract emails from an old CSV address book.

* Extract image sources from HTML files.

* Extract proxies from online websites.

* Extract URL results from Google.


# CSS Grid Layout :
* excels at dividing a page into major regions or defining the relationship in terms of size, position, and layer, between parts of a control built from HTML primitives.
Like tables, grid layout enables an author to align elements into columns and rows. However, many more layouts are either possible or easier with CSS grid than they were with tables. For example, a grid container's child elements could position themselves so they actually overlap and layer, similar to CSS positioned elements.


![](https://miro.medium.com/max/840/1*kuzeYL058uQGHPt8_wuoqg.png)
## Grid, columns, and rows 
With CSS Grid, you’ll work with rows and columns and in this way produce a grid. Within the grid, individual objects can be arranged. This grid can or must be freely selected.

for Example 
.grid-one { display: grid;

grid-template-rows: 100px 100px;

grid-template-columns: 100px 100px 100px; }

# Flags
A regex usually comes within this form /abc/, where the search pattern is delimited by two slash characters /.
At the end we can specify a flag with these values (we can also combine them each other):
g (global) does not return after the first match, restarting the subsequent searches from the end of the previous match
m (multi-line) when enabled ^ and $ will match the start and end of a line, instead of the whole string
i (insensitive) makes the whole expression case-insensitive (for instance /aBc/i would match AbC).
