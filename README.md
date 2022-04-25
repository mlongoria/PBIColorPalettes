# PBI Color Palettes
I created Power BI theme files to contain the colors of the viridis color palettes. In addition to being visually appealing, viridis color palettes are CVD (colorblind) friendly and perceptually uniform. These themes can be useful for sequential, diverging, or categorical color palettes by strategically choosing which colors (and shades) to include. For a quick explanation of these color palettes, see this [post about the colors in R on CRAN](https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html). For a much deeper explanation, read [this research article](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0199239). 

# Color Choices
I generated these palettes using the handy tool I found at https://waldyrious.net/viridis-palette-generator/. 

My process: 
1. Set the color palette generator to 10 categories. 
2. Use the middle 8 colors for the standard data colors in the theme. The third color from the bottom of the 10 is used as the first/main color in the theme to provide good color contrast from a light background. 
3. Set the color palette generator to 9 categories. 
4. Use the top color of the 9 as the maximum, the middle color of the 9 as the center, and the bottom color of the 9 as the minimum.  

# Import the Themes
To import a theme file into Power BI: 
1. Download the file. 
2. In Power BI Desktop, on the View tab, expand the Themes menu and select "Browse for themes". 
3. Select the file you downloaded. 

# Usage
Feel free to use these theme files and modify them any way you see fit. I just want to help people make better color choices in Power BI. You may want remove a couple of colors on either end to allow for "alert" colors to highlight certain data points. You might want to switch the first/main color depending on your background color. 

## Warnings
Because I don't know what background color you plan to use, I cannot guarantee that these colors have good color contrast. Please remember that you need a color contrast of at least 3:1 for non-text objects and 4.5:1 for text. For instance, if you use a white background with the Plasma theme, you would want to avoid using the bright yellow (#fdca26) color as it does not stand out enough from the white background. But if you were to use a dark gray background (#424242), the bright yellow would have very good contrast. So generally, if you use a dark background, you will want to use light/bright colors in your charts to provide good contrast. If you use a light background, you will want to use darker/bolder colors in your charts. 

# Issues and suggestions
If you have a suggestion for improvement, please log an issue here on this Github project. You can also find me on twitter [@mmarie](https://twitter.com/MMarie).
