# Pixabay Image Search

![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=flat-square&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-Build%20Tool-purple?style=flat-square&logo=vite&logoColor=white)
![Pixabay](https://img.shields.io/badge/API-Pixabay-green?style=flat-square)
![SimpleLightbox](https://img.shields.io/badge/SimpleLightbox-Gallery-lightgrey?style=flat-square)

## Overview

A browser-based image search application that retrieves photos from the Pixabay API and renders the results as an interactive gallery.

The project separates API communication from rendering logic and provides user feedback for loading, empty results, and request errors.

## Tech Stack

- JavaScript
- HTML
- CSS
- Vite
- Fetch API
- Pixabay API
- SimpleLightbox
- iziToast
- Git & GitHub

## Functionality

- accepts an image search query from the user;
- sends an HTTP request to the Pixabay API;
- renders returned images dynamically;
- displays likes, views, comments, and download statistics;
- opens large images through SimpleLightbox;
- shows a loader while data is being fetched;
- validates empty search input;
- handles no-result and network-error states with iziToast;
- keeps API and rendering logic in separate modules.

## Project Structure

```text
src/
├── js/
│   ├── pixabay-api.js
│   └── render-functions.js
├── css/
├── index.html
└── main.js
```

## Running Locally

```bash
npm install
npm run dev
```


## Learning Outcomes

- working with REST APIs;
- asynchronous HTTP requests with Fetch;
- modular JavaScript;
- dynamic rendering from API data;
- loading and error states;
- integration of UI libraries.
