# Group 10 Music Data

[Group 10 Git Repository](https://github.com/annachk/Group10-Final-INST377SP2021)

[Group 10 Heroku Instance](https://group10-final-inst377.herokuapp.com/index.html)

## Title

Music Data

## Description

We intend to develop a system that can assist users with inquiries such as predicting future trends, which genres and artists could be involved in the next big hit, when retro concepts will become popular again, and so on. 

When you open the application, you will be brought to our home page which will display the top ten artists and albums. From that page, you can use the navigation bar on the top left corner of the screen to navigate to the search page or the custom input page. The breakdown of our pages are as follows:

- The home page will have the top 10 artists and albums displayed. 
- The search page will allow the user to search for a specific song, genre, or artist.
- The custom input page will allow users to input their own music into the database.

## Target Browsers

The target browsers for our application are most, if not all, devices with web browser capabilities. Ideally, the user should use the latest versions of their technology, but our application should be avaialable to most softwares including the most popular ones like IOS, Android, Google Chrome, etc.

## Link to User Manual: [User Manual Link](#user-manual)
 
## Link to Developer Manual: [Developer Manual Link](#developer-manual)

# User Manual

You will notice in the top left corner of the page the menu button this is how you can naavigate from page to page within our application. The three pages we have are: Home, Search, and Custom Input. 

The Home page is a quick rundown of the top 10 albums and top 10 songs currently ranked in our database.  

The search page allows for the user to search by Genre Song or Artist

The last page the Custom Input page allows the user to input song names, artist, and genre and offers space for additional information and a link to the song. 

# Developer Manual

## How to install the application and all dependencies

To download our actual project, just select the clone repository button for this repository to clone it to your computer. Once you have cloned it, you could also fork it by clicking on the 'fork' button in the upper right hand corner. This allows you to use it as a repository for only your device. Using Github desktop is the most straight-forward way to clone the repository. You can find information about Github Desktop here: https://desktop.github.com/

### API 

We utalized a database from INST327 
* Our database is constructed of 7 tables and holds data from Spotify on genres, songs, artists, and their respective characteristics from the years 1921-2020
* `'GET'` is what allows the user to retrieve the data from our databases. When the top ten songs and albums display and the search results are acquired it is by using the `'GET'` function
* `'POST'` is what allows the user to input their own information to the databse. The Custom Input page uses the `'POST'` method for when the user adds a song using the form. 

### Bulma

We used Bulma, which is a CSS framework that allows users to style their HTML easily and nicely. You can find the instructions on how to install Bulma here: *https://bulma.io/documentation/overview/start/*. 

The simplest way to do this is by using npm to install it. Open a new terminal and enter *“npm install bulma”*.


### Known Bugs

* Our home page does not currently display the top ten albums and songs. Our team has been working on a way to fix this as it is an important part of our web page.
* We have been unable to figure out the form submission. We have the incrementation method set in place like in class, but there is still an error with the ID being null. The incrementation method should cover that so there must be something else in our code that is blocking that process from happening.
* We descided to take out our about page because we wanted to focus on the functionality of the app. We believe the about page is important and would develop it with more time, but we wanted the main functions of the app to work first.
* Adjusted some content as some API’s were not found in our database.



### Future Development

* Display the top ten songs and albums on the home page
* Continue working on making the form submit data to the server
* Create our about page to describe our mission
* Work out any bugs we find along the way
