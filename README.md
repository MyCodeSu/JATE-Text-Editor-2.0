# JATE-Text-Editor-2.0

### Description

Web app that stores user entered data into indexedDB and persists. User has options to run this app offline through the usage of service workers and bundling, install button on the top left corner. 

### Acceptance Criteria

GIVEN a text editor web application  
WHEN I open my application in my editor  
THEN I should see a client-server folder structure  
WHEN I run `npm start` from the root directory  
THEN I find that my application should start up the back end and serve the client  
WHEN I run the text editor application from my terminal  
THEN I find that my JavaScript files have been bundled using webpack  
WHEN I run my webpack plugins  
THEN I find that I have a generated HTML file, service worker, and a manifest file  
WHEN I use next-gen JavaScript in my application  
THEN I find that the text editor still functions in the browser without errors  
WHEN I open the text editor  
THEN I find that IndexedDB has immediately created a database storage  
WHEN I enter content and subsequently click off of the DOM window  
THEN I find that the content in the text editor has been saved with IndexedDB  
WHEN I reopen the text editor after closing it  
THEN I find that the content in the text editor has been retrieved from our IndexedDB database  
WHEN I click on the Install button  
THEN I download my web application as an icon on my desktop  
WHEN I load my web application  
THEN I should have a registered service worker using Workbox  
WHEN I register a service worker  
THEN I should have my static assets precached upon loading along with subsequent pages and static assets  
WHEN I deploy to Heroku  
THEN I should have proper build scripts for a webpack application  

![badge](https://img.shields.io/badge/license-lgpl-brightorange)


### Deployed link:

Not available. See following errors for heroku deploy attempts. 

<img src="./client/dist/assets/icons/Screen Shot 2022-10-10 at 1.36.32 AM.png" alt="heroku deployment error">

### Screenshots 


<img src="./client/dist/assets/icons/Screen Shot 2022-10-10 at 1.38.16 AM.png" alt="Michael's note taking page">

### License

_Project License: gpl_

To understand this license, please view the [license description]( https://opensource.org/licenses#:~:text=GNU%20Library%20or%20%22Lesser%22%20General%20Public%20License%20(LGPL)).

