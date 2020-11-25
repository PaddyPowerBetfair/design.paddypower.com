# Bet Button



## About Bet button

Bet buttons allow users to place a bet. They are the starting point for making a selection and when clicked add a desired selection to the betslip.

A button contains a numeric label representing the odds. The odds are expressed as a pair of numbers as fractions (e.g. 4/1) or a single number as decimals (e.g. 5.0) depending on the users preference.  



## Usage 

Bet buttons communicate the price of anything that can be bet on. They are used to tell users the odds associated with a selection in any given match/game/event and act as the primary call to action for bet placement.

![primaryPallete](media/bet-button-usage.png)



## Structure

Bet Buttons are composed of two elements:

![primaryPallete](media/bet-button-struture.png)

1. **Container** - space around the label.   
2. **Numeric Label** - the odds which describe the ratio of pay-out to stake



## Types



![primaryPallete](media/bet-button-variations.png)

1. **Bet Button** - default state of odds for any selection
2. **Bet Button Price Up** - use when the odds for a selection increase
3. **Bet Button Price Down** - use when the odds for a selection decrease
4. **Bet Button PowerPrice** - use to signify increased value for a selection
5. **Bet Button Disabled** - use to indicate a suspended or discontinued selection



## Specs

![primaryPallete](media/bet-button-specs.png)



## Colour

### Bet Button

![primaryPallete](media/bet-button.png)

| Element | Category | Attribute                               | Value                                          |
| ------- | -------- | --------------------------------------- | ---------------------------------------------- |
| 1.      | Normal   | Background<br />Colour<br />Text-colour | $color-ghost-white<br />#F2F2F7<br />#1BAA55   |
| 2.      | Hover    | Background<br />Colour<br />Text-colour | $color-panache<br />#EAF7EF<br />#1BAA55       |
| 3.      | Active   | Background<br />Colour<br />Text-colour | $color-pigment-green<br />#1BAA55<br />#ffffff |
| 4.      | Disable  | Background<br />Colour<br />Icon Colour | $color-ghost-white<br />#F2F2F7<br />#73737D   |



### Bet Button Price Up

![primaryPallete](media/bet-button-odds-up.png)

| Element | Category | Attribute                                                    | Value                                                        |
| ------- | -------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1.      | Normal   | Background<br />Colour<br />Text-colour<br/ >Overlay<br/ >Opacity | $color-ghost-white<br />#F2F2F7<br />#1BAA55<br />#000000<br />15% |
| 2.      | Active   | Background<br />Colour<br />Text-colour<br/ >Overlay<br/ >Opacity | $color-pigment-green<br />#1BAA55<br />#ffffff<br />#000000<br />15% |
| 3.      | Disable  | Background<br />Colour<br />Icon Colour                      | $color-ghost-white<br />#F2F2F7<br />#73737D                 |



### Bet Button Price Down

![primaryPallete](media/bet-button-odds-down.png)

| Element | Category | Attribute                                                    | Value                                                        |
| ------- | -------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 1.      | Normal   | Background<br />Colour<br />Text-colour<br/ >Overlay<br/ >Opacity | $color-ghost-white<br />#F2F2F7<br />#1BAA55<br />#000000<br />15% |
| 2.      | Active   | Background<br />Colour<br />Text-colour<br/ >Overlay<br/ >Opacity | $color-pigment-green<br />#1BAA55<br />#ffffff<br />#000000<br />15% |
| 3.      | Disable  | Background<br />Colour<br />Icon Colour                      | $color-ghost-white<br />#F2F2F7<br />#73737D                 |



### Bet Button PowerPrice

![primaryPallete](media/bet-button-power-price.png)

| Element | Category | Attribute                               | Value                                        |
| ------- | -------- | --------------------------------------- | -------------------------------------------- |
| 1.      | Normal   | Background<br />Colour<br />Text-colour | $color-yellow<br />#FCE300<br />#474752      |
| 2.      | Hover    | Background<br />Colour<br />Text-colour | $color-lemon<br />#FDF399<br />#474752       |
| 3.      | Active   | Background<br />Colour<br />Text-colour | $color-gun-powder<br />#474752<br />#FCE300  |
| 4.      | Disable  | Background<br />Colour<br />Icon Colour | $color-ghost-white<br />#F2F2F7<br />#73737D |



## Typography

![primaryPallete](media/bet-button-typography.png)

| Element     | Category  | Attribute                                     | Value                                       |
| ----------- | --------- | --------------------------------------------- | ------------------------------------------- |
| 1, 2, 3 & 4 | h400 bold | Typeface<br />Font<br />Size<br />Line height | Roboto <br />Bold<br />14px<br />24px / 1.5 |



## Interaction & transition

When the odds increase or decrease an animation indicates a change in odds and button style. The button changes from **Bet Button** to **Bet Button Price Up** or **Bet Button Price Down**. This signifier is used to notify users of changes. After 4 seconds it fades out and rolls back to the normal bet button colour.

![primaryPallete](media/normal.mp4)

## Live Component 

In case you want to know more, you can find more information about the accordions on **[storybook](http://abacus.sct.dev.betfair/docs/#/)**.	
