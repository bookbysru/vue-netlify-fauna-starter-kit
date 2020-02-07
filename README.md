 # Vue - Netlify - Fauna
 ## A [JAM stack](https://jamstack.org/) template for building CRUD applications with authentication baked in. 

This template uses [Vue](https://vuejs.org/) for the front-end, [Netlify](https://www.netlify.com/) for APIs (via Netlify Functions) and [Fauna](https://www.netlify.com/) for persistent data storage. 

This is a serverless stack which leans heavily on Netlify and Fauna for the backend. These services offer generous free tiers which means anyone can get started, deploy and host this completely free.

## Initial Project setup

Don't skip these steps ❗❗

1. If you don't have a Fauna account yet, sign up [here](https://dashboard.fauna.com/accounts/login). Create your first db and generate a server key in just few clicks.

![](https://user-images.githubusercontent.com/18376481/74045740-35e7f380-49c5-11ea-938f-48470242c1b3.gif)

2. With your server key ready, you can easily clone this repo and deploy this app in a few seconds by clicking this button:
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/chiubaca/vue-netlify-fauna-starter-kit)


3. Remember to enable Identity on your newly deployed Netlify site otherwise signups and logins wont work.

![Enable Netlify Identity](https://user-images.githubusercontent.com/18376481/74047309-07b7e300-49c8-11ea-90c9-688bf226d0d5.gif)

It will only take a few moments for Netlify to deploy the site, once ready, click on your assigned URL and you have an fully functioning CRUD application with persistent storage and a login system all ready to go! 

[Demo site](https://vue-netlify-fauna.netlify.com/)

## Further development setup
```
npm install
```

### Compiles and hot-reloads for development via [Netlify Dev](https://www.netlify.com/products/dev/). (Make sure you have Netlify Dev installed with `npm install netlify-cli -g`)

```
npm start
```

### Builds the app and deploys to Netlify on a preview URL
```
npm run deploy
```

### Builds the app and deploys to Netlify on your master URL
```
npm run deploy:prod
```

### Runs unit tests with Jest
```
npm run test:unit
```

## Dymystifying the magic
So how does this all work and does one extend upon this?

TODO...
I plan on writing a blog series on this soon.

## Why This Exists

I built this template because pretty much all my side projects need persistent data storage and a login system. It was also a great opportunity to learn more about the Netlify eco system including Netlify Functions, Identity and Netlify Dev. Full credits need to go to the following repos which I have effectively mashed together.

- https://github.com/shortdiv/gotruejs-in-vue
- https://github.com/fauna/netlify-faunadb-todomvc
- https://github.com/netlify/netlify-faunadb-example
