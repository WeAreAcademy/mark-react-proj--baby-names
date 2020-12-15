---
module: React

level: 1

methods:
  - team
  - pair
  - solo

tags:
  - wip
---

# Academy Project: Favourite Places

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.

## Overview

You will make and deploy a single-page React app which will list a few of your favourite places.

Here's an example screenshot to give you a rough idea, but note that the project text below takes precedence over any details from the image. Also, you are free to lay out and style your project as you see fit.

![example screenshot of simple implementation of the 'favourite places' project](example-screenshots/screenshot.png)

## Setup

- Create a new React app on your machine called `favourite-places-react`. See instructions on React project setup. Make sure you set up with TypeScript not the JavaScript default. TODO: add link to instructions: "React project creation setup (w typescript)".

- Publish the project repo to github. Call it `favourite-places-react`. TODO: add link to instructions: "publishing new project repo to github".

## Exercises:

### Exercise: Create the app!

The app's single page should have:

- a page header showing a suitable title.
- at least four "place" entries (see details below)
- a page footer including - at least - attribution for any images used.

Each "place" entry should have:

- a title (text)
- a place name (text)
- a country name (text)
- a main image (URL)
- a link to the rough location on google maps (or alternative) (URL)
- some text explaining why you like the place

**Regarding components**

Create a React component to represent a `Place`.
Parameterise it with props so that you can reuse the component for each of your favourite places.

You are free to make other components (either for subcomponents of a Place, or for other elements of the page).

**Regarding layout and styling**

You can lay the page out and style it as you like.

### Exercise: Deploy to netlify

Set up continuous deployment of your site to [netlify](https://netlify.app/) and make sure it has deployed.

Ensure your site is called `academy-yourgithubusername-places`.netlify.app where `yourgithubusername` is your github username. TODO: add link to netlify deploy instructions.

## Ideas for more work

- HTML: Link to another classmate's site in your footer to make a ring of "favourite places" sites.
- HTML: Make a table of contents or other navigation to take you directly to a chosen Place section.
- TypeScript & React: Make it data-driven. Store your places in an array of objects, and loop over them to create your list of places.
- CSS: Learn to use css grid or flexbox to lay out your places in a grid.
- CSS: Make it look good on mobile devices, too.
- Advanced: Embed a google map for each place
- Advanced: Embed a google map showing markers for each place.

## Further resources

- Free stock photos at unsplash: https://unsplash.com/ and pexels: https://www.pexels.com/ though you are encouraged to use your own images if you like.

## Credits
