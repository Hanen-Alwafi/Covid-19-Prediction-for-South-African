# Covid-19-Prediction-for-South-African
 Covid 19 prediction for South African analyzing and predicting the coronavirus(COVID-19) cases and death cases of South Africa using "Power Bi" for visualizations and linear regression in python for the prediction model.

II. INTRODUCTION


The coronavirus (COVID-19) that was first reported at the end of 2019 has impacted
almost every aspect of life as we know it. Since then, researchers are still working on discovering
the trends about the pandemic and when it will end. In our project, we are enthusiastic about
analyzing and visualizing South Africa provinces' cases, deaths, and recoveries. Also, we are
interested to know more about the prediction cases and deaths in the
country. We will approach this prediction using the linear regression model


III. PROBLEM DESCRIPTION


In this project, we are willing to explore the timeline of cases, deaths, and recoveries in
each province of South Africa. Also, we want to know which group age and gender are most
affected. So that can help the country put more effort to low the cases for the high rate cases or
deaths provinces. In addition, knowing the expected cases and deaths for the future could avoid
such a problem that the country offers more vaccination or takes a step to make the vaccination
mandatory for work or go out in public.


DATASET DESCRIPTION


We are using the Coronavirus (COVID-19) Data Repository for South Africa, created,
maintained, and hosted by the Data Science for Social Impact research group, led by Dr. Vukosi
Marivate, at the University of Pretoria. The data is as accurate as possible to collate the COVID
19 reporting data from NICD and DoH[1]. They update that data almost every day once there is
an official report or statement. We used three CSV files(timeline cumulative confirmed cases,
deaths, and recoveries). Each file has a date column from March 2020 up to date. Also, they
contain the cumulative province timeline for each province plus the total. The province's
columns. Also, for analyzing the gender and age count, we used another data for 2021.

 

 

METHODOLOGY


We used python language on Jupyter notebook and Power Bi business analytics service
by Microsoft for creating a dashboard that can be published to the public. We start off using
python by exploring the data to get a high-level insight of how our data is structured. We
extracted and cleaned the data and then plotted with histograms for visualizations. We dropped
the rows that contained the null values. Then we used a linear regression model using the total as
the target and date as the feature to predict the timeline cases and deaths. Then we extract the
prediction for visualization. After that, we used Power Bi to make the dashboard interface for the
users.



	
VII. CONCLUSIONS


This analysis was conducted to increase people's awareness to limit the spread of the
disease in the country; half of the solution is to educate the citizens and work with the
government to reduce the number of cases and limit their spread. This analysis showed an
increase in the number of deaths for 29/10/2021 to 10/10/2021, so it is necessary to take the required
vaccinations and limit the gathering of people in events and workplaces to reduce the spread of
this disease so that the government can control the disease in each region to return to normal life
and restore the economy and tourism to the country.




VII.REFERENCES
[1] https://github.com/dsfsi/covid19za 

