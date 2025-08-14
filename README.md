# Online Retail Transaction Dataset Project

In this project I aim to understand, analyse and manipulate the data. This is to better understand where the business is at currently, the customers, the products. Extracting useful text based and visual insights from this dataset is crucial as it will display where the business can improve and grow. Additionally, help make better informed business decisions aligning with the companies goals.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* The raw dataset consists of 8 columns and 541910 rows. The dataset lists out invoice numbers, stock codes, descriptions of products, quantities, invoice dates, unit prices, unique customer IDs and country. 


## Business Requirements
* To extract actionable insights from the dataset in order to enhance customer engagement, optimize product offerings, and drive strategic sales growth.


## Hypothesis and how to validate?
* Hypothesis one - the most popular products generate higher revenue during a particular season in the year, highlighting the importance of aligning inventory and marketing strategies with seasonal buying behavior.

I will validate this by identifying the popular products from the dataset and creating a chart where popular products are displayed over a period of time.

* Hypothesis two - The drive for the majority of the revenue comes from the contributions made by the top 10% of customers.

I will validate this by identify identifying the top 10% customers that contirbute towards revenue and plot an chart in comparison to another chart with the overall sales from all customers. 

* Hypothesis three - Quarter 4 of the year (Oct-Dec) has an increase on sales due to the seasonal holidays.

I will validate this by identifying the end of the year sales and comparing it to the other quarters of the year.

## Project Plan
Steps taken for analysis consists of:
* Loading the dataset and identifying what needs cleaning.
* Data cleaning to fill in empty cells and removing duplicate data. 
* Transformation with added feature for a clean dataset. 
* Analysis to get statistics and more understanding of the dataset.
* Visualisations to extract valuable insights

## The rationale to map the business requirements to the Data Visualisations
* my business requirement was "To extract actionable insights from the dataset in order to enhance customer engagement, optimize product offerings, and drive strategic sales growth." It is common in the retail industry to look at sales, seasonality, cusomters and their characteristics in spending and the products being bought. 

## Analysis techniques used
* researching and using the standard key metrics for an online retail industry, this helped reach my objectives and gain a better understanding on the dataset. 

* I structured the analysis around what a common retail industry would want to look at. Therefore giving me a basis of some sort of structure to go by, sales, products, customers etc.

* The dataset was not complicated, however within the description column, I noticed values such as "?" "lost" "damaged" "faulty". Ideally i wanted to remove these items but, it proved that there was alot of them. It was left in the dataset, however I checked the quantity on a small proportion of these on excel and they were 0 or below.

* Co-pilot helped with some bits of code where its suggesting lines of code or speeding up code writing with assumptions that i deemed correct to use. 

* ChatGPT was used for understanding of bits of code, particularly with plotly.

* *StackedOverFlow and Youtube was also used for code understanding and helped with code.

## Ethical considerations
* The dataset came from Kaggle and presumably would not have any legal or societal issues. There was no personal data within the dataset which could expose or identify any thing perosnal to a particular individual.

## Unfixed Bugs
* As previous mentioned, a proportion of data within the dataset under the description column containing values that did not match to product decriptions and may have been duplicates. However a small segment of this was checked to see if the quantities were in positive values or 0 and below. I would have liked to have more time in figuring out how i could remove those items, ideally not one by one, as there was a lot. 

* I tried to remove negative values from the boxplot chart by using the quantity column > 0, however this didnt seem to work. I did not have enough time to go back to it, and try find a solution.

* Knowledge gaps is a bit difficult to state, the course content is very new to me and feel as though I cant remember everything I have already gone through (fast paced course). However I did use the LMS quite a lot to go through particular sections I needed to use, mostly with visualisations. Also the use of some colleagues aiding me in some simple basics at the start was helpful. I did get a little confused with using VSCode as it is new to me, however I got the hang of it as time went on. If knowledge was missed, materials was used such as, LMS, StackedOverflow, Youtube, PlotlyCommunity, AI, facilitators and colleagues.


## Development Roadmap
* There was an issue with me plotting plotly charts in the notebook and obtaining the error of NBformat not installed. Essentially, i just wanted to see if the chart worked and by using StackedOverflow I was able to display it on the browser. I then contacted Vasi which I was advised to install NBformat in the terminal, reset the kernel and it still didnt seem to work. Vasi suggested installing it within the notebook, which eventually worked.

* General understanding around what i needed to do with the content I had already learned. content had been revisited to gain better understanding as well as using YouTube and AI.

* New skills or tools I plan to learn is mastering some what I already know, understanding VSCode more (first time user). I know dashboards was taken out of this project, so I expect this to be the next thing to learn as well as this being the next section on the LMS. 

## Main Data Analysis Libraries
* Pandas
* Numpy
* Seaborn
* Matplotlib
* Plotly


## Credits 
* LMS via Code Institute
* Google
* YouTube
* StackedOverflow
* GeeksForGeeks
* PlotlyCommunityForum
* Chat GPT
* Co-pilot
* Facilitators
* Colleagues



### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)
* Thank the people who provided support through this project.