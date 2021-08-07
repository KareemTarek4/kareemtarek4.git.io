Cyclists Data Case Study 

Ask

Cyclistic is a fictional cycling company that offers various subscription plans to its customers, with over 600 stations all over the city, the packages cover both member and casual cyclists, the executive team figured that memberships harvests more revenue for the company. So we’re about to explore that 

My task, with the help of the team would first be identifying the differences and behaviors between the data of both casual and member users, then after careful investigation of the data provided we should be able to come up with clever ways to convert a casual user to a member 



Prepare And Process 

The data was provided by Motivate International Inc (License Provided), a company that operates the City of Chicago’s Divvy bicycle sharing service. The source makes the data reliable, original and cited. The information is new too as it dates Year 2021. Moreover, the company grants full access to the data.

As for the data itself, sure some insights can be extracted, for instance, types of riders are provided (casual or annual), bicycle type,  as well as the duration of each ride, those metrics would be investigated carefully to try find patterns. No duplicates were found, also each column seems to be in a correct format. 

I managed to upload the data to a google drive in a spreadsheet for other data analyst is to join the case study. Data integrity was checked by inspecting the column’s correct format, checking for duplications and the size of the data. However, rides with 0 ride duration time where cleaned from the data to avoid outliners. New calculated fields where created through the software to represent the new columns, a dashboard was also created using the app for presenting. Finaly, As you see here Microsoft Power Point is then used for documentation and to present important information and illustrations. 

Analyze

Two dashboards where outputted using Tableau:-

1. For Overall Analysis to find the following:-
    1. Minimum ride length is  0, meaning there are rides logged with 0 duration, could be a problem with the system.
    2. Maximum ride length is 37 days, need more investigation by splitting into casual and member groups.
    3. Average ride length is 1/2 an hour, need to split for both member and casual users.
    4. Most rides are performed on the weekend (Saturday & Sunday’s)
    5. More rides are carried as we approach spring, away from winter (Months May And April)
A more detailed analysis was performed to have more insights 
1. For Casual vs Member Analysis:-
    1. Member users take more rides than casual users
    2. Maximum ride duration for member was 1, for casual was 37
    3. Minimum was zero for both users.
    4. Average duration for casual users was 38 but 15  minutes for member users.
    5. Most casual users take rides on Saturday and Sunday (the weekend), while the ride count of the members is distributed nearly throughout the week 

Conclusion

After careful investigation and by using the visualizations created, we can conclude the following :-
* Member users represent more number of rides than casual ones, which is a confirmation on the stakeholder’s hypothesis that members return more revenue.
* Number of rides spikes up in spring so it might me a good idea to have a good package deals (members) at that period.
* Both maximum and average duration for a ride is done by casual users, so maybe those people can be contacted for a membership, and they can be explained why that might be cheaper option.
* Casual users would rent bicycles on the weekend more often, maybe include flexible membership, or suggest weekend offer 

Next steps:
* Try to include more data in the ride logging, for example, a rider id, so later on we would create segmented packages or ads.
* Also from a seasonal perspective, data was only provided from nearly the first two quarters only, more data for the upcoming quarters should be of great benefit.

