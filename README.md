# Cocktails-Search-React 🍸
> PROD [Live] : https://cocktailsfinder.netlify.app/

#### Cocktails consists of a straight forward user interface where there is a 
- List of cocktails by default, a search form to search for specific cocktails as we are typing, and along with the routes to the **Home** and **About** in the navigation bar.
- To get more details of a specific cocktail in the list, click on the **Details**. 
- For each page render the **Loading** component has been implemented and unknown route URLs are handled by the **Error** component.
- To run the project locally, clone the repo, `npm install` to install the dependencies and `npm start` to start up the development server on default port 3000.

#### Languages / Technologies 
HTML, CSS, JavaScript, React ~ Context API - Hooks, React Router 6, React Axios

#### API
https://www.thecocktaildb.com/api.php

#### Deployment / Hosting
Netlify

---

#### React Router Fix

The routing implemented using react-router-dom to work properly on the server side after it has been continuous deployed on Netlify, [_redirects] is added. For more info -  [Fix](https://dev.to/dance2die/page-not-found-on-netlify-with-react-router-58mc)

```

"build": "react-scripts build"

```

But make sure to add `CI=` again when using continuous deployment setup on Netlify otherwise errors will occur
```

"build": "CI= react-scripts build",

```
---

**To install React router 6**

```sh
npm install react-router-dom@6
```

**To install React Axios**

```sh
npm install axios
```
