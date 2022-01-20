<div align="center">

<img src="app/assets/images/branding/logo.png" width="300px">

![](https://img.shields.io/github/last-commit/arthurfincham/acebook)
![](https://img.shields.io/github/languages/count/arthurfincham/acebook)
![](https://img.shields.io/github/languages/code-size/arthurfincham/acebook)

</div>

#### Table of Contents

- [Preview](#Preview)
- [Features](#Features)
- [Install](#Install)
- [Stack](#Stack)
  - [Project](#Project)
  - [Testing](#Testing)
  - [Gems](#Gems)
- [Assignment](#Assignment)
- [Team](#Team)

<div align="center" >

## Preview

<img src="app/assets/images/branding/dt_preview.gif" width="800px">

&nbsp;

</div>

## Features

- [x] User authentication (from scratch)
- [x] User can upload a profile picture
- [x] User can attach a picture to a post
- [x] User can like on a post
- [x] User can comment on a post
- [x] Likes & comments do not refresh the page
- [ ] User can make a friend request
- [ ] User can send a direct message to another user

## Install

Clone the repository

```bash
% git clone https://github.com/emanfolo/acebook-Jeamm-Team
```

Go to the project directory and install dependencies:

```bash
% cd acebook-Jeamm-Team
```

```bash
% bundle install
```

```bash
% yarn install
```

#### Set up [PostgreSQL](https://www.postgresql.org/download/) if not already installed.

Create databases

```bash
% rails db:create
```

Migrate tables

```bash
% rails db:migrate
```

Run the server

```bash
% bundle exec rails server
```

## Stack

### Project

|                                                                                                                                                                     | Tool                                      | Use?                                       | Where is it used?                                                      |
| :-----------------------------------------------------------------------------------------------------------------------------------------------------------------: | ----------------------------------------- | ------------------------------------------ | ---------------------------------------------------------------------- | --- |
|                             <img src="https://seeklogo.com/images/T/trello-logo-CE7B690E34-seeklogo.com.png" height="auto" width="60">                              | [Trello](https://trello.com/en-GB)        | Web-based, Kanban style list maker.        | To keep track of tickets and organise our team throughout the project. |
|      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/29/Postgresql_elephant.svg/1200px-Postgresql_elephant.svg.png" height="auto" width="60">      | [PostgreSQL](https://www.postgresql.org)  | Object-relation database.                  | In the databases and tables that make up the app.                      |
|           <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/Bootstrap_logo.svg/1280px-Bootstrap_logo.svg.png" height="auto" width="60">           | [Bootstrap](https://getbootstrap.com/)    | Open source tool-kit made by twitter.      | All of the design.                                                     |     |
|                                        <img src="https://image.pngaaa.com/154/4122154-middle.png" height="auto" width="60">                                         | [Ruby on Rails](https://rubyonrails.org/) | Server-side web framework written in Ruby. | Everywhere!                                                            |
|                                 <img src="https://www.drupal.org/files/issues/2019-12-27/heroku_logo.png" height="auto" width="60">                                 | [Heroku](https://www.heroku.com/)         | Cloud platform for deploying web apps.     | Behind the scenes, hosting the app.                                    |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/Amazon_Web_Services_Logo.svg/1200px-Amazon_Web_Services_Logo.svg.png" height="auto" width="60"> | [AWS S3](http://sinatrarb.com/)           | Object storage for images in AWS' S3       | Also behind the scenes, hosting images.                                |

### Testing

|                                                                                                         | Tool                                                 | Use?                                | Where can I see it?                         |
| :-----------------------------------------------------------------------------------------------------: | ---------------------------------------------------- | ----------------------------------- | :------------------------------------------ |
|               <img src="https://rspec.info/images/logo_ogp.png" height="auto" width="60">               | [RSpec](https://rspec.info/)                         | Testing tool for Ruby.              | `/spec/*` Unit tests for the app's classes. |
| <img src="https://www.braveterry.com/wp-content/uploads/2015/01/capybara.jpg" height="auto" width="60"> | [Capybara](https://github.com/teamcapybara/capybara) | Acceptance test framework for Ruby. | Feature testing for the app.                |

### Gems

|       | Gem                                                                | Use?                                                                    |
| :---: | ------------------------------------------------------------------ | ----------------------------------------------------------------------- |
| :gem: | [shoulda-matchers](https://github.com/thoughtbot/shoulda-matchers) | Extends the matchers of Rspec.                                          |
| :gem: | [awesome_print](https://github.com/awesome-print/awesome_print)    | One of our favourite gems; pretty prints output from the Rails console. |
| :gem: | [bcrypt](https://github.com/bcrypt-ruby/bcrypt-ruby)               | Ruby password hashing to secure user passwords.                         |
| :gem: | [carrierwave](https://github.com/carrierwaveuploader/carrierwave)  | File upload solution for Rails in tandem with AWS S3.                   |

## Assignment

Create a clone of Facebook with Ruby on Rails.
Users can:

- Sign Up
- Sign In
- Like and Comment on Posts
- Have new likes and comments refresh without reloading the page.

## Team

> Arthur &nbsp;&middot;&nbsp;
> GitHub [@arthurfincham](https://github.com/arthurfincham) &nbsp;&middot;&nbsp;

> Emmanuel &nbsp;&middot;&nbsp;
> GitHub [@emanfolo](https://github.com/emanfolo) &nbsp;&middot;&nbsp;

> Jacob &nbsp;&middot;&nbsp;
> GitHub [@jtc27](https://github.com/jtc27) &nbsp;&middot;&nbsp;

> Marianne &nbsp;&middot;&nbsp;
> GitHub [@marazzo](https://github.com/marazzo) &nbsp;&middot;&nbsp;

> Max &nbsp;&middot;&nbsp;
> GitHub [@maxcfry](https://github.com/maxcfry) &nbsp;&middot;&nbsp;
