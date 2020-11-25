# Subheader



### About subheader

A subheader is a secondary header that defines or separates sections containing related data. Subheaders are normally used to separate different sections in cards. There are two types of subheaders: **Subheader Primary** and **Subheader Secondary**.



### Usage 

Use subheader to separate subsections in cards to define or separate sections containing related data.

![subheader_usage](./media/subheader_usage.png)



### Structure

It should be used in cards, giving a clear understanding to what is beeing displayed in the different sections. 

![subheader_struture](./media/subheader_struture.png)

1. **Container** - Is around a text label.
2. **Signifier** - Placed on the left edge of the card to highlight the subheader. 
3. **Main label** - This refers to the title of the subheader.
4. **Secondary label** - This refers to the secondary label of the subheader

 

### Types 

There are two main subheader types:

![subheader_variants](./media/subheader_variants.png)

1. **Subheader primary** - Subheader primary have higher emphasis and are used as the primary subheaders to separate larger sections in cards. (ex: Today, Tomorrow, Monday).
2. **Subheader secondary** - Subheader Secondary with main label and between one and three secondary labels. Normally applied to competitions or markets.

**Note**: When applying a subheader secondary without a subheader primary, the main label and signifier should have the primary style.



### Specs

##### Subheader Primary

![subheader_specs](./media/subheader_specs_primary.png)

**Note**: When placing two ore more subtitles on top of each other, the bottom margin and divider is removed. 



##### Subheader Secondary

![subheader_specs](./media/subheader_specs_secondary.png)



### Colour

##### Subheader Primary

![subheaderprimary_color](./media/subheader_color_primary.png)

| Element | Category  | Attribute         | Value                       |
| ------- | --------- | ----------------- | --------------------------- |
| 1.      | Signifier | Color             | $color-manatee              |
| 2.      | Text      | Color             | $color-gunpowder            |
| 3.      | Divider   | Color<br />Border | $color-ghost-white<br />1px |

#####  

##### Subheader Secondary

![subheadersecondary_color](./media/subheader_color_secondary.png)

| Element | Category  | Attribute         | Value                       |
| ------- | --------- | ----------------- | --------------------------- |
| 1.      | Signifier | Token<br />Color  | $color-wood-ash             |
| 2.      | Text      | Color             | $color-manatee              |
| 3.      | Divider   | Color<br />Border | $color-ghost-white<br />1px |



### Typography

##### Subheader Primary

![subheaderprimary_typography](./media/subheader_typography_primary.png)

| Element | Category  | Attribute                                     | Value                                       |
| ------- | --------- | --------------------------------------------- | ------------------------------------------- |
| 1.      | H300 Bold | Typeface<br />Font<br />Size<br />Line height | Roboto <br />Bold<br />14px<br />20px / 1.4 |



##### Subheader Primary

![subheadersecondary_typography](./media/subheader_typography_secondary.png)

| Element | Category | Attribute                                     | Value                                          |
| ------- | -------- | --------------------------------------------- | ---------------------------------------------- |
| 1.      | H300     | Typeface<br />Font<br />Size<br />Line height | Roboto <br />Regular<br />14px<br />20px / 1.4 |



In case you want to know more, you can find more information about the accordions on **storybook** ( http://abacus.sct.dev.betfair/storybook/?path=/story/components-subheader--primary

In case you want to know more, you can find more information about the tabs on **[storybook](https://abacus.sct.dev.betfair/docs/#/components/subheader/)**.