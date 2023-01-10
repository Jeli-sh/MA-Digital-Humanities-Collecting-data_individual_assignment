# Reddit's understanding of history: Dataset of all hot posts from r/history (2022)

History is a topic of interest which is nowadays discussed by many on online forums such as Reddit. Yet, what does it mean for our understanding of history when a large group of people, including Academic historians themeselves, discuss a variety of such topics on Reddit? We can imagine that it would be easier for Academics to interact with lots of users. This could bring 'niche' topics to our attention or provide deeper dimensions to anyone interested. At the same time, everyone can post anything. So Academic historians could have less authority on Reddit than they would have in Academic circles. Moreover, what kind of topics get the most attention? As the users themeselves decide, by engaging into conversations and making threads. Does it depend on the interests of the users or even on current developements in the contemporary world?

Daniele Linkevicus de Andrade and Demival Vasques Filho already tipped in these sorts of questions by looking at history forums on Reddit. (see: de Andrade & Filho (2021). Diving into Reddit: authority networks in history forums. Digital Humanities Lab. https://dhlab.hypotheses.org/?p=2297.) They noticed one fascinitating thing about this Reddit universe: the plurality of proposals: All kinds of Reddit-users, academic or non-academic, can engange in and propose topics for a field we all consider as 'history.' de Andrade and Filho explore these phenomenon by looking at ways 'authority' is granted in multiple subreddits about history. In doing so, they analyze different discussions on the subreddits. They focus mainly on the interactions between users in order to see a whole web of factors which could influence someones 'authority' on subreddits dedicated to the topics of history. 

Where de Andrade and Filho provided us with an extensive network analysis of forms of authorization in the reddit universe of history, my dataset lends the possibilities to explore the 'plurality of proposals' more in depth. By zooming in on one subreddit, namely r/History, we could gain more insights into the topics these diverse group of Reddit users actually propose for discussion. I propose that 'simply' looking at the topics in the titles and body's of the threads, the amount of upvotes and the amount of comments we can already have the opportunity to gain important insights into the various ways the user of reddit engange, understand and shape our understandings of history. 

However this repository is merely focused on the creation of the dataset itself. Although I kept these research reccomendations and discussions in mind when creating the dataset, I encourage everyone to use it for there own different research purposes aswell. 

The dataset I created with PRAW (Python Reddit Api Wrapper). My code for the scraper is definitely reusable. As explained in the notebook, one only needs to make its own Reddit App on the Reddit website itself. For this project I only collected the title of the thread, the score (upvotes), a unique ID, the url (of the post itself or content like video's or images within the code), the number of comments and the date of posting. Do note that PRAW gives the opportunity to collect even more data like usernames (but be careful with privacy regulations). For a more extensive guide on how to use PRAW I encourage to go to: https://towardsdatascience.com/scraping-reddit-data-1c0af3040768. Eventually a DataFrame with pandas can be created and saved as a CSV file for further use and exploration.

I gave some examples on how to use pandas for an Exploritary Data Analysis and Summary Statistics, mainly focused on setting the stage for an extensive topic analysis. As a final output I created two graphs with the Python library Plotly. This library is very user friendly and gives the opportunity to create interactive graphs from the dataset. I chose to create two scatterplots. It is possible to hover over the dots the see the title of the thread. In the axes of the graph the amount of upvotes or amount of comments are visible and the date of posting. as Github does not support to display these graphs I provided some snapshots to this repository. If you want to see the interactive elements of the graphs I encourage to view the notebook here: https://nbviewer.org/github/Jeli-sh/MA-Digital-Humanities-Collecting-data_individual_assignment/blob/main/History%20reddit%20dataset-%20EDA%20and%20summary%20statistics.ipynb.


