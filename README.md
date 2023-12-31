## About TravelStrats

Are you a wanderlust enthusiast who loves to explore new destinations but often finds the process of planning your adventures overwhelming? Enter TravelStrats, your ultimate travel companion and guide, designed to simplify and enrich your travel experiences.

### The Purpose

TravelStrats is born out of a passion for travel and the desire to streamline the vacation planning process. In a world where information overload is commonplace, this dynamic platform has been meticulously crafted to empower travelers with curated, personalized travel recommendations, helping them make the most of their precious time away from home.

As the creator of this project, I understand the challenges that come with planning trips to unfamiliar destinations. It's all too common to spend hours scouring the internet for things to do, places to visit, and the best dining spots. With TravelStrats, I set out to revolutionize this process.

Our mission is simple: to be your one-stop resource for discovering the hidden gems, must-see attractions, and authentic experiences that make each journey unforgettable. TravelStrats combines cutting-edge technology with real-time data from a trusted API, ensuring that you have access to the latest and most reliable information about your chosen destination.

## Key Features

- **Tailored Recommendations**: TravelStrats utilizes advanced algorithms to provide you with personalized recommendations based on your interests, budget, and travel dates. Say goodbye to generic advice; say hello to customized travel plans.

- **Organized Itineraries**: Stay organized and stress-free with our built-in itinerary planner. TravelStrats helps you create a detailed schedule, complete with activity times and locations, ensuring that you make the most of every moment during your trip.

- **Real-Time Updates**: Our platform continuously updates information from our API source, keeping you informed about any changes to your travel plans. Whether it's a sudden attraction closure or a new must-visit spot, you'll always have the latest insights at your fingertips.

- **Community Engagement**: Join a community of fellow travelers, share your experiences, and discover travel tips and insights from others who have explored the same destinations. TravelStrats fosters a sense of belonging among globe-trotters.

### Future Development

TravelStrats is a dynamic project that is constantly evolving. While it is still in its early stages, our team is committed to expanding its capabilities and enhancing user experiences. We have exciting plans for integrating even more features, such as travel booking options and real-time weather updates, to make your travel planning even more seamless.

We believe that every journey is an opportunity for self-discovery and enrichment. With TravelStrats, we aim to empower travelers to embark on unforgettable adventures, explore new horizons, and create lasting memories.


## How it works
On the main menu, you are given 2 text boxs to enter your text. The top being Location, that's where you will input where you would like to travel to. This could be
* "Tokyo, Japan"
* "London, UK"
* "Lima, Peru"
* etc

The next text box is to count how many days you plan on staying at that location. A visual reference is show below

![Dashboard](Screenshots/Top_dash.png)


![Bottom Dashboard](Screenshots/Bottom_dash.png)

Once you have inputed the data into the text box and hit "Submit", you should be taken to a place where it shows you your data. For example, we will be inputting "Tokyo, Japan" and we'll stay there for '4' days. A visual is show below.

![Top Results page](Screenshots/Top_resultPage.png)


![Bottom Results page](Screenshots/Bottom_resultPage.png)

# How to run the project for yourself

In order to start, you must first open you terminal/shell and open the directory in which you cloned the project and cd to the project name.

```
C: \path\to\Erick435.github.io>
```

Then you will need to install a few required items needed to run the project but not to worry just copy and paste!

```
npm install react react-helmet react-router-dom axios react-spinners @emotion/react
```

Once you have everything installed, you can run the React App by typing "npm start" and this will automatically open a window screen for you.

```
Erick435.github.io> npm start
```
If for any reason a new window does not open up automatically, then you can open a browser of your choice (preferrably Chrome) and in the url type:
>localhost:3000

![View of Home Page](Screenshots/Top_dash.png)


In order to be able to search for the data (in this case the destination and how many days the person is staying), you must first get an API key since the API I'm using is not mine and requires to get one.

To get started, click [Here](https://rapidapi.com/nabeeldev1340/api/ai-trip-planner/)

You should be directed to this screen, and then click on "Pricing" where the red arrow is pointing.

![RAPIDAPI_price](Screenshots/RAPIDAPI_page.png)

It should direct you to another screen where you will be asked which subscription you would like to have. Click on the subscribe button under "Basic".

![RAPIDAPI_pricing_page](Screenshots/RAPIDAPI_pricing.jpg)

* Just a quick reminder, with this package, you will only have 10 calls per account (you can only search/run the project 10x)

![RAPIDAPI_Account_creation](Screenshots/RAPIDAPI_account.jpg)

Once you have created you account, head back to the [AI Trip Planner Api](https://rapidapi.com/nabeeldev1340/api/ai-trip-planner/). You should be able to see your API key now, you can copy the key, from the right side.

![RAPIDAPI_gettingKey](Screenshots/API_KEY.jpg)

Great! Now you have your API key, all you need to do now is just add that key to the Dashboard.jsx file. Which I will show you just in case.

I have the project running on VSCode so my files may or may not look a little bit different from your machine. When cloning and opening the project, to navigate to the Dashboard.jsx file, I highlight the folders/files we need to go to in order to find it.

>src -> components -> Dashboard.jsx

![Project_files](Screenshots/Project_directory.jpg)

Once we open the code, we have to find the line where we need add our API key located at.

> X-RapidAPI-Key': ''

![input_API_KEY](Screenshots/Dashboard_file.jpg)

Save the project and open your terminal or your cmd and navigate to the project.

![Server_Run](Screenshots/Start_server.jpg)

This will open up a new Window and you have now successfully started the server and React application.

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:
### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
"# TravelStrats" 
