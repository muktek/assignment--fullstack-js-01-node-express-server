# Full Stack JS Project - DevJobs - 01 - Node Express Starter

**`fullstack-js-01-node-express-server`**

## Context
You are going to build a full stack web application with node.js + React. In order to become familiar with how a node project works, you will be responsible for configuring the  initial major components of the project.  

- **express server**
- application routes
- views
- api layer
  - data access
  - data models (ORM)
  - RESTful routes


## The Assignment
For this assignment, we will focus on creating the **express server**.

You will need to install the express package from NPM.

In order to satisfactorily complete this assignment, you will need to do the following in `server.js`:

- import the express application with `require()`
- initialize the express application
- create a basic route handler on the home path (`/`)
- return the contents of the `home.html` file from the `src/views/` directory by using the `fs.readFile()`
- make the app listen on port 3000

### Deliverable

You will need to push your code to github on the `part-01-app-server` git branch

```
git add .
git commit -m '«your commit msg»'
git push origin --all
```


### Setup Instructions

In Terminal:

```sh
# (1) navigate to your assignments directory
cd ~/Documents/muktek/assignments

# (2) Clone the Project and navigate into it
git clone https://github.com/muktek/build--node-project-starter.git project--devjobs

cd project--devjobs

# (3) Install project dependencies
npm install

# (4) Remove the remote origin repository
git remote remove origin

# (5) You will work on the part-01-app-server branch for this feature
get checkout -b part-01-app-server
```

### Questions to consider
- What does `app.use(...)` do?
- Why are `req`, `res` important and what do they allow us to do?
