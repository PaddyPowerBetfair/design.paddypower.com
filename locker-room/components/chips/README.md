# Chips
## About Chips

Chips allow our users to make selection or filter content. Unlike buttons, this should be treated only to filter/treat information rather than providing a destination.


#### 

## Usage 

![ tab](./media/chips-usage.png)


### How to Use

- They should be compact, be careful of the content needs to be clear.

- They need to be relevant and have a clear relationship to the content they represent.

- Chips should make the task to sort content easier.

  

### How Not to Use

Chips are not buttons, so they should not bring you to another page/location.

#### 


## Structure

A Chip comprises the following:

![tab](./media/chips-struture.png)

1. **Icon** -  An area where you can add one icons.
2. **Container** -  Surrounds chip label, icon and title.
3. **Label** - This text label could be a counter or countdown.
4. **Title** - The textual label of the item. May be truncated if bigger than the % of space available.


## Types 

For standard cases like the in- play or virtuals, use the primary version.

![tab](./media/chips-variations.png)

1. **Primary** - Should be the most used. 
2. **Secondary** - Should be used on horse racing or greyounds next races.
#### 

## Specs

![tab](./media/chips-specs-primary.png)

When using the primary with counter, a `padding-right: 2px` and `padding-radius:2px`  needs to be added from the edge of the background

![tab](./media/chips-specs-primary-counter.png)

###### 

###### 

## Colour

![tab](./media/chips-colors-primary.png)

| Element | State  | Category   | Attribute               | Value                                             |
| ------- | ------ | ---------- | ----------------------- | ------------------------------------------------- |
| 1.      | Normal | Background | Color<br />Text-colour  | $color-white<br />\$color-gunpowder               |
| 2.      | Hover  | Background | Color<br />Text-colour  | $color-white<br />\$color-pigmentgreen            |
| 3.      | Active | Background | Color<br />Text-colour  | $color-pigmentgreen<br />\$color-white            |
| 4.      | Normal | Counter    | Colour<br />Text-colour | $color-ghostwhite<br />\$color-gunpowder<br />    |
| 4.      | Hover  | Counter    | Colour<br />Text-colour | $color-ghostwhite<br />\$color-pigmentgreen<br /> |
| 4.      | Active | Counter    | Colour<br />Text-colour | $color-white<br />\$color-pigmentgreen<br />      |

###### 

###### 

## Typography

![tab](./media/chips-typography.png)

| Element | Category | Attribute                                     | Value                                         |
| ------- | -------- | --------------------------------------------- | --------------------------------------------- |
| 1.      | H100     | Typeface<br />Font<br />Size<br />Line height | Roboto<br />Regular<br />11px<br />16px / 1.4 |
| 2.      | H100     | Typeface<br />Font<br />Size<br />Line height | Roboto<br />Regular<br />11px<br />16px / 1.4 |
| 3.      | H100     | Typeface<br />Font<br />Size<br />Line height | Roboto<br />Regular<br />11px<br />16px / 1.4 |
| 4.      | H100     | Typeface<br />Font<br />Size<br />Line height | Roboto<br />Bold<br />11px<br />16px / 1.4    |

#### 

## Live Component

In case you want to know more, you can find more information about the tabs on **[storybook](http://abacus.sct.dev.betfair/docs/#/)**.