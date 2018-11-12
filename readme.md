# THE PRICE IS RIGHT (Code Louisville project)

## Description  
In searching for events going on around Louisville, I have often found myself searching for a centralized site containing activities happening around town.  This site aims to provide a comprehensive list of events in order to ease the search.  
  

## Packages you will need:
* requests  
* numpy  
  
  
  
CSS  
* flex_bootstrap.css  
* https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css  
* https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css
  
  
Javascript/JQuery  
* script/LOU_JS.js  
* script/jquery-3.3.1.min.js



## Funtionality  
The following functionality has been added to this site:
  
* Bootstrap was used in the page layout.
* Flexbox was also used.
* JQuery was used to create the background fade in/fade out  
* JQuery was also used to filter the event list  
* Form at bottom of page allows user to add an event (although not posted to database)  
* This site is also available through github/pages using the link below:  
  https://koryvette.github.io/eventcalendar
* Testing was done on the github/pages link to ensure various screen sizes and browsers were functional.


  
## Known Issues  
Here are a few known issues with the site:  
* This site is not currently connected to a database.  All of the events listed within this site were exported from an MS Access database to an HTML format.  From there, the event data was copied/pasted to the appropriate sites.  
* "New Event" form does not post information.  This is a mock-up form to be used later when tied to a database.
* Dates of "New Event" form currently display 31 days for all 12 months.  
* Columns do not fully extend across table, leaving empty space on some pages.  
* Columns also do not align when there are more than one table on a page.


