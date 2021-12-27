# UFOs

**Project Overview**

This project utilizes JavaScript as the coding language. JavaScript is a well-established coding language that was designed to improve webpages by enhancing the user experience. Javascript enhances websites by providing front-end functionality, customization, dashboards (such as maps or graphs), and allows for user input to create dynamic web pages. Javascript enables websites to be visually appealing and interactive.

In this project, I built on the module repository by updating the table we created in the module which organizes UFO data that is stored as a JavaScript array, or list. This table have the ability to filter data based on certain criteria and was created using JavaScript as the primary coding language. 

I also created filters to make the table fully dynamic, meaning that it will react to user input, and I then place the table into an HTML file for easy viewing. I then customize the webpage using Bootstrap, and equiped the table with several fully functional filters that will allow users to interact with my visualizations.

**Coding Methods**

In this project
- We built and deployed JavaScript functions, including built-in functions.
- Converted JavaScript functions to arrow functions.
- Built and deployed forEach (JavaScript for loop).
- Created, populated, and dynamically filtered the table using JavaScript and HTML (convert a Javascript array into an HTML Table)

Project Deliverables
Deliverable 1: Filter UFO sightings on multiple criteria
Deliverable 2: A written report on the UFO analysis (README.md)

**Results**

I created a user-friendly webpage that display UFO sighting data with a filter table that allows users to easily filter on various criteria. The criteria includes date, city, state, and shape. On the webpage, there is no need to for refresh button because the tables update in real time. When you filter, the selection can be broad. For example, in addition to being able to filter by date as initially done in the module, we can now filter by selecting a country = United States, state = California, and city = Roswell. The global view of the unfiltered webpage is shown in the link below:

![UFO webpage.png](https://github.com/FUNMIIB/UFOs/blob/main/static/images/UFO%20webpage.png)

The tables will be updated in real time and there is no need for a refresh buton. The webpage can be filtered to show information for a specific date, state, country as shown in the link below when filtered by the date 1/13/2021.

![UFO webpage_filtered.png](https://github.com/FUNMIIB/UFOs/blob/main/static/images/UFO%20webpage_filtered.png)

**Summary**
One main advantage of this webpage is that users can input different criteria to search without the need for a submit button. 

**Drawbacks**
One major drawback is that the filter is case sensitive, if an item is entered in upper case, the results may not be accurate. 
Another draw back is that the search options don't provide enough information about the search options. For example, users may not know the date range of the data so the user may enter a date that the data does not have. 
Finally, the users may not know which shape options are available for search.

**Recommendations for further development**
- We can remove case-sensitivity in the textbox search fields
- We can add a calendar selection option for the date search and also add a drop down menu for the shape field to make the webpage more user friendly.