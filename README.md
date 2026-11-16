# Movie App

A movie app build using ReactJs and Appwrite.

## Overview

This movie app is a single page application where you can view movies from external API called The Movie Database. I built this to study about ReactJS and how to show data from API.

## Tech Used

- Language: ReactJS
- Libraries: Tailwind CSS, PostgreSQL
- Tools: Git, VS Code, Appwrite, Github Pages, TMBD

## What I Learned

- How importance to separate components.
- How to pass data one component to another using props.
- How useState hook works for example giving the errorMessage a default value of empty string then setting it to "Failed to fetch movies" if there is no available movie.
- How useEffect hook like fetching data from the server for example fetching movies from the API. Another simple example is you want to display the value of how many you clicked the like button with dependency array.
- How to implement optimize search funtion

## Challenges and Solutions

| Challenge | How I Solved It |
|-----------|-----------------|
| Search function send too many request | Optimize the performance by debouncing the input field |
| Need to show the trending movies | Implmenent database and monitor the times movie has been search |

## What I'd Improve

- Reusable components
- Display data from API
- Deploy a project using Github Pages with Appwrite

## Check the final project
- https://iamjamescee.github.io/movie-app/

## Resources

- [Official documentation](https://react.dev/)
- [The Movie Database](https://www.themoviedb.org/)
- [Tutorial I followed](https://www.youtube.com/watch?v=dCLhUialKPQ)
