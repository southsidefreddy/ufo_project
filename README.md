# ufo_project

## About

There have been more stories popping up about ufo's lately and there are so many questions that could be asked on this topic?  This data analysis is going to look at two data sets to see if there are any relationships between where ufo sightings occur and the climate of those areas. This project will break the climate down to the average year round temperature of the fifty US states and some Canadian provinces. The data will be analyzed in a Jupyter Notebook using Visual Studio Code as a text editor.  There is a requirements.txt file that provides all the necessary packages needed to edit and run the program.

## Question to answer

    * Is there any relationship between the temperature of an area and the amount of ufo sightings that are reported in those areas?
    
    
## Features
    
    * Read in two sets of data with Pandas
    * Join the dataframes using Pandas concat
    * Create SQL table with the dataframe
    * Create visualizations using Seaborn
    * Data dictionary
    * Annotate

## Run the Program

    * source venv/Scripts/activate - Virtual Environment activation
    * pip freeze requirements.txt - list of the packages installed
    * open notebook
    * run the programs
    * edit if necessary

## Conclusion

Based on the data that was collected there does not appear to be any specific connection between temperature of an area and the amount of ufo sightings that are reported. The graphs seem to go up and down and there is not a noticable trend. There would need to be more data to get a better analysis of this topic.

## Data Dictionary

     UFO data was taken from https://www.kaggle.com/search?q=ufo+sightings+us
        
        Event.Date- Date of the reported ufo sighting
        Shape- Shape of the flying object 
        Location- City/Town of the reported sighting
        State- State of the reported sighting
        Country- USA or Canada
        Source- Where the report came from
        USA- 1 if the report is in the USA 0 if it is not
        unnamed- Unused column

     Climate data was taken from https://www.kaggle.com/datasets/jmcslk/2018-quarterly-us-weather-data-by-state

        Unnamed- Gives the row number of the data set
        State- Climate reports are categorized by state location
        avg_hum_spr- Average humidity for the spring season
        avg_hum_sum- Average humidity for the summer season 
        avg_hum_fall- Average humidity for the fall season 
        avg_hum_wint- Average humidity for the winter season
        avg_temp_spr- Average temperature for the spring season
        avg_temp_sum- Average temperature for the summer season
        avg_temp_fall- Average temperature for the fall season
        avg_temp_wint- Average temperature for the winter season
        avg_precip_spr- Average precipitation for the spring season 
        avg_precip_sum- Average precipitation for the summer season 
        avg_precip_fall- Average precipitation for the fall season
        avg_precip_wint- Average precipitation for the winter season
        avg_pressure_spr- Average pressure for the spring season
        avg_pressure_sum- Average pressure for the summer season
        avg_pressure_fall- Average pressure for the fall season
        avg_pressure_wint- Average pressure for the winter season


These csv files are kept in the data folder that is in the Github repo.

