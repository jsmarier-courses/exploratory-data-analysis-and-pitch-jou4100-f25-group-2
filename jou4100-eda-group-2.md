**6 November 2025**<br>
**CMN4100: Special Issues**<br>
**Luc Baisley; Claire Forest; Joyce; Naomie**<br>
**Presented to Jean-Sébastien Marier**<br>

# Exploratory Data Analysis (EDA) & Pitch
## 1. Introduction

- Joyce

## 2. Getting Data

- Joyce 

## 3. Understanding Data
### 3.1. VIMO Analysis

Our group conducted a VIMO analysis based on our hypothesis of “Could official language laws in each ward affect the French population?” drawn from our isolated data within the larger dataset from the City of Ottawa’s 2021 long-form Census ward data. Our dataset presents the first official language spoken for the population in private households; English, French, both, or neither, based on the different city wards.

Since the original dataset is from Statistics Canada’s official Census, it ensures a high level of accuracy and reliability. Internally, the data seemed consistent, with the total of each category equaling the Total column for each ward. This consistency affirms that the dataset is accurately representative of the variable used, while also supporting the overall validity of the dataset. As our group first looked over the dataset, we saw no clear invalid entries. However, our group made sure to double-check the totals for each language group, as this is where we viewed the greatest risk of invalid entries. Confirming that the number of individuals from each row did not exceed the total population, and by utilising the Google Sheets =SUM formula, we were able to confirm that our first view of the dataset was correct. Along with our own validation, knowing that the dataset came from the City of Ottawa and is based on official census data, not something manually typed by individuals, it is unlikely to have random errors or even made-up values.

There were few or no blanks in the dataset, and if there were, they were likely due to unavailable information rather than a mistake. Although these blanks do not significantly change or affect any of our analysis or findings, they should still be noted, especially if any values were to be turned into percentages. Any outliers within the dataset were expected due to Ottawa’s bilingual demographic. While some wards showed higher or lower proportions of French or bilingual speakers, these fluctuations were treated as meaningful rather than abnormal, ensuring that we are viewing them as geographical differences rather than an issue with the data's quality.

From this analysis, we can draw the conclusion that the data is valid, comes from reliable sources, and does not have any major errors, meaning we can confidently use it for the following stages of our analysis.

### 3.2. Cleaning Data

When performing the cleaning data portion of the Exploratory Data Analysis, our team focused this step around the topic of our hypothesis, “Could official language laws in each ward affect the French population?”. The goal of this step was to prepare the data for analysis by ensuring that formatting was consistent and that any new dataset we were creating was structured in a clear and organized way for easier interpretation, not only for our team but for outside readers looking at our results.

The first step performed in this data cleaning process was removing the extra white spaces that were either within or around cell entries. When doing this, we used Google Sheets data cleaning tools; Data → Data cleanup → Trim whitespace to clean hidden spaces in the characteristics column. By performing this cleanup step, it ensured consistency if we used filters or formulas later. After performing the trim whitespaces tool, it was evident that the values now appear consistent across all rows, minimizing the possibility of mismatched categories. 

Next, we isolated the data relevant to our hypothesis from the original dataset by creating a new sheet that only consisted of rows and columns specific to “First official language spoken for the population in private households”. This included copying only relevant rows, such as rows 432 to 436, excluding the rest of the unrelated information from the census sheet. This made the dataset easier to manage and prepared it for analysis without unrelated information cluttering the view.

Finally, we tried to check and remove any duplicates using Google Sheets; Data → Data cleanup → Remove duplicates. However, the dataset did not contain any duplicate rows. Although this step turned out not to be required, confirming that there were no duplicates helped establish the dataset’s integrity, in turn aiding in future parts of our analysis.

By trimming whitespace, isolating relevant data, and ensuring there were no duplicates, we made sure that our new data set, “First Official Language Spoken,” was clean, consistent, and ready for future analysis. These steps improved both the readability and the accuracy while keeping the original dataset’s reliability.

### 3.3. Exploratory Data Analysis (EDA)

The main purpose of this exploratory phase was to identify language trends across Ottawa’s 24 wards and determine whether bilingualism appears concentrated in certain regions. Using the **2021 Long Form Census on Ward Data** from the City of Ottawa, we focused on three key variables: the first official language spoken (English, French, English and French, or neither), the ward name, and population counts and percentages per language. These variables directly relate to our guiding question: could official language laws or local bilingual conditions influence the French-speaking population within each ward?

To establish a baseline, I built a pivot table showing the total and proportional breakdown of official-language groups for the entire City of Ottawa. Using the range A1:Z6 from the “First Official Language Spoken” sheet, I created a new pivot table, added “Characteristics” as rows, and “City of Ottawa” as values summarized by SUM. I then displayed the results as “% of grand total.” This table (see Figure 1 below) confirmed that English speakers make up roughly four-fifths of Ottawa’s population, French speakers account for about one-seventh, and bilingual residents represent fewer than three per cent. This served as a control for ward-level comparisons.

!![alt text](image-1.png)

*Figure 1: (Above) This pivot table shows the total and proportional breakdown of official-language groups for the entire City of Ottawa*

To explore local variation, I created a second pivot table (see Figure 2 below) calculating each ward’s percentage of French speakers relative to its total population using the formula (French / Total) * 100. This standardized measure allowed for direct comparisons among wards of different sizes. The results showed clear east-west asymmetry: the highest shares of French speakers were found in Orléans South-Navan (32.4%) and Orléans East-Cumberland (32.2%), while the lowest appeared in West Carleton-March (5.3%) and Rideau-Jock (5.8%).

![alt text](image-2.png)

*Figure 2: (Above) This pivot table shows each ward’s percentage of French speakers relative to its total population*

I then visualized these results through two charts in Google Sheets. The first, **Percentage of French-Speaking Residents by Ward**, was a column chart that displayed the proportion of French speakers in each ward (see Figure 3 below). For example, in Orléans East–Cumberland, 15,690 French speakers out of 48,680 residents produced a value of 32.2 per cent. The chart revealed a distinct spatial trend: French-speaking populations are heavily concentrated in the east, particularly near Orléans and the Ottawa-Gatineau corridor, while western suburban wards such as Kanata, Stittsville, and Barrhaven fall below seven per cent.

![alt text](image-3.png)

*Figure 3: (Above) This exploratory chart displays the proportion of French speakers in each ward*

The second visualization, **Distribution of English and French Speakers by Ward**, used a stacked horizontal bar chart to show both groups within each ward (see Figure 4 below). Each bar represented 100 per cent of a ward’s population, split between English and French portions. This layout highlighted the same geographic divide: east-end wards display a more balanced linguistic composition, while most others remain overwhelmingly anglophone. Citywide, English speakers represent roughly 82 per cent of residents and French speakers 14 per cent, consistent with the pivot results.

![alt text](image-4.png)

*Figure 4: (Above) This exploratory chart shows the distribution of English and French speakers by ward*

## 4. Potential Story

- Naomie

## 5. Conclusion

- Naomie

## 6. References

Bounegru, L., & Gray, J. (Eds.). (2021). *The Data Journalism Handbook 2: Towards A Critical Data Practice*. Amsterdam University Press. [https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153](https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153)
