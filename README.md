# Learning Objectives

- Implement an authentication flow that encrypts sensitive data and authorizes access to secure data
- Explain how business requirements get translated into user stories
- Design and build an architecture that has a front-end application consuming data from a database-backed API
- Explain how Continuous Delivery / Integration fits in to the software development lifecycle

# Project Requirements

## Planning Stage

- Must have a Star Feature broken down into User Stories *(see the below section on star features)*
- Must have User Stories for core application features
- Must have Entity Relationship Diagrams which are kept up to date
- Must have Wireframes for the frontend application
- Must have a GitHub project board, kept up to date, with the following columns:
    - `Backlog` containing all tasks (user stories)
    - `To Do` containing only the tasks chosen for the current sprint
    - `In Progress` containing tasks in progress
    - `Done` containing completed tasks

## Build Stage

- **Fork** this repo for your backend: [https://github.com/boolean-uk/boolean-uk-final-solo-project-server](https://github.com/boolean-uk/boolean-uk-final-solo-project-server)
- **Fork** this repo for your client: [https://github.com/boolean-uk/boolean-uk-final-solo-project-client](https://github.com/boolean-uk/boolean-uk-final-solo-project-client)
- Must not expose sensitive information
- Must have authentication (sign up, log in, log out)
- Must use authorization to limit user actions based on role


# Star Feature

By default, this should be a section of the app that only admin style users can access where they can perform actions that a standard user cannot.

If you think you have a sufficient understanding of the topics we have been learning, we are open to discussing a different star feature that still satisfies the project requirements. This could be one of the following examples, or an idea of your own:

- A game that users have to log in to play, with a Game Master role who can define the rules for the game
- Publish your own npm package with unit tests that you can install and use in the project
- A Chrome / Firefox extension that interacts with your application in some way
- An interactive map where users can plan road trips, save their map and share it with others
- Movie / TV show / game suggestions using a third-party API such as TheMovieDB
- Build your app in TypeScript
- A *complete* suite of automated tests using a library such as `jasmine` or `jest`


# Friday
- Homework:
    - Consider your own abilities and decide whether you should move forward with the default star feature or a custom idea
    - Come up with a few ideas of what you'd like to build; it's best to bring at least 3 potential projects to the table

# Monday

- User Stories
- Entity Relationship Diagrams
- Wireframes
- Project Boards - *Backlog, To Do, In Progress, Done*
- Research potential packages & services to use

# Workflow

1. `git pull origin main` to make sure you have the latest code
2. `git checkout -b my-feature` to create a new branch to work on
3. Add and commit your changes
4. `git push -u origin my-feature` to push your branch to GitHub
5. Open a new pull request and change the "base repository" to your forked version (it will default to the boolean-uk one - see the image below for guidance)
6. Once PR has been approved and merged, `git checkout main`
7. Go back to step 1

![](https://i.imgur.com/9cpJjbY.png)