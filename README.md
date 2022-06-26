# LSE-Fourth-Rev-Covid-Analysis
LSE_DA_COVID_analysis
Assignment 2: Summary
Did I notice anything interesting about the Data?

The Data starts from early January 2020, back when there had only been 1 confirmed case not in Asia, which is interesting to see how on top of things they were, as well as how their were only 2 rows that had any empty data in them, compared to the thousands of rows that take up the data frames.
Does the DataFrame have a default index?
Yes the DataFrames have default index’s with both the vaccinated and cases data frames having an index of numbers starting at 0 and going up to 7584 in increments of 1.

What are some initial insights I have discovered?

I have discovered that since the data starts from January 2020, it heavily effects the statistics of the Vaccinated.csv data, since it took a long time for the Covid Vaccine to be made and tested, there are months of data of just 0’s across all the vaccine categories, it probably would have been better to focus on the vaccine data from when the vaccine went into effect, since the 25 percentile and the 50 percentile data is heavily effected by the months of 0 vaccines, since the vaccines hadn’t even been made or tested by the time that data was collected.

Other insights I have discovered are that some Provinces/States got of much lighter compared to others, Like how Bermuda had 95 deaths, the Cayman Isles had 2 and the Others had 138,237 deaths over the same time frame, most likely due to the lower population of the different provinces, but the difference in the amount of deaths is quite striking, especially when in a lot of areas there was a spike in the number of deaths between 20/01/2021 to 24/03/2021.  

How has the number of vaccinated individuals changed over time? What might these changes indicate? Include reasons to support your rationale.

The data shows a massive jump in vaccinated individuals once the vaccines actually were made, but a large slump of no vaccines since the vaccines hadn’t been made before, once the vaccines went into effect their was a few weeks of initial tentativeness before the number of vaccinated individuals quickly shot up, this is likely due to a combination of vaccine weariness due to how quickly it came into being since vaccines usually take years to develop, and also the initial policy of vaccines being given to at risk individuals, the sick and the elderly, first.

Once the vaccine weariness wore off and the government rolled out the vaccine to more and more of the population, the amount of people who got vaccinated spiked quite rapidly, before eventually subsiding since people had been vaccinated, their was no point to getting vaccinated a second time, so the number of people vaccinated each day started to decline quite rapidly after the initial jump in vaccinated individuals.

On which date(s) are there values missing, and from which columns and rows are these values missing? Which states or provinces do the missing values belong to?
The Dates 21/09/2020 and 22/09/2020 are the dates where values are missing, the missing data is in the columns: Deaths, Cases, Recovered, Hospitalised.
The states or provinces of the missing data is Bermuda

Is there anything unusual about the filtered Gibraltar DataFrame? Include Reasons to support your rationale.

After 2021-08-04 the number of people Recovered just seems to go down to 0 from 4670 from the previous day, and after 2021-10-12 the number of people Hospitalised goes down to 0 from 876 the previous day, which is highly unusual considering the data collected we the total number of people from each Column throughout the entire period, if the data isn’t wrong that would imply the 876 hospitalised people suddenly were never hospitalised, and the 4670 recovered people had a relapse.
Likely this is just an input error that could be fixed, but still there is a quite large section of incomplete data in the Gibraltar DataFrame.
