## NewsApp

This is a News app built using the MVVM architecture, Retrofit, Room, Coroutines, and Navigation Components. The app allows users to browse news articles, add them to favorites, and search for news.

## Features
- Browse news articles from various sources
- Add news articles to favorites
- Search for news articles by keyword
- View detailed news article with images and descriptions
- Browse News Articles
- The app retrieves news articles from the News API and displays them in a RecyclerView. Users can browse through the articles and tap on them to view the detailed article.

## Add News Articles to Favorites
Users can add news articles to their favorites by tapping on the "heart" icon next to each article. The articles are then saved to a local database using Room, which allows the user to access them even when offline.

## Search for News Articles
The app allows users to search for news articles by entering a keyword in the search bar. The app then retrieves articles from the News API that match the keyword and displays them in a RecyclerView.

## View Detailed News Article
Users can view a detailed news article by tapping on an article in the RecyclerView. The app then displays the article's title, author, description, and image. Users can also navigate to the original article by tapping on the "Read More" button.

## Architecture and Libraries Used
The app was built using the Model-View-ViewModel (MVVM) architecture pattern. The following libraries were used:

- Retrofit: Used to make API calls to the News API and retrieve news articles.
- Room: Used to save news articles to a local database.
- Coroutines: Used to handle asynchronous tasks such as API calls and database operations.
- Navigation Components: Used to navigate between fragments in the app.

## Getting Started
To use this app, you will need to obtain an API key from News API. Once you have your API key, you will need to replace the API key in the gradle.properties file with your own API key.

<pre>
<code>
NEWS_API_KEY="YOUR_API_KEY_HERE"
</code>
</pre>




