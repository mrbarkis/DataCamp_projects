# My completed DataCamp projects
The below descriptions have been scraped from
[DataCamp projects page](https://www.datacamp.com/projects).
The keywords, imports, methods, functions, and attributes, in turn, have been scraped from the notebooks themselves,
and sorted using the tf-idf, i.e. term frequency–inverse document frequency, metric. 
## [A Network Analysis of Game of Thrones](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/A%20Network%20Analysis%20of%20Game%20of%20Thrones/notebook.ipynb)
<div>
 <p>
  Jon Snow, Daenerys Targaryen, or Tyrion Lannister? Who is the most 
important character in Game of Thrones? Let's see what mathematics can tell
us about this!
 </p>
 <p>
  In this project, you will look at the character co-occurrence
network and its evolution over the five books in R.R. Martin's
hugely popular book series
  <em>
   A Song of Ice and Fire
  </em>
  (perhaps better known as the TV show
  <em>
   Game of Thrones
  </em>
  ). You will
look at how the importance of the characters changes over the books using
different centrality measures.
 </p>
 <p>
  This project uses a dataset parsed by Andrew J. Beveridge and Jie Shan 
which is available
  <a href="https://github.com/mathbeveridge/asoiaf">
   here
  </a>
  . 
For more information on this dataset have a look at
  <a href="https://networkofthrones.wordpress.com">
   the Network of Thrones blog
  </a>
  .
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|book network central charact throne fifth degre node pagerank eddard co edg between jon stark import game correl occurr stanni|networkx numpy pandas|.degree_centrality() .from_records() .Graph() .add_edge() .betweenness_centrality() .pagerank() .items() .iterrows() .set_title() .set_ylabel() .arange() .corr() .set_xticks() .idxmax() .set_xticklabels() .sort_values() .plot() .fillna() .set_xlabel() .append() .head() .read_csv()|setBookAxes() list() set() sorted() range() print()|.DataFrame .T .index .csv|


[Original project](https://www.datacamp.com/projects/76) by Mridul Seth, Data science enthusiast

## [A New Era of Data Analysis in Baseball](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/A%20New%20Era%20of%20Data%20Analysis%20in%20Baseball/notebook.ipynb)
<div>
 <p>
  There's a new era of data analysis in baseball. Using a new technology called Statcast, Major League Baseball
is now collecting the precise location and movements of its baseballs and players. In this project,
you will use Statcast data to compare the home runs of two of baseball's brightest (and largest) stars,
Aaron Judge (6'7") and Giancarlo Stanton (6'6"), both of whom now play for the New York Yankees.
 </p>
 <p>
  The dataset used in this project is from
  <a href="https://baseballsavant.mlb.com/about">
   Baseball Savant
  </a>
  .
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|pitch home stanton statcast judg run ball veloc bat player zone hit angl aaron basebal giancarlo pitcher exit hitter launch|seaborn matplotlib.pyplot pandas|.set_visible() .gca() .set_title() .apply() .colorbar() .get_xaxis() .get_yaxis() .hist2d() .kdeplot() .set_label() .regplot() .startswith() .copy() .subplots() .concat() .set_option() .title() .boxplot() .tail() .value_counts() .read_csv()|assign_x_coord() assign_y_coord() print()|.zone .loc .max_columns .str .pyplot .csv|


[Original project](https://www.datacamp.com/projects/250) by David Venturi, Curriculum Manager at DataCamp

## [A Visual History of Nobel Prize Winners](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/A%20Visual%20History%20of%20Nobel%20Prize%20Winners/notebook.ipynb)
<div>
 <p>
  The Nobel Prize is perhaps the world's most well known scientific award. Every
year it is given to scientists and scholars in chemistry,
literature, physics, medicine, economics, and peace. The first Nobel
Prize was handed out in 1901, and at that time the prize was Eurocentric and
male-focused, but nowadays it's not biased in any way. Surely, right?
 </p>
 <p>
  Well, let's find out! What characteristics do the prize winners have? Which
country gets it most often? And has anybody gotten it twice? It's up to you to
figure this out.
 </p>
 <p>
  The
  <a href="https://www.kaggle.com/nobelfoundation/nobel-laureates">
   dataset
  </a>
  used in this project is from The Nobel Foundation on Kaggle.
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|prize winner nobel 1901 imbal peac chemistri physic laureat usa econom literatur medicin 2010 domin categori nowaday gotten youngest got|PercentFormatter matplotlib.ticker seaborn numpy matplotlib.pyplot pandas|.nsmallest() .lineplot() .lmplot() .set_major_formatter() .astype() .floor() .filter() .nlargest() .set() .groupby() .value_counts() .mean() .to_datetime() .head() .read_csv()|PercentFormatter() display() len()|.ticker .yaxis .figsize .rcParams .year .dt .values .pyplot .csv|


[Original project](https://www.datacamp.com/projects/441) by Rasmus Bååth, Senior Data Scientist at King (Activision Blizzard)

## [Analyze Your Runkeeper Fitness Data](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Analyze%20Your%20Runkeeper%20Fitness%20Data/notebook.ipynb)
<div>
 <p>
  With the explosion in fitness tracker popularity, runners all of the world are collecting data with gadgets (smartphones, watches, etc.) to keep themselves motivated. They look for answers to questions like:
 </p>
 <ul>
  <li>
   How fast, long, and intense was my run today?
  </li>
  <li>
   Have I succeeded with my training goals?
  </li>
  <li>
   Am I progressing?
  </li>
  <li>
   What were my best achievements?
  </li>
  <li>
   How do I perform compared to others?
  </li>
 </ul>
 <p>
  I exported seven years worth of my training data from
  <a href="https://runkeeper.com/">
   Runkeeper
  </a>
  . The data is a CSV file where each row is a single training activity. In this project, you'll create import, clean, and analyze my data to answer the above questions. You can then apply the same strategy to your training data if you wish!
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|run km heart train miss shoe distanc activ rate climb resampl runkeep averag forrest intens fill weekli summari export subplot|statsmodels.api warnings matplotlib.pyplot pandas|.resample() .set() .axhspan() .mean() .fillna() .copy() .axhline() .figure() .show() .isnull() .sum() .plot() .subplots() .bfill() .seasonal_decompose() .set_facecolor() .stack() .set_xticklabels() .filterwarnings() .format() .sort_index() .append() .drop() .legend() .sample() .set_title() .describe() .hist() .replace() .use() .groupby() .info() .value_counts() .count() .head() .read_csv()|display() int() range() print() len()|.5 .api .figure .observed .trend .tsa .xaxis .3 .4 .2 .style .str .pyplot .csv|


[Original project](https://www.datacamp.com/projects/727) by Andrii Pavlenko, Project Instructor

## [Bad passwords and the NIST guidelines](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Bad%20passwords%20and%20the%20NIST%20guidelines/notebook.ipynb)
<div>
 <p>
  Almost every web service you join will require you to come up with a password. 
But what makes a good password? 
In June 2017 the National Institute of Standards and Technology (NIST)
published
  <a href="https://pages.nist.gov/800-63-3/sp800-63b.html">
   publication 800-63B
  </a>
  titled
  <em>
   Digital Identity Guidelines: Authentication and Lifecycle Management
  </em>
  . 
This publication doesn't tell you what is a
  <em>
   good
  </em>
  password,
but it does have specific rules for what is a
  <em>
   bad
  </em>
  password.
 </p>
 <p>
  In this project, you will take a list of user passwords and, 
using publication 800-63B, you will write code that automatically 
detects and flags the bad passwords.
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|password nist user secret 63b flag repetit verifi 800 shall check memor rule bad public special prospect charact common ay|pandas|.extract() .sum() .isin() .any() .len() .contains() .head() .lower() .read_csv()|print() len()|.str .txt .csv|


[Original project](https://www.datacamp.com/projects/141) by Rasmus Bååth, Senior Data Scientist at King (Activision Blizzard)

## [Book Recommendations from Charles Darwin](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Book%20Recommendations%20from%20Charles%20Darwin/notebook.ipynb)
<div>
 <p>
  Recommendation systems are at the heart of many products such as Netflix or Amazon. They generally rely on metadata (e.g., the actors or director of a movie) or on user tastes (e.g., the movies you liked before) to determine which you are most likely to enjoy. 
But when you are working with text-heavy datasets, you have access to a much richer resource—the whole text! In this project, you will learn how to build the basis of a book recommendation system based on their content. You will use Charles Darwin's bibliography to find out which books might interest you.
 </p>
 <p>
  The dataset was manually collected from
  <a href="https://www.gutenberg.org">
   Project Gutenberg
  </a>
  .
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|book darwin speci stem token select charl origin concept model idf tf bow similar word topic analys content domest downstream|gensim TfidfModel corpora gensim.models glob hierarchy pickle re, scipy.cluster similarities os matplotlib.pyplot pandas|.DataFrame() .split() .sort_values() .Dictionary() .MatrixSimilarity() .barh() .basename() .dendrogram() .doc2bow() .dump() .glob() .linkage() .load() .stem() .read() .sub() .append() .apply() .replace() .lower() .xlabel() .title() .head()|open() PorterStemmer() TfidfModel() list() sorted() set() range() len() print()|.txt .p .columns .index .cluster .models .path .stem .plot .pyplot|


[Original project](https://www.datacamp.com/projects/607) by Philippe Julien, Senior Data Scientist	at King

## [Comparing Cosmetics by Ingredients](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Comparing%20Cosmetics%20by%20Ingredients/notebook.ipynb)
<div>
 <p>
  Buying new cosmetic products is difficult. It can even be scary for those who have sensitive skin and are prone to skin trouble. The information needed to alleviate this problem is on the back of each product, but it's tought to interpret those ingredient lists unless you have a background in chemistry.
 </p>
 <p>
  Instead of buying and hoping for the best, we can use data science to help us predict which products may be good fits for us. In this Project, you are going to create a content-based recommendation system where the 'content' will be the chemical components of cosmetics. Specifically, you will process ingredient lists for 1472 cosmetics on Sephora via
  <a href="https://en.wikipedia.org/wiki/Word_embedding">
   word embedding
  </a>
  , then visualize ingredient similarity using a machine learning method called t-SNE and an interactive visualization library called Bokeh.
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|ingredi cosmet item sne matrix product skin dimens dimension chemic hover fill composit token embed interpret bokeh difficult coordin 2233|ColumnDataSource, HoverTool TSNE bokeh.io bokeh.models figure push_notebook show, sklearn.manifold bokeh.plotting output_notebook, numpy pandas|.query() .zeros() .add_tools() .circle() .split() .lower() .reset_index() .fit_transform() .append() .value_counts() .head() .read_csv()|oh_encoder() display() ColumnDataSource() HoverTool() TSNE() figure() output_notebook() show() len() range() print()|.Ingredients .Label .io .manifold .values .models .8 .plotting .csv|


[Original project](https://www.datacamp.com/projects/695) by Jiwon Jeong, Graduate Research Assistant at Yonsei University

## [Disney Movies and Box Office Success](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Disney%20Movies%20and%20Box%20Office%20Success/notebook.ipynb)
<div>
 <p>
  Since the 1930s, Walt Disney Studios has released more than 600 films covering a wide range of genres. While some movies are indeed directed towards kids, many are intended for a broad audience. In this project, you will analyze data to see how Disney movies have changed in popularity since its first movie release. You will also perform hypothesis testing to see what aspects of a movie contribute to its success.
 </p>
 <p>
  This project assumes that you can manipulate data using pandas and can make basic plots using Seaborn. You should also be familiar with statistical inference and be able to perform two-sample bootstrap hypothesis tests for difference of means. The prerequisites for this project are
  <a href="https://www.datacamp.com/courses/introduction-to-linear-modeling-in-python">
   Introduction to Linear Modeling in Python
  </a>
  and
  <a href="https://www.datacamp.com/courses/introduction-to-seaborn">
   Introduction to Seaborn
  </a>
  .
 </p>
 <p>
  The dataset used in this project is a modified version of the Disney Character Success dataset from
  <a href="https://data.world/kgarrett/disney-character-success-00-16">
   Kelly Garrett
  </a>
  .
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|genr movi gross disney coeffici action interv confid adventur adjust variabl dummi offic regress box intercept bootstrap film 95 grow|LinearRegression sklearn.linear_model seaborn numpy pandas|.empty() .get_dummies() .percentile() .choice() .relplot() .fit() .arange() .reset_index() .sort_values() .mean() .head() .groupby() .read_csv()|LinearRegression() range() len() print()|.5 .coef_ .intercept_ .linear_model .random .year .dt .csv|


[Original project](https://www.datacamp.com/projects/740) by Sirinda Palahan, Assistant Professor at University of the Thai Chamber of Commerce

## [Do Left-handed People Really Die Young?](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Do%20Left-handed%20People%20Really%20Die%20Young%3F/notebook.ipynb)
<div>
 <p>
  Barack Obama is left-handed. So are Bill Gates and Oprah Winfrey; so were Babe Ruth and Marie Curie. A
  <a href="https://www.nejm.org/doi/full/10.1056/NEJM199104043241418">
   1991 study
  </a>
  reported that left-handed people die on average nine years earlier than right-handed people. Nine years! Could this really be true?
 </p>
 <p>
  In this project, you will explore this phenomenon using age distribution data to see if we can reproduce a difference in average age at death purely from the changing rates of left-handedness over time, refuting the claim of early death for left-handers. This notebook uses
  <code>
   pandas
  </code>
  and Bayesian statistics to analyze the probability of being a certain age at death given that you are reported as left-handed or right-handed.
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|p age lh handed left hand die death studi hander probabl peopl deceas rate extrapol nine gap distribut younger bay|numpy matplotlib.pyplot pandas|.nansum() .array() .subplots() .set_xlabel() .set_ylabel() .sum() .plot() .legend() .logical_and() .multiply() .mean() .tail() .zeros() .arange() .isin() .dropna() .info() .head() .read_csv()|P() P_lh() P_lh_given_A() str() round() P_A_given_lh() P_A_given_rh() print()|.githubusercontent .Series .com .array .tsv .values .loc .shape .pyplot .csv|


[Original project](https://www.datacamp.com/projects/479) by Madeleine Bonsma-Fisher, PhD Candidate at University of Toronto

## [Dr. Semmelweis and the Discovery of Handwashing](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Dr.%20Semmelweis%20and%20the%20Discovery%20of%20Handwashing/notebook.ipynb)
<div>
 <p>
  In 1847, the Hungarian physician Ignaz Semmelweis made a breakthough discovery:
he discovers handwashing. Contaminated hands was a major cause of childbed fever
and by enforcing handwashing at his hospital he saved hundreds of lives.
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|handwash semmelwei clinic death proport vienna childb fever hospit women birth medic dr student reduc corps wash graph effect confid|pandas|.set_ylabel() .mean() .sample() .plot() .quantile() .Series() .to_datetime() .append() .read_csv() .head()|range()|.births .clinic .deaths .date .025 .975 .csv|


[Original project](https://www.datacamp.com/projects/20) by Rasmus Bååth, Senior Data Scientist at King (Activision Blizzard)

## [Exploring the Bitcoin Cryptocurrency Market](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Exploring%20the%20Bitcoin%20Cryptocurrency%20Market/notebook.ipynb)
<div>
 <p>
  To better understand the growth and impact of
Bitcoin and other
  <a href="https://en.wikipedia.org/wiki/Cryptocurrency">
   cryptocurrencies
  </a>
  you will, in this project, explore the
  <em>
   market capitalization
  </em>
  of different cryptocurrencies.
 </p>
 <p>
  <strong>
   Warning: The cryptocurrency market is exceptionally volatile,
and any money you put in might disappear 
into thin air. Never invest money you can't afford to lose.
  </strong>
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|cryptocurr bitcoin coin capit market volatil stock warn pleas color 2020 6th bigger coinmarketcap fork investopedia lose valuabl project definit|matplotlib.pyplot pandas|.query() .bar() .count() .set_index() .set_ylabel() .sort_values() .notnull() .suptitle() .assign() .info() .subplots() .use() .set_xlabel() .dropna() .sum() .head() .read_csv()|capcount() top10_subplot()|.market_cap_usd .plot .figure_format .id .market_cap_perc .percent_change_24h .percent_change_7d .style .pyplot .csv|


[Original project](https://www.datacamp.com/projects/82) by Juan González-Vallinas, Director Data Science at multilayer.io

## [Exploring the Evolution of Linux](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Exploring%20the%20Evolution%20of%20Linux/notebook.ipynb)
<div>
 <p>
  Version control repositories like CVS, Subversion or Git store rich
evolution information about a software project. In this project, 
you'll be challenged to read in, clean up and visualize a real world
Git repository dataset of the Linux kernel. With almost 700k commits and 
thousands of contributors (find out the exact number in this project ;-) )
there are some little data cleaning and wrangling challenges that you'll
encounter. But you'll also gain insights about the development activities
over the last 13 years.
 </p>
 <p>
  For this Project, you need to be familiar with Pandas
  <code>
   DataFrame
  </code>
  s,
especially the
  <code>
   read_csv
  </code>
  and
  <code>
   groupby
  </code>
  functions, as well as working with time series data.
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|linux commit timestamp kernel git develop 00 log author contributor repositori gz latin placehold contribut 01 effort encod year late|pandas|.describe() .Grouper() .max() .min() .idxmax() .read() .unique() .count() .set_xlabel() .set_ylabel() .dropna() .to_datetime() .value_counts() .plot() .groupby() .head() .read_csv()|open() len() print()|.timestamp .author .year .gz .columns .index .csv|


[Original project](https://www.datacamp.com/projects/111) by Markus Harrer, Software Development Analyst

## [Exploring the History of Lego](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Exploring%20the%20History%20of%20Lego/notebook.ipynb)
<div>
 <p>
  The
  <a href="https://rebrickable.com/downloads/">
   Rebrickable
  </a>
  database includes data on every 
LEGO set that has ever been sold; the names of the sets, what bricks they contain, 
what color the bricks are, etc. It might be small bricks, but this is big data!
In this project, you will get to explore the Rebrickable database and answer a series of 
questions related to the history of Lego!
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|lego color theme transpar block danish ship databas unless explor comprehens set vari read divers fascin godt is_tran leg rebrick|pandas|.groupby() .count() .agg() .duplicated() .unique() .set_title() .set_xlabel() .set_ylabel() .sum() .mean() .plot() .head() .read_csv()|len() print()|.rgb .count .Series .csv|


[Original project](https://www.datacamp.com/projects/10) by Ramnath Vaidyanathan, VP of Product Research at DataCamp

## [Extract Stock Sentiment from News Headlines](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Extract%20Stock%20Sentiment%20from%20News%20Headlines/notebook.ipynb)
<div>
 <p>
  It used to take days for financial news to spread via radio, newspapers, and word of mouth. Now, in the age of the internet, it takes seconds. Did you know news articles are
  <em>
   automatically
  </em>
  being generated from figures and earnings call streams? In this project, you will generate investing insight by applying
  <a href="https://en.wikipedia.org/wiki/Sentiment_analysis">
   sentiment analysis
  </a>
  on financial news headlines from
  <a href="https://finviz.com">
   Finviz
  </a>
  . Using this
  <a href="https://en.wikipedia.org/wiki/Natural_language_processing">
   natural language processing
  </a>
  technique, you will understand the emotion behind the headlines and predict whether the market
  <em>
   feels
  </em>
  good or bad about a stock.
 </p>
 <p>
  The datasets used in this project are raw HTML files for the
  <a href="https://finviz.com/quote.ashx?t=FB">
   Facebook
  </a>
  (FB) and
  <a href="https://finviz.com/quote.ashx?t=TSLA">
   Tesla
  </a>
  (TSLA) stocks from
  <a href="https://finviz.com/">
   FINVIZ.com
  </a>
  , a popular website dedicated to stock information and news.
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|headlin sentiment stock news financi finviz journalist lexicon vader insid nltk trade html pars tabl day extra independ piec tesla|#nltk.download('vader_lexicon') SentimentIntensityAnalyzer nltk.sentiment.vader BeautifulSoup bs4 nltk; os matplotlib.pyplot pandas|.find() .prettify() .xs() .get_text() .set_index() .DataFrame() .split() .findAll() .find_all() .listdir() .to_list() .update() .bar() .items() .drop_duplicates() .unstack() .to_datetime() .sort_index() .download() .join() .head() .count() .apply() .drop() .legend() .use() .ylabel() .append() .mean() .groupby()|SentimentIntensityAnalyzer() BeautifulSoup() enumerate() open() print() len()|.text .a .date .html .lexicon .polarity_scores .sentiment .td .time .title .vader .dt .plot .2 .5 .columns .style .pyplot|


[Original project](https://www.datacamp.com/projects/611) by Juan González-Vallinas, Director Data Science at multilayer.io

## [Find Movie Similarity from Plot Summaries](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Find%20Movie%20Similarity%20from%20Plot%20Summaries/notebook.ipynb)
<div>
 <p>
  Natural Language Processing (NLP) is an exciting field of study for data scientists where they develop algorithms that can make sense out of conversational language used by humans. In this Project, you will use NLP to find the degree of similarity between movies based on their plots available on IMDb and Wikipedia.
 </p>
 <p>
  The dataset contains the titles of the top 100 movies on
  <a href="https://www.imdb.com/">
   IMDb
  </a>
  as well as each movie's plot summary from both IMDb and Wikipedia.
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|movi sentenc cluster stem token dendrogram similar stopword wed daughter imdb genr shall watch wit vector word idf tf citi|KMeans SnowballStemmer cosine_similarity dendrogram linkage, nltk.download('punkt') nltk.stem.snowball scipy.cluster.hierarchy sklearn.cluster sklearn.metrics.pairwise nltk; TfidfVectorizer re sklearn.feature_extraction.text numpy matplotlib.pyplot pandas|.search() .sent_tokenize() .word_tokenize() .astype() .stem() .gcf() .get_xmajorticklabels() .set_color() .tolist() .gca() .seed() .set_size_inches() .download() .hist() .fit_transform() .fit() .show() .value_counts() .head() .read_csv()|SnowballStemmer() tokenize_and_stem() KMeans() Not() cosine_similarity() dendrogram() linkage() TfidfVectorizer() print() len()|.cluster .hierarchy .labels_ .pairwise .snowball .shape .8 .stem .random .feature_extraction .metrics .2 .text .pyplot .plot .csv|


[Original project](https://www.datacamp.com/projects/648) by Anubhav Singh, Founder at The Code Foundation

## [Generating Keywords for Google Ads](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Generating%20Keywords%20for%20Google%20Ads/notebook.ipynb)
<div>
 <p>
  You work for a digital marketing agency, which is approached by a massive online retailer of furniture. 
You are tasked with creating a prototype set of keywords for search campaigns for their sofas section. With your 
Python skills, you will efficiently create these keywords!
 </p>
 <p>
  The most important task in structuring a search engine marketing account is mapping the right keywords to the right ads and making sure they send users to the right landing pages. Having figured that out is a big part of the account setup and makes the life of the account manager much easier.
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|keyword sofa reclin campaign match exact ad campaign1 buy brief sem_sofa price phrase adgroup_1 datacampsofa deliveri shop product search client|pprint pandas|.to_csv() .append() .from_records() .rename() .copy() .DataFrame() .count() .groupby() .head()|pprint() print()|.csv|


[Original project](https://www.datacamp.com/projects/400) by Elias Dabbas, Owner at The Media Supermarket

## [Introduction to DataCamp Projects](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Introduction%20to%20DataCamp%20Projects/notebook.ipynb)
<div>
 <p>
  This is an introduction to DataCamp projects. DataCamp projects allow you to apply 
the skills you have learned in DataCamp courses. In each project, you will carry out 
an end-to-end analysis on real-world tasks using real-world tools and workflows.
 </p>
 <p>
  In doing so, you will learn how to work with Jupyter notebooks: an open-source web 
application that is great for interactive data analysis.
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|cell jupyt code magic inlin run command interact greet render temperatur nice 2016 display click notebook children global tabl output|folium matplotlib.pyplot pandas|.Map() .Marker() .add_to() .xlabel() .ylabel() .title() .show() .plot() .read_csv()|greet() print()|.0266 .0311 .0579 .3318 .4970 .5431 .9 .4 .5 .pyplot .csv|


[Original project](https://www.datacamp.com/projects/33) by Rasmus Bååth, Senior Data Scientist at King (Activision Blizzard)

## [Naïve Bees: Image Loading and Processing](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Na%C3%AFve%20Bees:%20Image%20Loading%20and%20Processing/notebook.ipynb)
<div>
 <p>
  Can a machine distinguish between a honey bee and a bumble bee? Being able to identify bee species from images, while challenging, would allow researchers to more quickly and effectively collect field data. In this Project, you will use the Python image library Pillow to load and manipulate image data. You'll learn common transformations of images and how to build them into a pipeline.
 </p>
 <p>
  This project is the first part of a series of projects that walk through working with image data, building classifiers using traditional techniques, and leveraging the power of deep learning for computer vision. The second project in the series is
  <a href="https://www.datacamp.com/projects/412">
   Naïve Bees: Predict Species from Images
  </a>
  .
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|imag bee color channel bumbl honey pillow grayscal height pil pipelin save width blue mode flower manipul pixel simplifi matrix|Path pathlib IPython.display Image PIL display numpy matplotlib.pyplot pandas|.imshow() .format() .save() .open() .array() .show() .convert() .crop() .rotate() .transpose() .beta() .density() .fromarray() .maximum() .resize() .flatten() .Series()|plot_rgb() display() plot_kde() process_image() Path() enumerate() print()|.jpg .cm .FLIP_LEFT_RIGHT .gray .stem .Blues_r .Greens_r .Reds_r .g .size .shape .display .random .plot .pyplot|


[Original project](https://www.datacamp.com/projects/374) by Peter Bull, Co-founder of DrivenData

## [Naïve Bees: Predict Species from Images](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Na%C3%AFve%20Bees:%20Predict%20Species%20from%20Images/notebook.ipynb)
<div>
 <p>
  Can a machine distinguish between a honey bee and a bumble bee? Being able to identify bee species from images, while challenging, would allow researchers to more quickly and effectively collect field data. In this project, you will use the Python image library Pillow to load and manipulate image data, then build a model to identify honey bees and bumble bees given an image of these insects.
 </p>
 <p>
  This project is the second part of a series of projects that walk through working with image data, building classifiers using traditional techniques, and leveraging the power of deep learning for computer vision.
 </p>
 <p>
  The recommended prerequisites for this project are
  <a href="https://www.datacamp.com/courses/intermediate-python-for-data-science">
   Intermediate Python for Data Science
  </a>
  ,
  <a href="https://www.datacamp.com/courses/introduction-to-data-visualization-with-python">
   Introduction to Data Visualization with Python
  </a>
  ,
  <a href="https://www.datacamp.com/courses/supervised-learning-with-scikit-learn">
   Supervised Learning with scikit-learn
  </a>
  , and
  <a href="https://www.datacamp.com/projects/374">
   Naïve Bees: Image Loading and Processing
  </a>
  .
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|imag bee featur svm 0 bombu curv bumbl honey label auc gradient hog pca roc compon model predict array scikit|PCA SVC StandardScaler accuracy_score auc, hog mpl rgb2gray roc_curve, skimage.color skimage.feature IPython.display Image PIL display matplotlib sklearn.decomposition sklearn.metrics sklearn.preprocessing sklearn.svm os sklearn.model_selection train_test_split numpy matplotlib.pyplot pandas|.imshow() .format() .array() .hstack() .predict_proba() .fit_transform() .flatten() .open() .show() .Series() .join() .predict() .legend() .xlabel() .ylabel() .title() .fit() .plot() .append() .value_counts() .head() .read_csv()|get_image() create_features() create_feature_matrix() hog() rgb2gray() PCA() SVC() StandardScaler() accuracy_score() auc() roc_curve() train_test_split() display() print()|.0 .genus .shape .cm .gray .index .2f .color .feature .3 .path .display .jpg .decomposition .preprocessing .svm .metrics .model_selection .values .pyplot .csv|


[Original project](https://www.datacamp.com/projects/412) by Peter Bull, Co-founder of DrivenData

## [Predicting Credit Card Approvals](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Predicting%20Credit%20Card%20Approvals/notebook.ipynb)
<div>
 <p>
  Commercial banks receive a lot of applications for credit cards. Many of them get rejected 
for many reasons, like high loan balances, low income levels, or too many inquiries on an 
individual's credit report, for example. Manually analyzing these applications is mundane, 
error-prone, and time-consuming (and time is money!). Luckily, this task can be automated with 
the power of machine learning and pretty much every commercial bank does so nowadays. 
In this project, you will build an automatic credit card approval predictor using machine learning 
techniques, just like the real banks do.
 </p>
 <p>
  The dataset used in this project is the
  <a href="http://archive.ics.uci.edu/ml/datasets/credit+approval">
   Credit Card Approval dataset
  </a>
  from the UCI Machine Learning Repository.
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|card credit approv miss applic model numer machin valu featur learn predict imput deni train non scale confus statu preprocess|sklearn.preprocessing sklearn.model_selection GridSearchCV LabelEncoder LogisticRegression MinMaxScaler confusion_matrix sklearn.linear_model sklearn.metrics train_test_split numpy pandas|.isnull() .sum() .tail() .fit_transform() .fillna() .score() .fit() .predict() .mean() .drop() .describe() .replace() .info() .value_counts() .head() .read_csv()|GridSearchCV() LabelEncoder() LogisticRegression() MinMaxScaler() confusion_matrix() dict() train_test_split() zip() print()|.preprocessing .dtypes .model_selection .best_params_ .best_score_ .data .nan .values .linear_model .33 .metrics .index|


[Original project](https://www.datacamp.com/projects/558) by Sayak  Paul, Deep Learning Associate at PyImageSearch

## [Real-time Insights from Social Media Data](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Real-time%20Insights%20from%20Social%20Media%20Data/notebook.ipynb)
<div>
 <p>
  Fear of missing out, curiosity, self-esteem, speed: it's like social media has changed our basic human needs; these baits are keeping us hooked and engaged. And Twitter is a master at this
  <em>
   game
  </em>
  .  Elon Musk's tweets keep Wall Street on its toes; Trump's tweets have the potential of starting wars — Twitter has this huge influence on the world because of the type of its users. Data from
  <em>
   Twitter-storms
  </em>
  is available in near real-time. This means we can learn about the big waves of thoughts and moods around the world as they arise. So of course, we are not going to miss the chance to analyze this treasure trove.
 </p>
 <p>
  In this Project, you will use pre-downloaded datasets to understand the nuts and bolts of Twitter Data. In particular, you will do a thorough analysis of a hot-trend.
 </p>
 <p>
  <em>
   Warning: Some of the tweets in the Twitter datasets contain explicit language.
  </em>
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|tweet twitter trend welovetheearth retweet dicki json lil queri topic music leo api earth hashtag kati thought video insight around|Counter collections json matplotlib.pyplot pandas|.dumps() .keys() .loads() .read() .background_gradient() .intersection() .most_common() .DataFrame() .hist() .sort_values() .sum() .append() .groupby()|type() Counter() open() set() print() len()|.json .style .pyplot|


[Original project](https://www.datacamp.com/projects/760) by Samia Khalid, Senior Software Engineer at Microsoft

## [Recreating John Snow's Ghost Map](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Recreating%20John%20Snow's%20Ghost%20Map/notebook.ipynb)
<div>
 <p>
  In 1854, Dr. John Snow (no, not the Game of Thrones's character)
used a pre-computer method of spatial analysis by mapping patterns
and occurrences of cholera outbreaks in Soho, London. He mapped the
deaths in the neighbourhood and determined that a vast majority occurred
around one particular water well and that those that died used that
well.
 </p>
 <p>
  This is not only one of the earliest uses of data visualization,
but by solving this problem, Dr. John Snow also founded spatial analysis and
modern epidemiology. In this Python project, you will reanalyze the data and recreate 
his famous map.
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|john snow pump cholera outbreak street water map london theori death 1854 ghost miasma proof broad handl recreat anesthesia essay|bokeh figure, show bokeh.plotting output_notebook, folium pandas|.line() .add_to() .CircleMarker() .iterrows() .circle() .rename() .Map() .Marker() .info() .describe() .to_datetime() .sum() .groupby() .read_csv() .head()|zip() range() figure() output_notebook() show() list() len() print()|.13666 .5132119 .INLINE .resources .weekday_name .plotting .4 .2 .dt .shape .csv|


[Original project](https://www.datacamp.com/projects/132) by Radovan Kavicky, President and Principal Data Scientist at GapData Institute

## [Risk and Returns: The Sharpe Ratio](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Risk%20and%20Returns:%20The%20Sharpe%20Ratio/notebook.ipynb)
<div>
 <p>
  When you assess whether to invest in an asset, you want to look not only 
at how much money you could make but also at how much risk you are taking. 
The Sharpe Ratio, developed by Nobel Prize winner William Sharpe some 
50 years ago, does precisely this: it compares the return of an investment 
to that of an alternative and relates the relative return to the risk of
the investment, measured by the standard deviation of returns.
 </p>
 <p>
  In this project, you will apply the Sharpe ratio to real financial data using pandas.
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|ratio sharp return risk amazon invest 500 p daili benchmark stock facebook portfolio deviat opportun calcul input higher investor free|numpy matplotlib.pyplot pandas|.show() .describe() .pct_change() .bar() .plot() .div() .sqrt() .std() .dropna() .info() .sub() .use() .mean() .read_csv()|print()|.plot .style .pyplot .csv|


[Original project](https://www.datacamp.com/projects/66) by Stefan Jansen, Founder & Lead Data Scientist at Applied Artificial Intelligence

## [TV, Halftime Shows, and the Big Game](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/TV%2C%20Halftime%20Shows%2C%20and%20the%20Big%20Game/notebook.ipynb)
<div>
 <p>
  Whether or not you like football, the Super Bowl is a spectacle. There's drama in the form of blowouts, comebacks, and controversy in the games themselves. There are the ridiculously expensive ads, some hilarious, others gut-wrenching, thought-provoking, and weird. The half-time shows with the biggest musicians in the world, sometimes
  <a href="https://youtu.be/ZD1QrIe--_Y?t=14">
   riding giant mechanical tigers
  </a>
  or
  <a href="https://youtu.be/mjrdywp5nyE?t=62">
   leaping from the roof of the stadium
  </a>
  . And in this project, you will find out how some of the elements of this show interact with each other. You will answer questions like:
 </p>
 <ul>
  <li>
   What are the most extreme game outcomes?
  </li>
  <li>
   How does the game affect television viewership?
  </li>
  <li>
   How have viewership, TV ratings, and ad cost evolved over time?
  </li>
  <li>
   Who are the most prolific musicians in terms of halftime show performances?
  </li>
 </ul>
 <p>
  The dataset used in this project was scraped and polished from Wikipedia. It is made up of three CSV files, one with
  <a href="https://en.wikipedia.org/wiki/List_of_Super_Bowl_champions">
   game data
  </a>
  , one with
  <a href="https://en.wikipedia.org/wiki/Super_Bowl_television_ratings">
   TV data
  </a>
  , and one with
  <a href="https://en.wikipedia.org/wiki/List_of_Super_Bowl_halftime_shows">
   halftime musician data
  </a>
  for all 52 Super Bowls through 2018.
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|bowl super halftim tv musician game band song viewer miss march watch household show blowout broadcast u viewership lost point|pyplot matplotlib seaborn pandas|.subplot() .xlabel() .contains() .hist() .ylabel() .title() .show() .sort_values() .tight_layout() .regplot() .info() .plot() .merge() .use() .reset_index() .dropna() .count() .head() .groupby() .read_csv()|display() game() max() int() print()|.super_bowl .musician .ad_cost .and .avg_us_viewers .combined_pts .difference_pts .num_songs .rating_household .str .style .values .csv|


[Original project](https://www.datacamp.com/projects/684) by David Venturi, Curriculum Manager at DataCamp

## [The Android App Market on Google Play](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/The%20Android%20App%20Market%20on%20Google%20Play/notebook.ipynb)
<div>
 <p>
  Mobile apps are everywhere. They are easy to create and can be lucrative. Because of these two factors, more and more apps are being developed. In this project, you will do a comprehensive analysis of the Android app market by comparing over ten thousand apps in Google Play across different categories. You'll look for insights in the data to devise strategies to drive growth and retention.
 </p>
 <p>
  The
  <a href="https://www.kaggle.com/lava18/google-play-store-apps">
   data
  </a>
  for this project was scraped from the
  <a href="https://play.google.com/store/apps?hl=en">
   Google Play
  </a>
  website. While there are many popular datasets for Apple App Store, there aren't many for Google Play apps, which is partially due to the increased difficulty in scraping the latter as compared to the former. The data files are as follows:
 </p>
 <ul>
  <li>
   <code>
    apps.csv
   </code>
   : contains all the details of the applications on Google Play. There are 13 features that describe a given app.
  </li>
  <li>
   <code>
    user_reviews.csv
   </code>
   : contains 100 reviews for each app,
   <a href="https://www.androidpolice.com/2019/01/21/google-play-stores-redesigned-ratings-and-reviews-section-lets-you-easily-filter-by-star-rating/">
    most helpful first
   </a>
   . The text in each review has been pre-processed and attributed with three new features: Sentiment (Positive, Negative or Neutral), Sentiment Polarity and Sentiment Subjectivity.
  </li>
 </ul>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|app paid user free price sentiment review categori instal mobil strategi googl play rate expens market size junk download medic|go plotly plotly.graph_objs warnings seaborn matplotlib.pyplot pandas|.iplot() .nunique() .set_size_inches() .Box() .jointplot() .set_style() .stripplot() .set_title() .subplots() .sample() .Bar() .Histogram() .Layout() .init_notebook_mode() .filter() .filterwarnings() .duplicated() .drop_duplicates() .to_numeric() .boxplot() .query() .unique() .merge() .isin() .replace() .reset_index() .dropna() .sort_values() .info() .sum() .value_counts() .mean() .groupby() .read_csv() .head()|round() dict() len() print()|.Category .offline .Rating .graph_objs .index .str .values .shape .pyplot .csv|


[Original project](https://www.datacamp.com/projects/619) by Lavanya Gupta, Machine Learning Engineer at PropTiger.com

## [The GitHub History of the Scala Language](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/The%20GitHub%20History%20of%20the%20Scala%20Language/notebook.ipynb)
<div>
 <p>
  Open source projects contain entire development histories, such as who made changes, the changes themselves, and code reviews. 
In this project, you'll be challenged to read in, clean
up, and visualize the real-world project repository of 
Scala that spans data from a version control system (Git)
as well as a project hosting site (GitHub). With almost
30,000 commits and a history spanning over ten years, Scala
is a mature language. You will find out who has had the
most influence on its development and who are the experts.
 </p>
 <p>
  The dataset includes the project history of
  <a href="http://www.scala-lang.org">
   Scala
  </a>
  retrieved from Git and
GitHub as a set of CSV files.
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|pull project request scala contribut submit span recent develop utc person contributor commit github commun code histori calendar reflect reifi|pandas|.merge() .pivot_table() .set_xlabel() .count() .set_ylabel() .isin() .groupby() .reset_index() .strftime() .bar() .startswith() .nlargest() .agg() .to_datetime() .sort_values() .sort_index() .head() .apply() .split() .hist() .append() .plot() .read_csv()|set() january_only() len() print()|.scala .dtypes .dt .index .year .plot .date .csv|


[Original project](https://www.datacamp.com/projects/163) by Anita Sarma, Associate Professor at Oregon State University

## [The Hottest Topics in Machine Learning](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/The%20Hottest%20Topics%20in%20Machine%20Learning/notebook.ipynb)
<div>
 <p>
  Neural Information Processing Systems (NIPS) is one of the top machine learning conferences in the world where groundbreaking work is published. 
In this Project, you will analyze a large collection of NIPS research papers from the past decade to discover
the latest trends in machine learning. The techniques used here to handle large amounts of data can be applied 
to other text datasets as well.
 </p>
 <p>
  Familiarity with Python and pandas is required to complete this Project, as well as experience 
with Natural Language Processing in Python (
  <code>
   sklearn
  </code>
  specifically).
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|paper lda topic nip machin titl learn cloud neural text confer preprocess research publish network typic represent pdf perplex vector|CountVectorizer LDA LatentDirichletAllocation wordcloud re sklearn.decomposition warnings sklearn.feature_extraction.text numpy matplotlib.pyplot pandas|.get_feature_names() .join() .WordCloud() .argsort() .generate() .map() .simplefilter() .to_image() .toarray() .xticks() .bar() .size() .sub() .zeros() .arange() .drop() .lower() .xlabel() .ylabel() .title() .fit_transform() .fit() .show() .count() .head() .groupby() .read_csv()|plot_10_most_common_words() print_topics() LDA() CountVectorizer() sorted() enumerate() zip() len() print()|.components_ .gz .decomposition .feature_extraction .text .str .pyplot .plot .csv|


[Original project](https://www.datacamp.com/projects/158) by Lars Hulstaert, Data Scientist at Microsoft

## [Up and Down With the Kardashians](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Up%20and%20Down%20With%20the%20Kardashians/notebook.ipynb)
<div>
 <p>
  While I'm not a fan nor a hater of the Kardashians and Jenners, the polarizing family intrigues me. Why? Their marketing prowess. Say what you will about them and what they stand for, they are great at the hype game. Everything they touch turns to content.
 </p>
 <p>
  In this Project, you will explore the data underneath the hype in the form of search interest data from Google Trends. You'll recreate the Google Trends plot to visualize their ups and downs over time, then make a few custom plots of your own. And you'll answer the big question:
  <strong>
   is Kim even the most famous sister anymore?
  </strong>
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|sister kim kardashian jenner kyli daughter famili month search googl 2007 integ kourtney robert famou anymor caitlyn hype kendal khloé|pandas|.info() .rolling() .to_string() .plot() .mean() .to_numeric() .set_index() .replace() .to_datetime() .head() .read_csv()||.columns .str .csv|


[Original project](https://www.datacamp.com/projects/538) by David Venturi, Curriculum Manager at DataCamp

## [Who Is Drunk and When in Ames, Iowa?](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Who%20Is%20Drunk%20and%20When%20in%20Ames%2C%20Iowa%3F/notebook.ipynb)
<div>
 <p>
  Using data collected from the State of Iowa, you will group, summarize, and visualize data
on breath alcohol tests in Ames, Iowa, (home of Iowa State
University) from 2013-2017. Some questions you will answer
include, "What is the highest recorded value?" and 
"When do breath alcohol tests occur most?"
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|ame iowa alcohol breathalyz veishea test breath depart polic colleg week univers 2am campu town state usa administ drive month|pandas|.size() .value_counts() .bar() .assign() .unstack() .groupby() .boxplot() .dropna() .to_datetime() .sort_values() .count() .plot() .head() .read_csv()|print()|.08 .bar .week .shape .plot .dt .csv|


[Original project](https://www.datacamp.com/projects/475) by Samantha Tyner, Postdoctoral Research Associate at Iowa State University

## [Who's Tweeting? Trump or Trudeau?](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Who's%20Tweeting%3F%20Trump%20or%20Trudeau%3F/notebook.ipynb)
<div>
 <p>
  Let's apply our natural language processing knowledge to Twitter. Tweets are notoriously difficult, as they are shorter than most texts and usually have hard-to-parse content like hashtags, mentions, links and emoji.
 </p>
 <p>
  Despite the difficulties, tweets are fun content, so in this notebook we'll take a look at classifying two prominent North American politicians. Can we determine if it is Donald Trump  or Justin Trudeau based on just a tweet? Let's see!
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|trudeau tweet trump model french classifi linearsvc confus bayesian class modul accuraci vector multinomi learn idf tf scikit investig classif|datasets.helper_functions pprint CountVectorizer, LinearSVC MultinomialNB metrics plot_and_return_top_features plot_confusion_matrix random.seed(53) random; sklearn sklearn.naive_bayes TfidfVectorizer sklearn.svm sklearn.feature_extraction.text sklearn.model_selection train_test_split pandas|.transform() .predict() .accuracy_score() .confusion_matrix() .fit() .fit_transform() .seed() .sample() .read_csv()|plot_confusion_matrix() MultinomialNB() LinearSVC() plot_and_return_top_features() TfidfVectorizer() pprint() CountVectorizer() train_test_split() print()|.05 .helper_functions .9 .3f .e .naive_bayes .svm .33 .feature_extraction .model_selection .text .csv|


[Original project](https://www.datacamp.com/projects/467) by Katharine Jarmul, Founder, kjamistan

## [Word Frequency in Classic Novels](https://www.github.com/mrbarkis/DataCamp_projects/blob/master/Word%20Frequency%20in%20Classic%20Novels/notebook.ipynb)
<div>
 <p>
  Jon Snow, Daenerys Targaryen, or Tyrion Lannister? Who is the most 
important character in Game of Thrones? Let's see what mathematics can tell
us about this!
 </p>
 <p>
  In this project, you will look at the character co-occurrence
network and its evolution over the five books in R.R. Martin's
hugely popular book series
  <em>
   A Song of Ice and Fire
  </em>
  (perhaps better known as the TV show
  <em>
   Game of Thrones
  </em>
  ). You will
look at how the importance of the characters changes over the books using
different centrality measures.
 </p>
 <p>
  This project uses a dataset parsed by Andrew J. Beveridge and Jie Shan 
which is available
  <a href="https://github.com/mathbeveridge/asoiaf">
   here
  </a>
  . 
For more information on this dataset have a look at
  <a href="https://networkofthrones.wordpress.com">
   the Network of Thrones blog
  </a>
  .
 </p>
</div>
 


| Keywords | Imports | Methods | Functions | Attributes/Extensions|
| --- |--- | --- | --- | --- |
|dick mobi nltk word packag html soup novel beautifulsoup gutenberg text request stop languag 2701 beauti www web org http|nltk requests BeautifulSoup bs4|.FreqDist() .RegexpTokenizer() .get() .tokenize() .words() .get_text() .download() .lower() .plot()|BeautifulSoup()|.com .amazonaws .corpus .datacamp .encoding .htm .stopwords .tokenize .text|


[Original project](https://www.datacamp.com/projects/38) by Hugo Bowne-Anderson, Data Scientist at DataCamp
