# SpaceX Success Forecast

Welcome to SpaceX Success Forecast, a data science capstone project that aims to predict the success of Falcon 9 rocket first stage landings and uncover the economic implications of this prediction.

## Table of Contents

- [Story](#story)
  * [Purpose and Scope](#purpose-and-scope)
  * [Business Problem and Motivation](#business-problem-and-motivation)
  * [Objective and Data Exploration](#objective-and-data-exploration)
- [Data Collection](#data-collection)
- [Complete the Data Collection with Web Scraping](#complete-the-data-collection-with-web-scraping)
- [Data Wrangling](#data-wrangling)
- [EDA with Visualization](#eda-with-visualization)
- [Complete the EDA with SQL](#complete-the-eda-with-sql)
- [Launch Sites Locations Analysis with Folium](#launch-sites-locations-analysis-with-folium)
- [Dashboard](#dashboard)
- [Complete the Machine Learning Prediction](#complete-the-machine-learning-prediction)

## Story

Embark on a visionary data-driven odyssey with SpaceXSuccessForecast, where the frontiers of space exploration merge seamlessly with the precision of predictive analytics. The core of this capstone journey is the prediction of Falcon 9's first stage landing success—an endeavor that unlocks profound insights into the realm of space travel economics. SpaceX, renowned for its groundbreaking rocket launches, offers the Falcon 9 at an astonishing cost of 62 million dollars, a stark contrast to the staggering 165 million dollars demanded by other providers, thanks to SpaceX's pioneering practice of reusing the initial stage. Therefore, if we can determine if the first stage will land, we can definitively ascertain the launch cost. Such information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

### Purpose and Scope

In this transformative capstone expedition, we delve into the world of data science and its real-world applications. You step into the role of a Data Scientist leading a startup ready to take on the industry giant, SpaceX. This journey encompasses the entire spectrum of data science methodologies, from collecting and wrangling data to illuminating exploratory data analysis, crafting visualizations, developing intricate models, rigorously evaluating them, and culminating in the vital task of conveying insights to stakeholders. The mission is clear yet complex: predict the outcome of Falcon 9's first stage landing. Through the lens of data science, we navigate through real datasets, uncover hidden patterns, and craft predictive models that will shape the future of space endeavors.

### Business Problem and Motivation

The space industry's colossal costs present a formidable challenge. The Falcon 9, with its reusable first stage, holds the promise of redefining launch expenses and industry norms. Enter our startup—armed with data science—to predict the landing outcome. This goes beyond competition; it's about enabling informed decisions. As we determine the likelihood of a successful landing, we simultaneously unearth the cost of a launch. Armed with these insights, our startup stands ready to compete with SpaceX, placing strategic bids for rocket launches that promise both financial viability and technological excellence.

### Objective and Data Exploration

Within this data-driven saga lies a dual objective. Firstly, we wield data science tools and machine learning techniques to accurately predict the probability of Falcon 9's successful first stage landing. Secondly, we embark on a journey of data exploration, unearthing insights that reveal the vast potential hidden within the dataset. As we traverse the terrain of data analysis, our guiding star is classification accuracy—an essential metric that gauges the effectiveness of our journey. This metric provides a panoramic view of our models' capability to differentiate between triumphant landings and those that end in a different fate.

## Data Collection

Step into the realm of data collection, where the enigma of Falcon 9's first stage landings awaits decryption. Plunge into the troves of Falcon 9 launch data, extracting gems of potential cost savings that lie beneath the surface, a result of the innovative reusability of the inaugural stage. With these invaluable insights in tow, we empower aspiring contenders vying for celestial dominion, equipping them to soar beyond conventional bounds. Our voyage commences with meticulous data harvesting and precision formatting, extracting the essence of information from a robust API source. This endeavor lays the bedrock for an expedition that promises to unearth the uncharted territories of spacefaring statistics.

## Complete the Data Collection with Web Scraping

Unveil the next chapter of our data journey as we delve into the world of web scraping. With Falcon 9 historical launch records scattered across the vast landscape of Wikipedia, we employ the power of Python's BeautifulSoup library to scrape these records from the List of Falcon 9 and Falcon Heavy launches page. This intricate process involves extracting, parsing, and converting raw HTML tables into a structured Pandas dataframe. By harnessing the synergy of web technology and data science, we elevate our dataset to new heights, ready to fuel our exploration.

## Data Wrangling

As our dataset spreads its wings, we embark on a journey of data wrangling—a meticulous dance that transforms raw data into a harmonious symphony of insights. With Falcon 9 launch data in hand, we unravel the intricacies of launch outcomes, unraveling the enigmatic codes of 'True Ocean', 'False RTLS', and 'True ASDS'. These coded outcomes metamorphose into training labels, guiding our models toward predictive excellence. As data sorcerers, we untangle missing values, smooth erratic trajectories, and harmonize our data into a coherent narrative, setting the stage for our exploratory analysis.

## EDA with Visualization

In the realm of Exploratory Data Analysis (EDA), data finds its voice, singing stories of patterns, correlations, and insights. Armed with Pandas and Matplotlib, we immerse ourselves in this symphony. Witness the visual revelations as we chart the course of Falcon 9 launch success rat
es, unfurl the tapestry of payload masses against outcomes, and uncover the interplay of variables shaping the trajectory of success. EDA unveils the cosmos within the data, providing the foundation for informed decision-making and guiding the creation of models that will navigate this celestial landscape.

## Complete the EDA with SQL

In the pursuit of deeper insights, we harness the power of Structured Query Language (SQL) to navigate and query our data with precision. As the lunar phases illuminate the night sky, SQL illuminates patterns within our dataset, revealing relationships, frequencies, and historical trajectories. Dive into our SQL-driven exploration, unraveling launch sites, payload masses, and outcomes through the lens of structured queries. With each query, we unveil facets of the Falcon 9 journey that pave the way for our next phase of analysis.

## Launch Sites Locations Analysis with Folium

Our trajectory now steers us toward the cartographic realm, as we explore the spatial dimensions of launch site locations. With Folium, a dynamic mapping library, we chart the course of launch sites, marking each point on the map. As the Earth unfurls beneath us, witness the clustering of successful launches, observe the geographic nuances that influence outcomes, and discover the subtle interplay of location and success. This visual odyssey offers a spatial dimension to our insights, revealing the landscapes where rockets and data converge.

## Dashboard

In this chapter, we curate a visual symposium—a dashboard that distills our journey's insights into interactive visualizations. Through the lens of this dashboard, we peer into the collective wisdom of data, answering crucial questions: Which launch site boasts the highest success rate? What payload range yields the most successful outcomes? Armed with these visual insights, our dashboard equips stakeholders with the knowledge to navigate the cosmic dance of launch outcomes, steering them toward informed decisions and strategic bidding.

## Complete the Machine Learning Prediction

As our voyage nears its zenith, we enter the realm of predictive mastery. Employing a machine learning pipeline, we summon the power of Support Vector Machines, Classification Trees, and Logistic Regression. Guided by the North Star of model evaluation, we scrutinize hyperparameters, split data into training and testing sets, and fine-tune the algorithms that will predict the probability of a successful Falcon 9 first stage landing. This culmination blends data science and spacefaring, offering a glimpse into the predictive prowess that can shape the economics of rocket launches.

<!-- The rest of the sections should be included as per your project structure -->

## Installation

To get started with SpaceXSuccessForecast, follow these steps:

1. Clone this repository: `git clone https://github.com/yourusername/SpaceXSuccessForecast.git`
2. Navigate to the project directory: `cd SpaceXSuccessForecast`
3. Create a virtual environment (optional but recommended): `python -m venv venv`
4. Activate the virtual environment: `source venv/bin/activate` (on Windows: `venv\Scripts\activate`)
5. Install the required packages: `pip install -r requirements.txt`
6. Launch the project: `jupyter notebook`

## Contributor

- Amin Hassanzadeh


## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.

