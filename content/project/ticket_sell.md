+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Ticket Trading"

# Project summary to display on homepage.
summary = "Ticket trading platform."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "ticket_sell/home_view.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["android", "business", "server_integration"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++

Ticket Trading utilizes android and its features to provide, easy-to-use and convenient, ticket trading platform for its users. Core features include, list one or multiple tickets for sale, browse through available tickets in a list mode or see a detailed view of a specific listing, search for specific tickets with dedicated controls, and option to sort by price, date, and type. Additional features include facebook login, history of tickets listed, and integrated messaging to negotiate deals.

### Goal
Our team's primary goal was to deliver polished applications that includes features in out proposal. Considering team's background in regards to the tools used in this project, I would say we accomplished our goal.

### Responsibility
With no prior android or web development experience, I took the responsibility of back-end portion. I utilized Volley for transmission of data between client and server. PHP was used for data manipulation on server-side with MySQL database for storage. My contribution included following things:

* Utilized Volley library to allow client-server communications.
* Implemented PHP scripts to handle client requests, access MySQL database to insert, update or query data, and send results back to client.
* Design database schema for users and tickets.
* Debug and solve conflicts that arise while merging code, using Git.

<div id="carousel-ticket_sell" class="carousel slide" data-ride="carousel">
  <ol style="background-color:darkgrey" class="carousel-indicators">
    <li data-target="#carousel-ticket_sell" data-slide-to="0" class="active"></li>
    <li data-target="#carousel-ticket_sell" data-slide-to="1"></li>
    <li data-target="#carousel-ticket_sell" data-slide-to="2"></li>
    <li data-target="#carousel-ticket_sell" data-slide-to="3"></li>
  </ol>

  <div class="carousel-inner" role="listbox">
    <div class="item active">
      <img src="/img/ticket_sell/gesture.png" class="img-responsive" alt="Responsive image">
      <div class="carousel-caption">
      </div>
    </div>
    <div class="item">
      <img src="/img/ticket_sell/message.png" class="img-responsive" alt="Responsive image">
      <div class="carousel-caption">
      </div>
    </div>
    <div class="item">
      <img src="/img/ticket_sell/home_view.png" class="img-responsive" alt="Responsive image">
      <div class="carousel-caption">
      </div>
    </div>
    <div class="item">
      <img src="/img/ticket_sell/detail_view.png" class="img-responsive" alt="Responsive image">
      <div class="carousel-caption">
      </div>
    </div>
  </div>
</div>
