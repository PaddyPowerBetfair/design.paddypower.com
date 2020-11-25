# Buttons



### About buttons

Buttons are used to trigger actions. There are a variety of different button styles applied throughout our products each used to represent a specific type of action.

The button label uses sentence case and are as short as possible, while clearly explaining what happens when the button is clicked.

Avoid using disabled buttons to prevent users from completing an intended action without providing an explanation as to why the button has been disabled.



### Usage 

 They are placed throughout the UI, in places like:

- Cards

- Forms

- Modals

- Sidebar

![primaryPallete](./media/button-usage.png)



### Structure

Buttons can contain a combination of a clear label and an icon while links are always text.

![primaryPallete](./media/button-struture.png)

1. **Container** - Is around a text label.   
2. **Main label** - Text that indicates the result of selecting the button.
4. **Secondary label** - Text that gives more detail about the main label.



### Types

![primaryPallete](./media/button-variations.png)

1. **Default button** - Default buttons have the highest emphasis and are used as the primary call to action on a page. Used in different places means the colour for the text and background often changes.
2. **Outlined button** - Use with a default button for actions that are less crucial such as "cancel". 
3. **Link button** - Link buttons are used to navigate to another page or to be on the footer of a card to show more or less information. The icon is optional and should be used on links that redirect to another page. 
4. **Icon button** - Use for actions that can be represented by an icon.
5. **Round button** - Round buttons are used to create a patternized group of actions and can have either text or an icon as a label representing the action.
6. **Square button** - Used when the main label is not enough to explain the action and needs some extra info.



### Specs

![primaryPallete](./media/buttons-specs.png)

![primaryPallete](./media/buttons-specs2.png)

![primaryPallete](./media/buttons-specs3.png)

**Note:** The default, outlined, icon and detail button have `border-radius:4px`. 



### Colour

##### Primary button

![primaryPallete](./media/button-color-primary.png)

| Element | Category | Attribute                             | Value                                           |
| ------- | -------- | ------------------------------------- | ----------------------------------------------- |
| 1.      | Normal   | Background<br />Color<br />Text-color | $color-pigment-green<br />#1BAA55<br />\$ffffff |
| 2.      | Hover    | Background<br />Color<br />Text-color | $color-pigment-jewel<br />#147C3E<br />\$ffffff |
| 3.      | Active   | Background<br />Color<br />Text-color | $color-pigment-jewel<br />#147C3E<br />\$ffffff |
| 5.      | Disable  | Background<br />Color<br />Text-color | $color-wood-ash<br />#D5D5D8<br />#888891       |



##### Secondary button

![primaryPallete](./media/button-color-secondary.png)

| Element | Category | Attribute                                         | Value                                                        |
| ------- | -------- | ------------------------------------------------- | ------------------------------------------------------------ |
| 1.      | Normal   | Background<br />color<br />Text-color<br />Border | $color-white"<br />#ffffff<br />#1BAA55<br />$color-pigment-green |
| 2.      | Hover    | Background<br />color<br />Text-color<br />Border | $color-panache"<br />#ffffff<br />#1BAA55<br />$color-pigment-green |
| 3.      | Active   | Background<br />color<br />Text-color<br />Border | $color-panache"<br />#ffffff<br />#1BAA55<br />$color-pigment-green |
| 5.      | Disable  | Background<br />Text-color<br />Border            | $color-wood-ash<br />#D5D5D8<br />#888891                    |



##### Round button

![primaryPallete](./media/button-color-round.png)

| Element | Category | Attribute                                   | Value                                                      |
| ------- | -------- | ------------------------------------------- | ---------------------------------------------------------- |
| 1.      | Normal   | Background<br />Border<br />Text/icon color | \$color-white<br />​\$color-wood-ash<br />​\$color-gunpowder |
| 2.      | Hover    | Background<br />Border<br />Text/icon color | \$color-panache<br />\$color-jewel<br />​\$color-jewel      |
| 3.      | Active   | Background<br />Border<br />Text/icon color | \$color-panache<br />\$color-jewel<br />\$color-jewel      |
| 4.      | Disable  | Background<br />Border<br />Text/icon color | \$color-white<br />\$​color-woodash<br />​\$color-woodash    |
| 5.      | Delete   | Background<br />Text/icon color             | \$color-red<br />\$color-white                             |



##### Square button

![primaryPallete](./media/button-color-detail.png)

| Element | Category | Attribute                  | Value                                        |
| ------- | -------- | -------------------------- | -------------------------------------------- |
| 1.      | Normal   | Background<br />Text-color | \$color-ghostwhite<br />​\$color-pigmentgreen |
| 2.      | Hover    | Background<br />Text-color | \$color-pigmentgreen<br />​​\$color-white      |
| 3.      | Active   | Background<br />Text-color | \$color-pigmentgreen<br />\$color-white      |
| 4.      | Disable  | Background<br />Text-color | \$color-ghost-white<br />​\$color-woodash     |



### Typography

![primaryPallete](./media/button-typography.png)

| Element | Category    | Attribute                                     | Value                                 |
| ------- | ----------- | --------------------------------------------- | ------------------------------------- |
| 1 & 2   | h300 bold   | Typeface<br />Font<br />Size<br />Line height | Roboto <br />Bold<br />16px<br />20px |
| 4       | Large Bold  | Typeface<br />Font<br />Size                  | Roboto <br />Bold<br />16px           |
| 5       | xLarge Bold | Typeface<br />Font<br />Size                  | Roboto<br />Bold<br />16px            |
| 5       | xSmall      | Typeface<br />Font<br />Size                  | Roboto<br />Regular<br />11px         |



### Interaction & transition

A loading animation is used when performing when computational or connections speeds are slow. They help to notify users that loading is underway. 

![primaryPallete](./media/button_anim.mp4)



### Live Component 

In case you want to know more, you can find more information about the button on **[storybook](http://abacus.app.betfair/docs/#/)**.
