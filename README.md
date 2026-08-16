# Github Dashboard

## TL;DR

A tool that fetches your Github data using the Github API. It takes in your username and saves it into localStorage (you can change it whenever you like).

## How-To-Use

The first time you open your Github Dashboard, you have to enter your username and submit it. This saves your username in localstorage, so next time you open the website it loads your username. To reset your username at any time scroll to the bottom of the main page and click *reset your username*. The landing page contains an info card about your stats and the repositories page contains all your repositories. You can click on any repository to view more about it.

## How it Works

The Github Dashboard takes your username and requests information about your profile and your repositories to the Github API. The dashboard uses this to load information about you. The landing page contains an info card about you, while the repositories page contains all your repositories. When a repository is clicked, Javascript identifies which one you clicked and then uses the API endpoints for you repository and its commits, activity and coding languages. It then loads this to your page.

## How I made it

I used HTML and CSS for the structure and styling of the page, including adding the opening/loading animation and the squircle corners. Javascript did the heavy lifting, communicating with the Github API and dynamically updating the HTML using DOM and IDs.
