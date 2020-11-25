# Toggle



### **About Toggle**

Toggles are a quick way to switch between on and off states. Similar to a physical light switch Toggles are used to turn something on/off instantly. The options are mutually exclusive and always have a default state, enabled or disabled.



### Usage 

When you need to provide a switch to turn something on or off (eg. Do you want odds in decimal or fractional?) 

If a physical switch would work for the action a toggle is the best option.

![Toggles structure](./media/toggle-usage.png)

**Use a toggle switch when:**

There are only 2 options to choose from, on or off. 

To make decisions or a preference such as settings or dialogs.



### **Structure**

A toggle consists of the following:

![Toggles structure](./media/toggle-struture.png)

1. **Toggle** **slot**- Area the toggle button sits into and slides in.
2. **Button**- the piece of the toggle which moves side to side.
3. **Label** -  use labels with a Toggle so the action is clear. Labels should be three words or less.



### Types

![Toggles structure](./media/toggle-variations.png)

1. **Primary** - Should be used most. Behaves like an on/off switch
2. **Secondary** - Use secondary when you are given two options to toggle between.



### Specs

![Toggles structure](./media/toggle-specs.png)



### Colour

Toggles use custom colour on three elements: the background (active state), the background (inactive state) and the button.

![toggle-colour1](./media/toggle-colour1.png)

| Element | Category              | Attribute                     | Value                                       |
| ------- | --------------------- | ----------------------------- | ------------------------------------------- |
| 1.      | Background (active)   | Token<br />Color<br />Opacity | $color-light-green-1<br />#31953e<br />100% |
| 2.      | Button                | Token<br />Color<br />Opacity | $color-white<br />#ffffff<br />100%         |
| 3.      | Background (inactive) | Token<br />Color<br />Opacity | $color-wood-ash<br />#D5D5D8<br />100%      |

![toggle-colour2](./media/toggle-colour2.png)

| Element | Category              | Attribute                     | Value                                       |
| ------- | --------------------- | ----------------------------- | ------------------------------------------- |
| 1.      | Background (active)   | Token<br />Color<br />Opacity | $color-white<br />#FFFFFF<br />100%         |
| 2.      | Background (inactive) | Token<br />Color<br />Opacity | $color-wood-ash<br />#D5D5D8<br />100%      |
| 3.      | Text active           | Token<br />Color<br />Opacity | $color-pigment-green<br />#009E51<br />100% |
| 4.      | Text inactive         | Token<br />Color<br />Opacity | $color-gun-powder<br />#474752<br />100%    |



### Typography

All toggles labels are set in sentence case and should not exceed three words. 

![toggle-colour1](./media/toggle-typography.png)

| Element | Category  | Attribute                                     | Value                                    |
| ------- | --------- | --------------------------------------------- | ---------------------------------------- |
| 1       | H300 Bold | Typeface<br />Font<br />Size<br />Line height | Roboto<br />Bold<br />14px<br />20px     |
| 2       | H300      | Typeface<br />Font<br />Size<br />Line height | Roboto <br />Regular<br />14px<br />20px |







