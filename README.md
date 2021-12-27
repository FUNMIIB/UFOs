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

I created a user-friendly webpage that display UFO sighting data with a filter table that allows users to easily filter on various criteria. The criteria includes date, city, state, and shape. On the webpage, there is no need to for refresh button because the tables update in real time. When you filter, the selection can be broad. For example, in addition to being able to filter by date as initially done in the module, we can now filter by selecting a country = United States, state = California, and city = Roswell. The webpage view when filtered is shown in the link below:

![UFO webpage.png](https://github.com/FUNMIIB/UFOs/blob/main/static/images/UFO%20webpage.png)



The displayed results are dynamically filtered as you update the form field entries. There is no needed Submit or Refresh button as the tables update in real time. Filter selection can be broad such as only selecting a country and state like the United States, California.

Filter results can be more narrowed such as specifying the date, a city in one state and focusing on one type of shape such as "light".


**Summary**
One main advantage of this webpage is that 

users can search upon multiple criteria at one time and there is no submit button needed. However, there are also some drawbacks. The main draw backs all have to do with the fact that the search options don't provide much idea as to available options to search on. The current fields are all text boxes and these can allow for a lot of user errors or just simply misinterpretation. This makes the data analysis ineffective and time consuming.

Drawbacks

The filter method is case sensitive. Therefore if a user entered any items in upper case, the search results would not return properly. For example, if the user entered a city as "Ventura" instead of "ventura", the city would not return in the filtered data.
The user may not know exactly what period the data is from, so the user might type in dates that we don't have data for. For the date filter, the user should be able to click through a calendar.
The same issue with the Shape field, without knowing what the shape options are, the user will not know what terms to search for.
Recommendations for further development:

Remove case-sensitivity in all the textbox search fields.
Add a calendar selection option instead of textbox field for the Date search.
Add a drop down menu for the Shape field. This would be more user friendly as a drop down option than the textbox.
The text in the Comments section should be parsed and cleaned as there are strange symbols that can appear. These should be eliminated to make reading the comments more user-friendly.