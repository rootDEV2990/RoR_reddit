# Rails Reddit mini clone

![screenshot](./img/app_screenshot_scraper.png)

## Objectives

1. Practice Active Record creation, update and deletion.
2. Pactice relations between tables with rails. 
3. Focus on up and down inplementation for each model.

## Overview

Have you ever wanted to design your own database structure? With ruby you can! Check out how i have used rails to create tables and add, edit, delete into them. You can find assosiations too in the models to show how the diffrent relations are made bettwen tables. 

### Databases and queries simplified!

Rails will give you the freedom and flexiblity to create or edit the colums in your tables with ease. The power of Ruby the potential of Rails ;).

### Project Structure

```bash
app
├── controllers
│   └── Authors
│   └── Posts
│   └── Comments
├── models
│   └── author.rb
│   └── post.rb
│   └── comment.rb
├── views
│   └── articles
│       └── index.html.erb
│
config
│   └── routes.rb
│   └── database.yml
db  
├── migrate
│   └── xxxxxxxxx_create_articles.rb
│   └── xxxxxxxxx_create_posts.rb
│   └── xxxxxxxxx_create_comments.rb
├── shema.rb

README.md

```

## Built With

- Ruby, Ruby Gems, Rubocop, and target URL.

## Getting Started

1. Clone directory $ git clone https://github.com/rootDEV2990/ruby_scraper
2. Open terminal type cd /path/to/folder and hit enter.
3. Install Ruby gems, type in terminal "bundle install".
4. Run "ruby ./bin/main.rb" inside your terminal.
5. Script will promp you to input your search query..input query and hit enter.
6. Script will scrape and rescrape as user provides new inputs returning results. 
7. Bottom table will display page available with results number inputs will be auto detected to pan pages. 
8. You can click cmd+click on link to open in browser. 
9. Press Ctrl+C to stop ruby script. 

### Prerequisites

Ruby installed on your computer to be able to run the script.

## What it does:

1. Targets a URL.
2. Gets RAW HTML.
3. Extracts targeted DATA.
4. Displays values in terminal.
5. Allows you to directly navicate to download page 
(*Site requires you to be a member to downlaod, registration is free*)

## Authors

👤 **Miguel Angel Enciso Sanchez**

- Github: [@rootDEV2990](https://github.com/rootDEV2990)
- Twitter: [@m29902](https://twitter.com/m29902)
- Linkedin: [linkedin](https://www.linkedin.com/in/miguel-enciso-6474741a1/)
- Medium: [medium](https://medium.com/@website.dev)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](issues/).

## Show your support

Give a ⭐️ if you like this project!

Bitcoin donations accepted ;)

1AD5ANtHmqemTZ2Qmv5UqJAMijTNyCAH8D 🚀
