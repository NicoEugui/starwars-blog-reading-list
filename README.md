# Star Wars Blog Reading List

![Star Wars](https://img.icons8.com/color/452/star-wars.png)

This project focuses on URL routing for a Star Wars-themed web application. It implements a routing system that includes essential views, such as a list of items and individual views (e.g., spaceships). The project ensures proper URL configuration in the router and fetching of information when loading the respective views. Additionally, the Context API has been utilized to follow the Model-View-Controller (MVC) design pattern, efficiently managing storage, visualization, and actions.

## Usage Instructions

### Requirements:
- Make sure you are using Node.js version 10

### Getting Started:
1. Install the dependencies:
```
$ npm install
```
2. Create a .env file:
```
$ cp .env.example .env
```
3. Start coding! and the webpack dev server with live reload, for windows, mac, linux or Gitpod:

```bash
$ npm run start
```

### Customization
You can update the `styles/index.css` or create new `.css` files inside `styles/` and import them into your current scss or js files depending on your needs.

### Components
Add more files into your `./src/js/components` or styles folder as you need them and import them into your current files as needed.

### Views (Components)
Add more files into your `./src/js/views` and import them in `./src/js/layout.jsx`.

### Context
This boilerplate comes with a centralized general Context API. The file `./src/js/store/flux.js` has a base structure for the store, we encourage you to change it and adapt it to your needs.

## Publish your website!
This project is compatible with various hosting services, including Vercel and GitHub Pages. Follow the appropriate instructions to publish your site.
