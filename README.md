# Project Title

## Description
This is a React application built with TypeScript. The application provides a movie listing feature. This project consumes the [omdb api](https://www.omdbapi.com/)

## Pages
- **Home**: This is the main page of the application. It uses the `Movies` component from [src/components/Movies.tsx](src/components/Movies.tsx) to display a list of movies.

![](/readmeSources/moviesSearcher.gif)

## Hooks
- **useMovies**: This is a custom React hook located in [src/hooks/useMovies.tsx](src/hooks/useMovies.tsx). It is responsible for fetching and managing the state of the movies data.

## Technologies Used
- **React**: A JavaScript library for building user interfaces.
- **TypeScript**: A typed superset of JavaScript that compiles to plain JavaScript.
- **Vite**: A build tool that aims to provide a faster and leaner development experience for modern web projects.

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)

![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)

## Setup
To run this project, install it locally using npm:

```sh
npm install
npm run start