
### **Project Requirements:**

- [x] The app must be built using React and Redux.
- [x] The app must be version controlled with Git, and the repository hosted on GitHub.
- [x] You must use a project management tool (**GitHub Projects**, ~~Trello~~, _etc..._)
- [x] Write a README.md that documents the project including:
  - [x] Wireframes
  - [x] Technologies used
  - [x] Application Features
  - [x] Future update plans
- [x] Write unit tests for the app's components using Jest
- [x] Write E2E tests for the application.
- [x] The app is available on both desktop and mobile.
- [x] Users see an intial view of the data when first visiting the app.
- [x] Users can search the data using terms.
- [x] users can filter the data based on categories that are predefined.
- [x] Users are show a detail view(modal or new page/route) when they select an item.
- [x] Users are delighted with a cohesive design system.
- [x] users are delighted with animations and transitions.
- [x] users are able to leave an error state.
  - Note: it is understood that how media assets like videos and images are sent to the client, may impact performance. It is okay to have a score below 90 for Performance **if** they are related to media from Reddit.

## Project Setup

### **The API**

The following is a description from Codecademy of the API used for this project:

> " For this project, we will be using the Reddit JSON API. There is no maintained documentation but the API is simple enough to use. We will provide you with some pointers on how to use it.
>
> Note that Reddit has 2 APIs: the official API and an undocumented JSON API. You are welcome to use either APIs but we recommend using the JSON API because it doesn’t require an OAuth workflow. Using the JSON API does have limitations such as no write operations. For the purposes of this project, we find the JSON API adequate.
>
> You can take any Reddit URL, add .json at the end of it, and get JSON. For example, if you want to get the Popular page data in JSON:
>
> Original URL: https://www.reddit.com/r/popular/<br>
> JSON URL: https://www.reddit.com/r/popular.json "

## Technologies Used

This project makes use of the following technologies:

### **React:**

For building out the user interface of the application.

### **Redux:**

For application state management.

### **Redux-Persist:**

To save the user's bookmarks and theme preference to local storage.

### **React-Markdown:**

To display any markdown returned from the API.

### **React-Router:**

to handle internal routing.

### **Cypress**

For writing and executing E2E tests.

## Features

- ### Search
  Users are able to search for both subreddits and individual posts with a search term.
- ### Home Page
  Users are greeted by a home page, displaying today's popular posts and trending subreddits as well as a carousel of world news items.
- ### Subreddit Navigation
  Users can also navigate to individual subreddits to view their posts.
- ### Post Navigation
  Users can interact with posts to view more detailed information, including: a description of the post's containing subreddit, 30 of the most recent comments posted by Reddit users, a larger view of the post's media if any exist.
- ### Post Filtering
  Users can filter posts by Reddit's available categories: hot, top, and new. User's can further filter "top" results by year, month, day, and all time.
- ### Post Bookmarking
  Users are able to save and view post's they enjoy.
- ### Continuous Integration
  This application is hosted through [netlify](https://www.netlify.com/) with a CI workflow to automatically deploy changes pushed to the main branch.



