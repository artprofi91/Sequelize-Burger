# Sequelize-Burger

# MySQL-Burger

I created a burger logger app with Sequelize, Node, Express, Handlebars and a Sequelize's ORM methods. I followed the MVC design pattern; used Node and Sequelize to query and route data in my app, and Handlebars to generated my HTML.

## How it works

Devour Burger is a restaurant app that lets users input the names of burgers they'd like to eat.

Whenever a user submits a burger's name, my app will display the burger on the left side of the page -- waiting to be devoured.

![1](https://user-images.githubusercontent.com/28790452/31296915-b3742fca-aaa9-11e7-9c1f-9bc0692887f6.gif)

Each burger in the waiting area also has a Devour it! button. When the user clicks it, the burger will move to the right side of the page.

![2](https://user-images.githubusercontent.com/28790452/31296984-ef47d7a4-aaa9-11e7-9b17-1abbde5bee5a.gif)

I added a Customer association to the project. This involves creating at least one new Customer model and connecting it with my Burger model.

![1](https://user-images.githubusercontent.com/28790452/31297658-83c659e4-aaac-11e7-9641-aac8acc33ab6.gif)

Click [here](https://art-sequelize-burger.herokuapp.com/) to see the app live.

## Project Installation

There are two methods to download the repository.

#### Method I: Familiar with Git?

Clone this repository, install dependencies, then run the project with the following:

```
> git clone git@github.com:artprofi91/Sequelize-Burger.git
> cd Sequelize-Burger
> npm install
> node server.js
> go to localhost:8080
```

#### Not Familiar with Git?

Click [here](https://github.com/artprofi91/Sequelize-Burger) then download the .zip file. Extract the contents of the zip file, then open your terminal, change to the project directory and:

```
> npm install
> node server.js
> go to localhost:8080
```

#### Hint

Don't forget to change password in `config.json`