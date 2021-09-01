# data-portfolio

Here you can view projects that I've completed.

### Sales Analysis for Permits.com

Permits.com provides a one-stop shop for getting building permits and the like for commercial and residential properties. We were tasked with analyzing almost 5 years' worth of sales data to help them determine how best to deploy online ads.  We took into account a number of dimensions, including user type, company, task type (what the permit was for), location, date and value of the actual project.

Deliverables included a multi-page interactive dashboard that provided deep dives into all aspects of the sales that can help them target specific companies, locations, task types, etc. This information can further be correlated with website traffic for even more granular analysis.

A version of the dashboard (using anonymized data) can be see [here](https://www.wongworks.com/portfolio)

### Game Review Analysis for Allcorrect Games

Analyzed anonymized game reviews with over 12 million rows, in multiple languages. Purpose was to determine reviews on localization, correlate them with overall reviews, and determine algorithm for selecting most promising games as candidates for client's localization services. Data cleaning tasks included concatenating multiple Excel sheets from two notebooks (including misnamed columns), filtering for localization, detecting language, translating and tokenizing reviews, running sentiment analysis, and corroborate preliminary results with real-world business data before determining game selection algorithm. Notebook not available due to NDA.

## NOTE: Notebooks will be rendered in NBViewer as there have been issues rendering on Github

### [E-Commerce Final Project](https://nbviewer.jupyter.org/github/dwongster/data-portfolio/blob/main/e_commerce_final_project_accepted_cleaned.ipynb)

Analysis of a report of sales transactions for an e-commerce site.  We were given dataset of about half million transactions that appear to come from a wholesaler of some type.  I wrote custom functions to help clean the data, including switching variable names from camelCased to snake_cased, analyzing nulls as percentages of whole (as a way to help determine whether to delete). I had to account for outliers and duplicates before analyzing the range of products that were sold to see what items sold the best, what type of customers were most profitable, and any other type of insights.

### [Churn analysis project](https://nbviewer.jupyter.org/github/dwongster/data-portfolio/blob/main/churn_analysis_project_accepted_cleaned.ipynb)

Analyze the factors that impact churn most and draw basic conclusions and develop recommendations on how to improve customer service.

### [Event based Funnel analysis](https://nbviewer.jupyter.org/github/dwongster/data-portfolio/blob/main/event_based_funnel_analysis.ipynb)

Analysis of a font change on website to see if sales changed significantly.  We compared groups and their event based funnels to determine whether a font change resulted in positive sales difference.

### [AB Testing analysis project](https://nbviewer.jupyter.org/github/dwongster/data-portfolio/blob/main/AB_testing_project_accepted_cleaned.ipynb)

Analysis of an AB test in an online store.

### [Video Games Sales project](https://nbviewer.jupyter.org/github/dwongster/data-portfolio/blob/main/video_game_sales_project_accepted_cleaned.ipynb)

Analysis of console game sales through 2016.  This was an interesting project where I was able to utilize my own intimate knowledge of early game consoles with analyses of the sales data to provide a (hopefully) insightful breakdown.

### [Murder Myster Note with text analysis](https://nbviewer.jupyter.org/github/dwongster/data-portfolio/blob/main/analyzing_murder_mystery_note_with_text_analysis_techniques.ipynb)

In this project, we were given texts:
* a murder note
* sample letters from three suspects
Using text analysis techniques, I needed
 to determine which suspect most likely wrote the murder note
