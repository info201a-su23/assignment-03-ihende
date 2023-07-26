# A2: U.S. COVID Trends

## Overview
In many ways, we have come to understand the gravity and trends in the COVID-19 pandemic through data. Regardless of media source, people are consuming more epidemiological information than ever, primarily through reported figures, charts, and maps.

This assignment is your opportunity to work directly with the same data used by the [New York Times](https://github.com/nytimes/covid-19-data/). While the analysis is guided through a series of questions, it is your opportunity to use programming skills to ask more detailed questions about the pandemic.

## Getting Started
You should start this assignment by opening up the `analysis.R` script. The script will guide you through an initial analysis of the data.

* **Coding prompts.** Complete the coding prompts in `analysis.R`. You MUST use the `dplyr` package.

* **Reflection prompts.** Throughout `analysis.R`, there are prompts labeled `"Reflection"`. Please write at least 1-3 sentences for each of these prompts below in this `README.md` file. As appropriate, provide evidence, give justification for your opinions, or genuinely reflect on your views. Please strive for concise, clear, and interesting writing.

## Reflection 1
Before actually calculating the total number of COVID cases and deaths, record your guesses for the following questions.

Guess: How many total COVID cases do you think there have been in the U.S.?

**50 million**

Guess: How many total COVID-related deaths do you think there have been in the U.S.?

**1.5 million**

Guess: Which state do you think has the highest number of COVID cases, and which state do you think has the lowest?

**Highest: New York**

**Lowest: Alaska**

## Reflection 2
Did the number of COVID cases and deaths surprise you? Why or why not? What about the states with the highest and lowest number of cases? How did your guesses line up with the actual results? Answer in at least 1-3 sentences

**I was surprised by the number of cases because I didn't realize about a third of the country has experienced COVID. I was not surprised by the number of deaths because I remember when the U.S. hit 1 million deaths around when COVID was on the decline. My guess for the state with the highest number of cases was correct, which isn't surprising because California is the most populated state. However, for the state with fewest cases I was wrong because I didn't consider U.S. territories.**

## Reflection 3
Which county has the highest number of cases in the state of Washington, and does it surprise you? Why or why not? (You may need to google this county to learn about it) Answer at least in 1-3 sentences

**Yakima County has the highest number of cases in the state of Washington. This did surprise me, because I thought it would be King County, where Seattle is located. I also thought this because that would mean King County is more densely populated. However, I understand that Yakima may have been more conservative when it came to COVID measures and vaccines.**

## Reflection 4
Why are there so many observations (counties) in the variable `lowest_deaths_in_each_state`? That is, wouldn't you expect the number to be around 50? Why is the number greater than 50? Answer in at least 1-3 sentences

**The dataframe "lowest_deaths_in_each_state" chooses the county with the lowest death from each state. But like I mentioned previously, this data also considers territories like American Samoa, so the number of observations will exceed just the 50 states.**

## Reflection 5
What do you think about the number and scale of the inconsistencies in the data? Does the fact that there are inconsistencies mean that people should not use this data? Why or why not? Answer in at least 1-3 sentences

**I am not surprised that there are some inconsistencies in the data, as estimating a total number of COVID cases for the whole country vs. for just one county probably has wildly different methodology. This data also includes large amounts of statistics and numbers on something that is hard to estimate. However, because of the size of the dataset I still think this is a valid source to use on COVID data as it still can capture general trends.**


## Reflection 6
Why were you interested in this particular question? Were you able to answer your question with code? What did you learn? Answer in at least 1-3 sentences

**While I could predict that there would be several answers, I was still interested in what my code would tell me. The lowest possible number of cases is 0, and there are certainly some counties without reported data or isolated communities that never encountered COVID. I learned that there are several counties that are considered "unknown" and I'm curious about that missing data.**

## Reflection 7
What, if anything, made you curious about this COVID analysis? What, if anything, surprised you? What might you do the same or differently on your next data wrangling project? Answer in at least 1-3 sentences

**This analysis made me curious about the trends between individual states/counties in terms of COVID cases and deaths. For example, when I learned Yakima County had the most COVID cases I was surprised, However, the more I thought about it the more I realized that Yakima County may have more republican leaders. COVID soon became a political issue and political divides became apparent in this way. Next time I do a data wrangling project, I'd try to find connections between the tables I'm making instead of viewing them individually (states vs. counties vs. national)**
