<!--### Hello everyone 👋-->
```markdown
# Movie App

This repository contains an Android Movie App built using Java, following the MVVM (Model-View-ViewModel) architecture. The app uses Retrofit to make network requests to The Movie Database (TMDB) REST API to fetch popular movies and display them in a RecyclerView.

## Features

- Fetches and displays popular movies from TMDB API.
- MVVM architecture for a clean separation of concerns.
- Retrofit for network requests.
- LiveData for observable data.
- RecyclerView for displaying movie list.

## Project Structure

The project is organized into the following folders:

- **model**
  - `Movie.java`: Defines the schema of the movie data, extends `BaseObservable` for data binding, and includes methods for loading movie poster images.
  - `MovieRepository.java`: Abstracts data source details and provides a central source of movie data using Retrofit.
  - `Results.java`: Defines the schema for API results, similar to the movie schema.
- serviceapi
  - `MovieApiService.java`: Defines the API endpoints using Retrofit annotations.
  - `RetrofitInstance.java`: Sets up Retrofit and provides an instance for accessing the API.
- **view**
  - `MovieAdapter.java`: Manages the RecyclerView, binds data to views, and defines the ViewHolder.
- **viewmodel**
  - `MainActivityViewModel.java`: Extends `AndroidViewModel`, uses `MovieRepository` to fetch movie data, and provides LiveData for the view.
- **MainActivity.java**: The main activity that sets up the ViewModel, RecyclerView, and handles UI interactions.

## Setup and Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/skwasimrazzak/movie-app.git
   cd movie-app
   ```
<h1>
  Hello everyone
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
</h1>
<div id="header" align="center">
  <img src="https://media.giphy.com/media/ryRe2vuYIQ3RQ5eMtY/giphy.gif" width="150"/>
</div>
<div id="badges"  align="center">
  <a href="https://www.linkedin.com/in/skwasimrazzak/">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://twitter.com/skwasimrazzak">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
  <a href="https://www.instagram.com/skwasimrazzak/">
    <img src="https://img.shields.io/badge/Instagram-purple?logo=instagram&logoColor=white&style=for-the-badge" alt="Instagram Badge"/>
  </a>
</div>
Currently, I am a front-end developer. Soon to be a full-stack developer as I learn something new every day. Love coding and uploaded some basic websites (initially created by me) to track my improvement through out the process of learning. I have a rudimentary understanding of C and Python programming.Very enthusiastic about collaboration. Creating a team of like-minded people and working with them to build a project is something I often do and like to do so. Having a constant urge to learn made me do whatever I did to date.

