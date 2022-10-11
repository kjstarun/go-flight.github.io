Motive of this project: A flight booking site with functionalities:

The Home page UI:

Version-1:
The user can:
    1. Search flights between two cities.
    2. Can select the date of travel.
    3. Can select the count of passengers.
    4. Can see the search results with timing and price in a new page.

Functionalities of the UI: (Usage)
In home page UI:
1. From (input field):
    The user can enter the origin city in this field.
2. To (input field):
    The user can enter the destination city in this field.
3. Date (date selection):
    The user can select the date of travel in the dropdown calendar.
4. Count (input field):
    The user can select the count of passengers traveling.
5. Search (button):
    The user can click on this button and it will redirect to the new page.

Redirected UI:
1. The user can see the search results in the new page as a list.
2. At first, the flight number will be displayed.
3. At second, the departure time will be displayed.
4. At third, the arrival time will be displayed.
5. At fourth, the price of the flight will be displayed.
6. At last, the book now button will be displayed.


The below feature will be continued in the Version - 2 later.
- On clicking the book now button, the input form for passenger details will be displayed.



Updated with current functionalities:

The hamburger menu is working only on the First UI (without functionalities)

 Possible testcases:
 - Flight search between: (case-sensitive).
      - Chennai to Coimbatore.
      - Delhi to Bangalore.
 - This will show the flight results and proceed further.
 - If the search is correct, it will show the flight search results of the data and by clicking on the flight,
 - The page redirects to flight page and on that the user can see the flight details and the passeneger input forms as per the count of passengers given by the user.
 - If the search is not correct, it will throw a message in the UI and clicking by a button will redirect you again you to the search page.
