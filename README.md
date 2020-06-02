NewsApp is simple App which uses [NewsAPI](https://newsapi.org/) to get top headlines for country you live in or you can search for a specific news.
Focus of this app is to demonstrate (Not necessarily the best practices)

- MVVM Architecture with Kotlin Flow and LiveData

# Screenshots

<img alt="NewsApp Home" height="450px" src="https://raw.githubusercontent.com/nishantpardamwar/NewsApp/master/screenshot/screen1.png" /> <img alt="NewsApp Search" height="450px" src="https://raw.githubusercontent.com/nishantpardamwar/NewsApp/master/screenshot/screen2.png" />


# Setup
You will require Android Studio 3.0 (or newer).

- Git Clone the repo
- ### Get the API Key from [NewsAPI](https://newsapi.org/)
- Find the file named `HomeDataSource` and replace `YOUR_API_KEY` with your api key
- Build app and enjoy :)

# Architecture

<img alt="NewsApp Home" height="450px" src="https://raw.githubusercontent.com/nishantpardamwar/NewsApp/master/screenshot/architecture.png" />

# Libraries and Services Used

### Libraries
- Retrofit
- Glide
- Kotlin Coroutines/Flow
- ViewModel and LiveData

### Services
- [NewsAPI](https://newsapi.org/)
- [IP Geolocation API](https://ip-api.com/)
