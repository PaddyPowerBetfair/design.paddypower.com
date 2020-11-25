# Dropdown



### About 

Dropdown menus are a compact way to display a list of multiple options. They allow users to choose one option from a list of options.

###  

### Usage 

Use a dropdown menu when you need to give users a list of actions or links to choose from.

By default, selecting a menu item or clicking outside the menu dismisses the menu. You can change this behaviour to keep the menu open on item selection.

Place a descriptive label on the dropdown menu to clearly let users know what options are available.

This helps to keep the user focused on the task they’re trying to complete.

If a user needs to select a market, a good label would be “Select your first goalscorer” but something as simple as “First goalscorer” can also work.

Keep the text short and concise. Long menu items are truncated from the end and an ellipsis added.

![dropdown_struture](./media/dropdown_usage.png)



### Structure

![dropdown_struture](./media/dropdown_struture.png)

![dropdown_struture](./media/dropdown_struture_subheaders.png)

1. **Container** - contains a list section
2. **List section** - text label associated with the checkbox
3. **Arrow** - the arrow means interactivity and the state of the dropdown menu

4. **Menu** - container for links and action items 

5. **Subheader** -  used to separate different sections





### Behavior

![dropdown_struture](./media/dropdown_behavior_filled.png

![dropdown_struture](./media/dropdown_behavior.png)

Dropdown 

1. **Default** 
2. **Expanded** 
3. **Selected**



### Ordering the options

Options in a dropdown can be ordered in multiples ways. This includes but is not limited to: 

- Chronology

- Alphabet

- Popularity

- Location

- Category

Based on the context and relevance, options in a dropdown are ordered differently. Often multiple ordering systems are used together. For example, in the power nav content is ordered by date followed by alphabet.



### Specs

![dropdown_struture](./media/dropdown_specs.png)

**Note**: The outlined and filled dropdown have `border-radius:2px`. The menu shadow should be: `box-shadow: 0px 0px 3px 0px rgba(0,0,0,.5)`



### Colour

![dropdown_struture](./media/dropdown_colour.png)

| Element | Category         | Attribute                     | Value                                       |
| ------- | ---------------- | ----------------------------- | ------------------------------------------- |
| 1.      | Icon             | Token<br />Color<br />Opacity | $color-gun-powder<br />#474752<br />100%    |
| 2.      | Background       | Token<br />Color<br />Opacity | $color-white<br />#FFFFFF<br />100%         |
| 3.      | Text             | Token<br />Color<br />Opacity | $color-gun-powder<br />#474752<br />100%    |
| 4.      | Hover background | Token<br />Color<br />Opacity | $color-ghost-white<br />#f2f2f7<br />100%   |
| 5.      | Icon             | Token<br />Color<br />Opacity | $color-pigment-green<br />#3009E51<br />10% |
| 6.      | Divider          | Token<br />Color<br />Opacity | $color-ghost-white<br />#f2f2f7<br />100%   |



### Typography

![dropdown_struture](./media/dropdown_typography.png)

| Element  | Category | Attribute                                     | Value                                  |
| -------- | -------- | --------------------------------------------- | -------------------------------------- |
| 1. Label | H400     | Typeface<br />Font<br />Size<br />Line height | Roboto <br />Regular<br />16px<br />24 |
| 2. Label | H400     | Typeface<br />Font<br />Size<br />Line height | Roboto <br />Regular<br />16px<br />24 |
