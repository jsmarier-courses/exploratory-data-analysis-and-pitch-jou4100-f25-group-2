**Date**<br>
**Course Code & Course Name**<br>
**Luc Baisley; Claire Forest; Joyce; Naomie**<br>
**Presented to Jean-Sébastien Marier**<br>

# Exploratory Data Analysis (EDA) & Pitch

Use one hashtag symbol (`#`) to create a level 1 heading like this one.

## Foreword

hello For this assignment, you must extract data from a dataset provided by the instructor. You must then clean and analyze the data, create exploratory charts/visualizations, and find a potential story idea. Your assignment must clearly detail your process. You are expected to write about 1500-2000 words, and to include several screen captures showing the different steps you went through. Your assignment must be written with the Markdown format and submitted on GitHub Classroom.

I have been assigning different versions of this project to my digital journalism and data storytelling students for a few years now. Its structure was inspired by the main sections/chapters of [*The Data Journalism Handbook*](https://datajournalism.com/read/handbook/one/). This version was further inspired by the [Key Capabilities in Data Science](https://extendedlearning.ubc.ca/programs/key-capabilities-data-science) program offered by the University of British Columbia (UBC).

**Here are some useful resources for this assignment:**

* [GitHub's *Basic writing and formatting syntax* page](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [The template repository for this assignment in case you delete something by mistake](https://github.com/jsmarier/jou4100_jou4500_mpad2003_project2_template)

Did you notice how to create a hyperlink? In Markdown, we put the clickable text between square brackets and the actual URL between parentheses.

And to create an unordered list, we simply put a star (`*`) before each item.

## 1. Introduction

Hello

## 2. Getting Data

Use two hashtag symbols (`##`) to create a level 2 heading like this one.

To include a screen capture, use the sample code below. Your images should be saved in the same folder as your `.md` file.

![](import-screen-capture.png)<br>
*Figure 1: The "Import file" prompt on Google Sheets.*

**Here are examples of functions and lines of code put in grey boxes:**

1. If you name a function, put it between "angled" quotation marks like this: `IMPORTHTML`.
1. If you want to include the entire line of code, do the same thing, albeit with your entire code: `=IMPORTHTML("https://en.wikipedia.org/wiki/China"; "table", 5)`.
1. Alternatively, you can put your code in an independent box using the template below:

``` r
=IMPORTHTML("https://en.wikipedia.org/wiki/China"; "table", 5)
```
This also shows how to create an ordered list. Simply put `1.` before each item.

## 3. Understanding Data

### 3.1. VIMO Analysis

Use three hashtag symbols (`###`) to create a level 3 heading like this one. Please follow this template when it comes to level 1 and level 2 headings. However, you can use level 3 headings as you see fit.

Insert text here.

Support your claims by citing relevant sources. Please follow [APA guidelines for in-text citations](https://apastyle.apa.org/style-grammar-guidelines/citations).

**For example:**

As Cairo (2016) argues, a data visualization should be truthful...

### 3.2. Cleaning Data

Insert text here.

### 3.3. Exploratory Data Analysis (EDA)

The main purpose of this exploratory phase was to identify language trends across Ottawa’s 24 wards and determine whether bilingualism appears concentrated in certain regions. Using the **2021 Long Form Census on Ward Data** from the City of Ottawa, we focused on three key variables: the first official language spoken (English, French, English and French, or neither), the ward name, and population counts and percentages per language. These variables directly relate to our guiding question: could official language laws or local bilingual conditions influence the French-speaking population within each ward?

To establish a baseline, I built a pivot table showing the total and proportional breakdown of official-language groups for the entire City of Ottawa. Using the range A1:Z6 from the “First Official Language Spoken” sheet, I created a new pivot table, added “Characteristics” as rows, and “City of Ottawa” as values summarized by SUM. I then displayed the results as “% of grand total.” This table (Figure 1) confirmed that English speakers make up roughly four-fifths of Ottawa’s population, French speakers account for about one-seventh, and bilingual residents represent fewer than three per cent. This served as a control for ward-level comparisons.

To explore local variation, I created a second pivot table (Figure 2) calculating each ward’s percentage of French speakers relative to its total population using the formula (French / Total) * 100. This standardized measure allowed for direct comparisons among wards of different sizes. The results showed clear east-west asymmetry: the highest shares of French speakers were found in Orléans South-Navan (32.4%) and Orléans East-Cumberland (32.2%), while the lowest appeared in West Carleton-March (5.3%) and Rideau-Jock (5.8%).

I then visualized these results through two charts in Google Sheets. The first, **Percentage of French-Speaking Residents by Ward**, was a column chart that displayed the proportion of French speakers in each ward (Figure 3). For example, in Orléans East–Cumberland, 15,690 French speakers out of 48,680 residents produced a value of 32.2 per cent. The chart revealed a distinct spatial trend: French-speaking populations are heavily concentrated in the east, particularly near Orléans and the Ottawa-Gatineau corridor, while western suburban wards such as Kanata, Stittsville, and Barrhaven fall below seven per cent.

The second visualization, **Distribution of English and French Speakers by Ward**, used a stacked horizontal bar chart to show both groups within each ward (Figure 4). Each bar represented 100 per cent of a ward’s population, split between English and French portions. This layout highlighted the same geographic divide: east-end wards display a more balanced linguistic composition, while most others remain overwhelmingly anglophone. Citywide, English speakers represent roughly 82 per cent of residents and French speakers 14 per cent, consistent with the pivot results.

!![alt text](image-1.png)

*Figure 1: This pivot table shows the total and proportional breakdown of official-language groups for the entire City of Ottawa*

![alt text](image-2.png)

*Figure 2: This pivot table shows each ward’s percentage of French speakers relative to its total population*

![alt text](image-3.png)

*Figure 3: This exploratory chart displays the proportion of French speakers in each ward*

![alt text](image-4.png)

*Figure 4: This exploratory chart shows the distribution of English and French speakers by ward*

## 4. Potential Story

Insert text here.

## 5. Conclusion

Insert text here.

## 6. References

Include a list of your references here. Please follow [APA guidelines for references](https://apastyle.apa.org/style-grammar-guidelines/references). Hanging paragraphs aren't required though.

**Here's an example:**

Bounegru, L., & Gray, J. (Eds.). (2021). *The Data Journalism Handbook 2: Towards A Critical Data Practice*. Amsterdam University Press. [https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153](https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153)
