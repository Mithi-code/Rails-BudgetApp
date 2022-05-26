# Budge App
>  This is a mobile-web app that keeps record of user transactions made on a category. Users can create new categories and add several transactions under them. It is built with ruby on rails 

## Technologies Used
* Languages (Ruby, HTML, JS, CSS)
* Library (Ruby on Rails)
* Git
* Gitflow

## Presentation
[Presentation Video](https://www.loom.com/share/100924456f014224b120afb0630cca48)

## Live Demo
[Live Demo]([https://budget-appl.herokuapp.com/](https://rails-budget-application.herokuapp.com/))

## Software Requirements
* Node.JS
* Ruby
* npm
* Code Editor
* Git

## Local Installation
* Clone the repo using the command below

```
git clone git@github.com:Mithi-code/Rails-BudgetApp.git
```

* Navigate to the directory in which you cloned the project and use the command below

```
cd Rails-BudgetApp
```

* Install all project dependencies and packages using the command below

```
bundle install
```
> then initialize the database

```cmd
rails db:reset
```
Incase its the first time:

```cmd
rails db:create
```
then

```cmd
rails db:migrate

* Start the server to run the application locally using the command below

```
rails s
```

## Run Tests
* To run the test, replace `ENV.fetch('RAILS_ENV', nil) ||= 'test'` in `spec/rails_helper` with `ENV['RAILS_ENV'] ||= 'test'`
* Next, go to the terminal and type the command `rspec spec`

## Authors
👤 **Mithi**

[@githubhandle](https://github.com/Mithi-code/)
[@twitterhandle](https://twitter.com/sam_mongare)
[LinkedIn](https://www.linkedin.com/in/mithicode/)

## Contributing :handshake:
Contributions, issues, and feature requests are welcome!
* Fork this repo using the command below

```
gh repo fork (https://github.com/Mithi-code/Rails-BudgetApp)
```
* Clone the forked repo using the command below

```
git clone (https://github.com/Mithi-code/Rails-BudgetApp)
```

* Navigate to the directory in which you cloned the project and use the command below

```
cd Rails-BudgetApp
```

* Switch to dev branch using the command below

```
git checkout dev
```

* Create a new feature branch using the command below

```
git checkout -b [name_of_feature_branch]
```

* Commit your changes using git commit as shown below

```
git commit -m ["enter a commit message"]
```

* Push your changes using

```
git push -u origin [name_of_feature_branch]
```
* Open pull request to the dev branch


## Show your support
Give a 	:star: if you like this project.

## Acknowledgments
* Credit to- Gregoire Vella on Behance the author of the original design
* Design by -The Creative Commons license of the design.

## License :memo:
This project is [MIT](https://github.com/microverseinc/readme-template/blob/master/MIT.md) licensed
