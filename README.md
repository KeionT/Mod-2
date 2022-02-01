
This application looks pretty much the same like the original [Yelp](https://www.yelp.com) website.

It leverages the free [Yelp Fusion REST API](https://www.yelp.com/developers/documentation/v3) for which you need an API key.

1. Head over to the [Yelp Fusion API documentation](https://www.yelp.com/developers/documentation/v3)

6. Navigate to the `src/hooks/yelp-api/config.js` file and assign the `BEARER_TOKEN` variable the following content
   ```
   const BEARER_TOKEN = '<your-token-here>'
   ```
7. Install the dependencies by running `npm install` or `yarn install`
8. Run the app with `npm start` or `yarn start`


# 6. Used Technologies
* [React / create-react-app](https://github.com/facebook/create-react-app)
    * **only functional components**
    * communication with web servers with [React Hooks](https://reactjs.org/docs/hooks-intro.html) only
    * no higher order or class-based components
* [React router](https://github.com/ReactTraining/react-router) with [useReactRouter](https://github.com/CharlesStover/use-react-router)
* [Bulma](https://bulma.io)
* Flexbox

# 7. Disclaimer
This project is **solely intended for educational purposes** and is created under **fair use**.

It is **not intended to create any kind of Yelp competitor**, but to teach advanced concepts in frontend development.

Just see it a nice educational project that will help you to improve your coding skills.# Mod-2
