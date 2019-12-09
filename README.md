This is a template you can use for your final projects (as well other projects where you need to post replication code.) Fill in each section with information on your own project.

## Short Description

This code scrapes press briefings and remarks from the White House and State Department websites, then filters for text that relates to statements about North Korea. It then pulls all mentions of North Korean leader Kim Jong Un to determine what title the U.S. Government has used to refer to him over time. Finally, it graphs the results by time and source (White House and State Department).

## Dependencies

List what software your code depends on, as well as version numbers, like so:.

1. R, 3.6.1

In your scripts, includes commands that `require()` packages.

## Files

List all files (other than `README.md` and `Final-Project.RProj`) contained in the repo, along with a brief description of each one, like so:

#### /

1. Narrative.Rmd: Provides a 3-5 page narrative of the project, main challenges, solutions, and results.
2. Narrative.pdf: A knitted pdf of Narrative.Rmd. 
3. Lightning_Talk.pptx: Slides for brief presentation of code and results

#### Code/
1. wh_scraping.rmd: Collects data from the White House website and exports data to the file white_house_data.RData.
2. wh_filtering.rmd: Loads, cleans, and filters data to isolate mentions of Kim Jong Un, then exports to the file wh_kim_texts.RData.
1. state_scraping.rmd: Collects data from the State Department website and exports data to the file state_dept_data.RData.
2. state_filtering.rmd: Loads, cleans, and filters data to isolate mentions of Kim Jong Un, then exports to the file state_kim_texts.RData.
3. final_analysis.rmd: Conducts descriptive analysis of the data, producing the tables and visualizations found in the Results directory.

#### Data/

1. white_house_data.RData: Text scraped from White House website.
2. wh_kim_texts.RData: Cleaned dataset including all mentions of Kim Jong Un by the White House.
3. state_dept_data.RData: Text scraped from State Department website.
4. state_kim_texts.RData: Cleaned dataset including all mentions of Kim Jong Un by the State Department.

#### Results/

1. Kim_Titles.pdf: PDF of graph for the number and type of Kim Jong Un mention over time.
2. Kim_Titles.png: Image file of graph for the number and type of Kim Jong Un mention over time.
3. Results_Table.png: Table showing counts for each type of mention by both the White House and the State Department in the dataset.

## More Information

Jenna Gibson
University of Chicago

