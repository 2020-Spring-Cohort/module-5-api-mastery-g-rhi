# Make an API of your choosing

## Objective

You and your partner will be building an API using ASP.NET Core Web API to catalog some collection of data. It is up to the two of you exactly what it is you want your API to contain. This could be a collection of movies and their individual details, astronauts and their mission details, or a list of histories most significant programmers and their contributions. You can also catalog fictional data (so long as it's appropriate!).

You will also build a corresponding Single Page App (SPA) that will use your API to present this data. You are, however, required to build a modular JavaScript application. You will need to setup a bundler of your own. We suggest [WebPack](https://webpack.js.org/) for this as it doesn't require any configuration. You should follow the same component and utility based structure that we did for Module 5 with a single `index.js` access point at the root of your application.

<!--React instruction has not been added to Module 5 yet-->
<!-- You are free to use React if you feel like you have a good enough handle on it, but it is not required. You are, however, required to build a modular JavaScript application. So, if you use [Create React App](https://facebook.github.io/create-react-app/), this functionality is natively built in. If you are not, you will have to setup a bundler of your own. -->

Your front and back end should be totally decoupled for this project. This means you should have two project directories. You should house them in the same root project directory. It should look like this:

```shell
my-project (This is where your Git repo will be)
|- my-project-api (All .NET Core Web API material)
|- my-project-front-end (All front end material)
```

## Tasks

### Back-end/API

Your back end should be responsible ONLY for creating, reading, updating, and deleting data. Your database will be connected here as well so that your data can be persisted. Your `Controllers` should send/receive JSON data.

You must have multiple entities (at least 2) that interact with each other in some way.

#### API Interactions:

- All `CRUD` operations for all entities
- A root endpoint for all entities
- Endpoints for individual instances of all entities

#### Relationships

Make appropriate relationships between entities and map them such that you can access lower level entities from parent entities.

### Front-end

Our front-end should be an SPA that uses JS to build out components that our users can interact with. Use modular JS along with Webpack to create reusable components.

Users should be able to add new entities, remove existing entities, and update existing entities.

### Don't Forget...

- #### TDD

- #### Clean Code

- #### Source Control

- #### Basic styling that makes it look presentable/user friendly

