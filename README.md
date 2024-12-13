#Breweries and Obesity for each US state

##Motivation
I decided to look into US brewery statistics after accidentally walking into a brewery association discussion about the thriving Cincinnati brewery scene and a potential bubble that had formed at the time. I decided to add in heatlh statistics after visiting Seattle and Denver where they have an emphasis on the outdoors and exercise plus what felt like a large number of breweries.

##Objective
To analyze the number of breweries and obesity rate across all US states and see if there is a relationship between the two.

##Data Sources
API with a list of breweries for every US state. https://www.openbrewerydb.org/breweries
API with the obesity rate for every US state. https://rapidapi.com/adrienpelletierlaroche/api/obesity-by-state

##Data Processing and Transformation
Data from both APIs was cleaned and organized using the Python Pandas Library.

##Visualizations
- Bar Graph showing the different types of breweries
- US Map showing the number of breweries in each state
- US Map showing the obesity rate for each state
- Scatterplot with regression line

##Setup and Installation
1. Clone the repository
   git clone https://github.com/andrewb363/Project.git

2. Create and activate a virtual environment
   python -m venv venv
   source venv/bin/activate   #On Mac 
   venv\Scripts\activate   #On windows

3. Install required packages
   pip install -r requirements.txt

4. Once complete, make sure to deactivate
   deactivate

##Results
Colorado had the lowest obesity rate. California had the highest number of breweries. The data showed very slightly that as the obesity rate went up, the number of breweries started to go down. The scatterplot shows a slight decline and the correlation backs it up. However there is not enough data or variables to make a conclusive finding on the relationship between breweries and obesity.

##Future Ideas and Ways to Expand
- I would like to add in more data 
   - A good example would be step data. I tried really hard and was unable to get step data. It is very closely guarded but I was able to find a group that allows researches from prestigious institutions to use step data. There is self reported exercise data from the CDC that could be useful
    - Data around alchohol usage and smoking would be interesting to compare
    - Data around finances and demographics could add a lot
- I would also like to compare on a more granular level. Looking at county data or city/metro area might tell more of a story
