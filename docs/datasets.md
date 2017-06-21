# Datasets

## Hack Oregon

- [Civic Datasets](http://www.civicapps.org/datasets)
  - Portland crime data by year and location
- [PlotPDX](http://ec2-52-88-193-136.us-west-2.compute.amazonaws.com/services/)
  - Building construction and demolition permits
- [Campaign Finance, Behind the Curtain](http://hackor.github.io)
  - zipped CSV files with transaction and filing data up to Sept 2015
  - [human-browsable Django admin data view](http://totalgood.org/admin/)
    - user: admin
    - password: admin
  - Django admin interface to browse the BTC "schema" 
- [CropPlot agricultural data](https://github.com/hackoregon/or-agriculture/blob/master/data-sources.csv)

## Competitions

Competitions often have labeled datasets and many competitors open source their models, so you can see how well you are doing.

- Kaggle
  - ["Evergreen" or "Timelessness" classification of 10k URLs](https://www.kaggle.com/c/stumbleupon/data)
  - ["World Food Facts" 50MB csv of food carbon footprint and nurtition](https://www.kaggle.com/openfoodfacts/world-food-facts)
  - ["Kaggle Datasets" ](https://www.kaggle.com/datasets)

## Corpora and Lexica

- [Amazon Texts](https://s3.amazonaws.com/text-datasets/nietzsche.txt)
- [Gutenberg](https://www.gutenberg.org/browse/scores/top): all books before 1950
- [Google NGram Viewer](http://storage.googleapis.com/books/ngrams/books/datasetsv2.html) modern books

## Academic Studies

- [2015 Gau mQA data](http://face.baidu.com/nips/FM-IQA.tar.gz)
- [2015 Molay](http://gyro.ktam.org/): Mobile Web App to record accel and gyro from any phone!
- [Accelerometer Monitor](https://play.google.com/store/apps/details?id=com.lul.accelerometer): Android App
- [Google Syntacticly Tagged N-grams from 3.5 Million Books](http://commondatastorage.googleapis.com/books/syntactic-ngrams/syntngrams.final.pdf)
  - [dataset](http://commondatastorage.googleapis.com/books/syntactic-ngrams/index.html) 
- [Bing Queries for Search Algorithm Training](http://research.microsoft.com/en-us/projects/mslr/)
  - Wikipedia [Learning to Rank](https://en.wikipedia.org/wiki/Learning_to_rank) 
  - Wikipedia [Discounted Cumulative Gain](https://en.wikipedia.org/wiki/Discounted_cumulative_gain) metric
- [2011 De](https://www.openintro.org/redirect.php?go=ames_data_documentation&referrer=data_set_page) "Alternative to the Boston Housing Data ..."
  - [Ames, Iowa Residential Home Sales data](https://www.openintro.org/stat/data/ames.csv)

## APIs

- [Quandl](https://www.quandl.com/)
  - historical home price data from Zillow etc
  - historical BitCoin price data, etc.
- [USDA Food and Nutrient API](http://ndb.nal.usda.gov/ndb/doc/index)
- [MS COCO labeled Images](http://mscoco.org/dataset/#download)
  - amazing results have been acheived by training CNN+RNNs on this dataset
- [NYC crime data for past few years](https://thomaslevine.com/!/nyc-crime-map/)
  - API, CSVs, and JSON 

## Data Aggregators

 - [pug-data](https://github.com/totalgood/pug-data)
    - `pip install pug-data` 
    - historical weather time series in the US
    - twitter feeds (natural language text)
 - [nltk](http://www.nltk.org/api/nltk.html#data-module)
    - `pip install nltk`  
    - GUI downloader for Corpora, Lexica, and word usage stats 
 - [twip](https://github.com/totalgood/twip)
    - `pip install twip`
    - twitter feed normalizer
 - [pug-ann](https://github.com/hobson/pug-ann/tree/master/pug/ann/data)
    - historical weather data for Artificial Neural Net experiments
 - [Amazon AWS Datasets](https://aws.amazon.com/datasets/)
    - 

## Government

- [USDA Food Nutrient Database](www.ars.usda.gov)
  - [Release 28](https://www.ars.usda.gov/SP2UserFiles/Place/12354500/Data/SR/SR28/dnload/sr28asc.zip)
  - [Release 28 updates (additional entries)](https://www.ars.usda.gov/SP2UserFiles/Place/12354500/Data/SR/SR28/dnload/sr28upd.zip)
- [DATA.GOV search for portland Data](https://catalog.data.gov/dataset?q=portland%2C+oregon&sort=none&groups=local&organization_type=State+Government&ext_location=&ext_bbox=&ext_prev_extent=-142.03125%2C8.754794702435605%2C-59.0625%2C61.77312286453148)
  - PSU [2014 Salaries by Role](https://data.oregon.gov/api/views/9x7t-w4u8/rows.csv?accessType=DOWNLOAD), [Expenses by Category](https://data.oregon.gov/api/views/ruye-i7t4/rows.csv?accessType=DOWNLOAD)
  - [Oregon OSHA Fatal Accidents](https://data.oregon.gov/api/views/7e2w-n5dn/rows.csv?accessType=DOWNLOAD)

## Interesting Torrent Search Queries

- [Ashley Madison dump](http://google.com/?search=torrent search dmps tar gz)

## University Data Collections

- [Cornell University Collection of Social Science Data](http://www.ciser.cornell.edu/ASPs/datasource.asp)

## Data Tools

- [JSONView](https://chrome.google.com/webstore/search/JSONview?hl=en-US) plugin for Chrome
  - decompresses and lays out json in a tree to make it easier to understand
