# **Overview**
Using Tableau to visualize bike sharing data from New York City in order to present visualizations to an angel investor to determine if opening a bike sharing company in Des Moines, Iowa would be a profitable decision.

**LINK  TO TABLEAU PUBLIC** https://public.tableau.com/app/profile/john.kuchinski/viz/CitiBike_16778759674160/ModuleStory?publish=yes

## **Software**
1. Tableau
2. Pandas
3. Jupyter Notebook


# **Results**

Prior to putting any of the data into the Tableau server we were asked to create a Jupyter Notebook in order to clean and change some data types that we had been working with throughout the module. We were asked to change one of the date columns in order to be formatted from overall seconds to be formatted to display the date and the time of the bike rental. This would set us up for success as it would give us an easier time of displaying the data in a digestible form that would be more widely accepted. After changing this data type I was asked to save the dataframe as a csv file and then upload this csv file as a text file into the Tableau Public software to begin creating our visualizations.

## **_Item 1- Trip Duration By Time_**

The first result that was secured by this data inquiry was that most bike rides from the data set lasted roughly 5-15 minutes, demonstrated by the visual below.

![Screenshot 2023-03-03 at 4 08 15 PM](https://user-images.githubusercontent.com/114188120/222829657-fb71db9e-00bb-4f3e-9486-52a20362493e.png)

## **_Item 2 - Trip Duration Date Time_**

The next item on our agenda was to determine if there was any differnce in the average duration based on the gender of the rider.

![Screenshot 2023-03-03 at 4 09 23 PM](https://user-images.githubusercontent.com/114188120/222829850-975bf1e1-f6a5-4cba-9b3c-08ab0047764e.png)

So far based on the two graphics we can see that even though the numbers may not be exact, they contain consistent trends showing the average duration of the rides is not greatly effected by the riders' gender. The most apparent thing so far as that it appears that we have a much higher volume of riders male riders as compared to those that identify as female or those that were left as undefined.

## **_Items 3 & 4 - Stoptime & Stoptime by Gender_**

The next graph we were asked to provide was a heatmap that would display the average start and stop times of the users as whole, and then the visualization directly after would provide a break down of the same items along with accounting for the genders of the riders.

![Screenshot 2023-03-03 at 4 13 29 PM](https://user-images.githubusercontent.com/114188120/222830436-687dda86-de61-4ceb-8635-b24daec6c227.png)

![Screenshot 2023-03-03 at 4 15 53 PM](https://user-images.githubusercontent.com/114188120/222830871-e4767a60-2ecb-4e30-acd8-c3ec6b56f578.png)

## **_Item 5- Breakdown of all previous data along with applied calculated field_**

![Screenshot 2023-03-03 at 4 27 39 PM](https://user-images.githubusercontent.com/114188120/222832624-4394f99e-e4ee-4070-baa8-08bdbb6bff57.png)


This graphic now takes some our first graphics and brings them all together in order to get a "Total" picture. We have now displayed all relevant data that we have been asked to use in order to analyze this decision. We have brought the average length of rides, the time of day, the gender of the rider, as well as the status of the rider in this program as a subscriber or as a one time customer. We have also applied the filters so that we can easliy search through the data in the future to answer other similar questions regarding these patrons. This visualization I believe could be there cherry on top in order for us to complete our analysis and make an informed decision on opening a bike sharing company in another location.

## **_Misc. Items used through module to gain additional information_**

### **Top Staring & Ending Locations**

![top_starting_locations](https://user-images.githubusercontent.com/114188120/222834179-f6949348-9f08-40ca-b488-bab0c93fbbcb.png)

![top_ending_locations](https://user-images.githubusercontent.com/114188120/222834203-83f4b40d-0718-43e2-a5d2-cc4b81387edd.png)

### **Gender Breakdown**

![gender_breakdown](https://user-images.githubusercontent.com/114188120/222834219-fac3f9b4-d2e4-425d-8395-c18b4f6cfe28.png)

### **Demonstration of creating a basic caluclated field in order to change the values of 0, 1, 2, into "strings" of 'male' , 'female', and 'Uknown'**

![basic_calculated_field](https://user-images.githubusercontent.com/114188120/222834235-d219df1a-9bdc-47c2-af2a-9156284c64c3.png)

### **Give overall view of which bikes are most utilized**

![bike_utilization](https://user-images.githubusercontent.com/114188120/222834250-8607f812-5a26-4e6b-93d3-7fa96f65c5de.png)


# **Summary**
