# Friend List Project

This contact list app was created as a refresher exercise in Ruby on Rails, and to gain experience deploying to Heroku. As such, very little attention is given to stylistic details, as the primary focus here is to sharpen my understanding of Active Record and other core Rails functionality. The app contains the following features:

## Features

- User account creation and deletion
- New contact creation, edit, and deletion
- Contacts are associated with user accounts
- Contacts are hidden from anonymous users
- CRUD actions are prohibited unless the user is signed in
- Anonymous users cannot perform CRUD actions by guessing URL paths


## Final Product

!["Sign up"](https://github.com/rjlmacfarlane/friends-list/blob/master/docs/signup.png)
!["Login"](https://github.com/rjlmacfarlane/friends-list/blob/master/docs/login.png)
!["Add a Friend"](https://github.com/rjlmacfarlane/friends-list/blob/master/docs/newcontact.png)
!["Contact List"](https://github.com/rjlmacfarlane/friends-list/blob/master/docs/contacts.png)

## Getting Started

- Install all dependencies (see below) using the `npm install` command.
- Run the development web server using the `node express_server.js` command.

## How to Use

- Clone this repo
- CD into project folder
- $ rails -b 0.0.0.0
- Browse to `http://localhost:3000`

## Dependencies

- Rails 4.2.6
- PostgreSQL
- SASS-Rails ^5.0
- Uglifier ^1.3.0
- Coffee-rails 4.1.0
- Devise ^4.7.3
- JQuery-Rails
- Turbolinks

## Dev Dependencies

- ByeBug
- SQLite
- Web-console 2.0
- Spring