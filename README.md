# Recipe Application (Minumum Viable Product)

The goal of this project was to create a MVP(minumum viable product) within 24 hours with end product being ready to demo.  I created a recipe application that displays ten random recipes, along with their image.

![Alt text](/images/screenShots/mainScreenShot.png?raw=true)

With the time constrant in mind I had to limit my expectations for the projects functionality and create something with enough CSS to be pleasing to the eye and presentable.

## Getting Started

Prerequisites: NodeJS and Xcode

First, in order to use this application you must have access to the Spoonacular API.  You can sign up for a free account [here](https://spoonacular.com/food-api/pricing) in order to get a key, and replace this piece of code in client/src/components/random.jsx line 22:

```
`https://api.spoonacular.com/recipes/random?number=10&apiKey= Your Key`
```

Second, navigate to preferred local directory.

Next, clone the repository from GitHub:

```
$ git clone https://github.com/Nkcrothers/mvp_recipes.git
```

Replace the API address with your personal key.

Navigate to the './mvp_recipes' directory and run the following commands:

```
$ npm install
$ npm run react-dev
```

After, navigate to the './mvp_recipes/server' directory and run:

```
$ node app.js
```
Command + click the 'http://localhost:3000' link, or click this link.
This will open the website in a new tab.
