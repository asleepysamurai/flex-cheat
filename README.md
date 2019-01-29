### flex-cheat - Easy cheat classes for common CSS flexbox layouts.

CSS stylesheet which provides the following basic classes:

- `flex-container`: Marks an item as a `display:flex` and all it's immediate children as fixed width i.e. both flex-grow and flex-shrink set to 0.
- `flex-container.column`: `flex-container` + sets `flex-direction` to column.
- `flex-container.inline`: `flex-container` but sets display to `flex-inline` instead of `flex`.
- `flex-container.center`: `flex-container` + centers direct child elements using `align-items`.
- `flex-container.column.center`: `flex-container.column` + centers direct child elements using `justify-content`.
- `flex-rest`: To be added to specific direct child elements, to allow them to take up the rest of available space. When multiple child elements are marked as `flex-rest` they share remaining space equally. Components marked `flex-rest` will grow and shrink as required.

You can see all these style declarations in `flex-cheat.css`. That will also be the single file required to be imported into your application.

#### That's it? Just six classes?

Yes, that's all there is to it. However, do not mistake the simplicity for impotence. By combining these six classes, we can come up with a myriad of layouts.

- Fixed Width Row: ![Fixed Width Row](/img/row.png)
- Equal Width Row: ![Equal Width Row](/img/row-equal-width.png)
- Mixed Width Row: ![Mixed Width Row](/img/row-mix-width.png)
- Fixed Centered Row: ![Fixed Centered Row](/img/row-center.png)
- Fixed Centered With Mixed Width Row: ![Fixed Centered With Mixed Width Row](/img/row-mix-width-center.png)
- Fixed Height Column: ![Fixed Height Column](/img/column.png)
- Equal Height Column: ![Equal Height Column](/img/column-equal-height.png)
- Mixed Height Column: ![Mixed Height Column](/img/column-mix-height.png)
- Fixed Centered Column: ![Fixed Centered Column](/img/column-center.png)
- Fixed Centered With Mixed Height Column: ![Fixed Centered With Mixed Height Column](/img/column-mix-height-center.png)
- Grid With Mixed Rows and Columns: ![Grid With Mixed Rows and Columns](/img/grid.html)

The code for these examples can be found in the `examples` directory.

Deceptively simple eh?
