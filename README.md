# Samachar - News App in Flutter

## Introduction

A complete beautiful news app in flutter. Multiple themes, search functionality, 3D navigation and much more. This News App is a simple mobile application developed using flutter. It allows users to stay up-to-date with the latest news from various categories such as Technology, Sports, Entertainment, and more. The app fetches news data from a reliable news API and presents it in a user-friendly interface, making it easy for users to browse and read articles of interest.

## Features

- Browse news articles from different categories.
- View detailed information for each news article, including title, description, and source.
- Share articles with friends through various communication channels.
- User-friendly and intuitive interface for a seamless news browsing experience.

## Other features
✔️ Sound NullSafety

## Architechture
✔️ Clean Architechture <br />

## State Management
✔️ Bloc pattern <br />

## Screenshots

<p float="left">
    <img alt="Loading Screen" src="https://raw.githubusercontent.com/sabinmhx/samachar/master/images/samachar_loading_screen.png" width="200" height="400"/>
    <img alt="Home Screen" src="https://raw.githubusercontent.com/sabinmhx/samachar/master/images/samachar_home_page1_light.png" width="200" height="400"/>
    <img alt="Home Screen" src="https://raw.githubusercontent.com/sabinmhx/samachar/master/images/samachar_home_page2_light.png" width="200" height="400"/>
    <img alt="Home Screen" src="https://raw.githubusercontent.com/sabinmhx/samachar/master/images/samachar_home_page1_dark.png" width="200" height="400"/>
    <img alt="Home Screen" src="https://raw.githubusercontent.com/sabinmhx/samachar/master/images/samachar_home_page2_dark.png" width="200" height="400"/>
    <img alt="Home Screen" src="https://raw.githubusercontent.com/sabinmhx/samachar/master/images/samachar_news_page_light.png" width="200" height="400"/>
    <img alt="Adding Screen" src="https://raw.githubusercontent.com/sabinmhx/samachar/master/images/newsapp_news_page_dark.png" width="200" height="400"/>
</p>

## Setup Instructions

To set up the News App on your local machine, follow these steps:
1. Clone the repository to your local machine.

    ```
    git clone https://github.com/sabinmhx/samachar.git
    ```

2. Open the project in Android Studio.
3. Build the project to resolve dependencies.
4. Obtain an API key from a news API provider. You can use popular news APIs like NewsAPI, New York Times API, or any other of your choice.
5. Open the `lib/cubits/both-folders/data_provider.dart` file and replace `YOUR_API_KEY` with your actual API key in.

    ```
    static final apiKey = dotenv.env['apiKey'];
    ```

6. Build and run the app on your emulator or physical device.

## Build Tools


## Credits 📖
[News API](https://newsapi.org/) is used to get all the news.This News App is inspired and built upon the foundation of various open-source projects and APIs, which we acknowledge and thank for their valuable contributions.

## License
The News App is open-source software licensed under the MIT License. Feel free to use, modify, and distribute the app according to the terms of the license.