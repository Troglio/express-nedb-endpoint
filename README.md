A lightweight express server that accepts Troglio's data (`POST /newdata`) and stores them in a Nedb instance, then serves them through `GET /`.


# Demo

Better than words, here is the project live: [Glitch project with Troglio + Express + Nedb](https://glitch.com/edit/#!/troglio-nedb)

# Getting started

The easiest way to get started is to remix the Glitch project [here](https://glitch.com/edit/#!/troglio-nedb).
Once remixed you will get an URL like `https://my-project.glitch.me`: this is your endpoint.
From here, in Trello, you should tell Troglio to send pages data to `https://my-project.glitch.me/newdata`.

That's it. After setting up your custom endpoint in Troglio, anything you write into Trello cards will be available in `https://my-project.glitch.me`.

[See how to organize your API with Troglio]()
