# C# Bootstrap BingNewsAPI WebApp

## Objective
Create a web application that shows the 20 most recent Bing news articles and a tally of their providers. 

## Deliverable
The application can be found at [DrewDakinsFluentWebApp](https://fluentwebapp.azurewebsites.net/) 

## Technologies Used
```
Microsoft Visual Studios 2017
Microsoft Azure
Bing Search API 
```

## Approach and Details
The project is an ASP.NET Core Web App written in C#. Stylistic elements based off of Bootstrap. It's hosted on Azure under free tier. A load balancer, auto scaling group, or route procedure could be applied if necessary, but in order to stay in free tier it is not.

The Page Model holds two objects list which represent both the News Titles and the News Providers. This could be expanded to include others but I left it as just that detail.

Basically the API is called within the Page Model and using Get() and Post() functions displays the result of the API call. You can refresh the list by selecting the "Click to Refresh Results" button at the top.

## Screenshots

Below are the screenshots of the application interfance and how the JSON object was parsed

![alt_text](/images/AppPage.PNG)
![alt_text](/images/NewsProviderCode.PNG)
![alt_text](/images/NewsTitleCode.PNG)
