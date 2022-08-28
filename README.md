# Projects I've worked on during my studies (and links to their repositories)

NOTE: The projects are ordered from most recently completed to oldest. <br>
DISCLOSURE: My Data Science course puts heavy focus on groupwork, therefore most of these projects are collaborative where I have worked on them in varying degrees. Only the data visualization is fully mine.

## :chart_with_upwards_trend: Data Visualisation Project

Using Tableau I created an interactive visualisation showcasing ammunition statistics from the videogame "Escape from Tarkov".

![EfT Showcase](https://github.com/woodstr/woodstr/blob/main/gifs/datavis-tarkov-showcase.gif)

Feel free try a (less functional) public version [here](https://public.tableau.com/app/profile/aidan.stocks/viz/AmmoGraph-Themed/AmmoGraphDashboard?publish=yes)!

For more details read the paper I wrote about it [here](https://drive.google.com/file/d/1vtx8P8xnSeRl-RvrJJ_PnbPBFjhN6EsE/view?usp=sharing).



## :bar_chart: Cross-platform sentiment analysis (in depth project)

For this project, we investigated a method of training a model on multiple domains to then predict on an unseen domain. For this we used review data from multiple different domains such as Amazon. We wanted to see how we could choose different amounts of each training domain to train on in order to get better performance on the test domain, and we ended up finding a couple different methods of preprocessing that effectively boosted the performance of our model by up to a 5% increase in accuracy.

 - [Repo](https://github.com/hugzito/2nd_year_project_group13) (no description)
 - [Report](https://drive.google.com/file/d/1ZnKUj-_UZbtwQbXMLdmGm10naod1SQBu/view?usp=sharing)




## :cocktail: Forensic Identification of Glass Fragments

We used machine learning techniques to analyse various properties of glass as an input, and make predictions of what type of glass the sample was. We wrote two classifiers from scratch, one a feed forward neural network (which I did), and the other a decision tree classifier. Furthermore we implemented an ensemble method, and then compared all 3 approaches to the problem.

 - [Repo](https://deepnote.com/workspace/woodstr-1f9ed61b-c580-4bc2-83cf-4153bf93470f/project/Machine-Learning-Project-Duplicate-d98e77ce-aa76-4dec-b5ba-79ff85eafdd7/%2Fmain.ipynb) (deepnote)
 - [Report](https://drive.google.com/file/d/165FXZAjAE6jFMIHL9WkAQIe0DuF7CB3X/view?usp=sharing)



## :globe_with_meridians: Airport Network Analysis

For this project we had to choose a network dataset and analyse its various properties. We chose a dataset of the worlds airports and the connections between them. A fun part of our project was to analyse the unrealistic hypothetical scenario of "which airports would still be above sea level should all of the ice in the world melt". I used the python libraries "networkx" and "cartopy" to create maps that showed which airports would be underwater at different sea-levels:

![Network Analysis Showcase](https://github.com/woodstr/woodstr/blob/main/gifs/network-analysis-showcase.gif)

Notice how many of the coastal airports become submerged (red) and how many of the connections are lost!




## :angry::smile::cry: Tweet Sentiment Classification

We used machine learning and natural language processing techniques to automate sentiment classification of tweets. We learned two models to predict whether a tweet contained hate-speech or not, and to predict whether a tweet was of the emotion of anger, joy, optimist or sadness.

 - [Repo](https://github.com/jonas-mika/twitter-hatespeech-detection)
 - [Report](https://drive.google.com/file/d/1TSVmheuEQSd5_ccieIEXxGXJNBP0IYdl/view?usp=sharing)



## :woman_health_worker::man_health_worker: Skin Lesion Detection in Medical Treatment Using Machine Learning

We used machine learning and image processing techniques to learn a KNN algorithm to be able to analyse images of skin lesions and predict whether the lesions were Melanoma (a type of skin cancer) or benign (not harmful).

 - [Repo](https://github.com/jonas-mika/skin-lesion-detection)
 - [Report](https://drive.google.com/file/d/1LzLnPkFjVLFgo9Q9K9coTzZuj8z9VEa5/view?usp=sharing)



## :partly_sunny: How weather possibly influences the spread of Covid-19

We investigated the effects of weather on the spread of Covid-19 in Germany by analysing related data using python. We discovered a negative correlation between the amount of ultra violet light (UV-index) and humans being infected with Covid-19, suggesting that sunnier days leads to less infections. Whether it is due to the ultra violet light killing Covid-19, or due to changes in human social interaction during sunnier days remained inconclusive.

 - [Repo](https://github.com/jonas-mika/covid19-analysis)
 - [Report](https://drive.google.com/file/d/14LGWbN8rWumDQ92pwLWQDk_gyb90EkpJ/view?usp=sharing)



## :bicyclist::collision::car::dash: Road Collision Analysis of Leeds

We investigated the overall road safety in Leeds by analysing traffic data using python. We made visualisations and drew the conclusion that many bicycle-vehicle collisions occur at junctions, and so measures should be taken to improve safety particularly in those areas.

 - [Repo](https://github.com/jonas-mika/fyp2021p01g09)
 - [Report](https://drive.google.com/file/d/1yXyYCPax3Cn5yMM6xYzNYNivF7ozlA1X/view?usp=sharing)
