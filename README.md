---
module: React

level: 1

methods:
  - team
  - pair
  - solo

tags:
  - react
---

# Academy Project: Baby Names Picker

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.

## Overview

You will make and deploy a single-page React app which will show baby names and let you pick your favourites. The names data is provided for you.

Here's an example screenshot to give you a rough idea, but note that the project text below takes precedence over any details from the image. Also, you are free to lay out and style your project as you see fit.

![example screenshot of simple implementation of the 'baby names' project](./example-screenshots/finished.png)

## Setup

- Create a new React app on your machine called `baby-names-react`. Make sure you set up with TypeScript not the JavaScript default. 
[Guide to React project creation setup (with TypeScript)](https://www.notion.so/weareacademy/How-to-create-a-React-app-with-TypeScript-76643f84db564a69a04db9a0b6a2f2e7)

- Publish the project repo to github. Call it `baby-names-react`.

- Set up continuous deployment of your app to [Netlify](https://netlify.app/) as `academy-yourgithubusername-baby-names`.netlify.app where `yourgithubusername` is your github username. See [Netlify deployment guide for React apps](https://www.notion.so/weareacademy/How-to-deploy-a-React-app-to-free-Netlify-hosting-9e6ebd4dcb814cb483c34eb0f05ea96e)



### Setup - the data:

The data is available in the file [./data/babyNamesData.json](./data/babyNamesData.json).

Copy across this JSON file to your app's `src/` directory, and then import it.

## Exercise 1

- Write a React app which lists baby names from the given file.

- It should display boys' and girls' names differently - it's your choice as to how\*

- The names should be displayed in ascending alphabetical order.

- Your project should be on GitHub and Netlify with correct names.

(\*) Feel very free to break from the the "blue-for-boys/pink-for-girls" stereotyping and style it differently.

### Example Screenshot

![Level 1 Example Screenshot](./example-screenshots/level-1.png)

## Exercise 2

- Add a search bar.

- When the user types into it, your app should update the displayed list of baby names to only show matches.

- Matches should be case-insensitive.

- When the search bar is clear, all names should be shown.

### Example Screenshot

![Level 2 Example Screenshot](./example-screenshots/level-2.png)

## Exercise 3

- Check in with faculty before continuing to this level.

- Add a "favourites" list, displayed separately.

- When the user clicks a name from the main list, it should be moved to a "favourites" list. It should disappear from the main list!

- When the user clicks a name from the _favourites_ list, it should be moved back to the main list. It should disappear from the favourites list!

### Example Screenshot

![Level 3 Example Screenshot](./example-screenshots/level-3.png)

## Exercise 4

Add "name gender" filter buttons.

These buttons should allow the user to see only boy names, girl names, or all names.

The buttons should operate as "radio" buttons - exactly one should be active at any time.

The app should start by showing all names.

It should be clear which filter (if any) is in effect at any time.

_How it works with search:_

If there is also a search term in effect, your app should apply the gender filter to those search results.

### Example Screenshot

![Level 4 Example Screenshot](./example-screenshots/level-4.png)

# Ideas for more work

- Find a way to persist the user's favourites even after the browser tab is closed
- Add the ability for the user to shuffle the list of names
- Find an attractive way to differentiate names by gender that doesn't use blue/pink stereotypes.
- Add some suitably-themed sound effects for the UI.
  - Josh W Comeau's [useSound hook](https://www.joshwcomeau.com/react/announcing-use-sound-react-hook/) can help here,
  - as can [freesound.org](https://freesound.org/)

## Credits

The core app idea for this challenge, and its default look, were taken from [Simon Vrachliotis'](https://simonswiss.com/) app, found via [react.rocks](https://react.rocks/example/Baby_name_inspiration).
