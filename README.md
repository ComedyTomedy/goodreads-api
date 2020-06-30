# Goodreads Fetch Shelf

Example app to download data from your personal shelves from the Goodreads API. Requires a Goodreads account, and developer access.

It's not possible to access generic "genre" type shelves, only your own personal shelves.

## Installation & Usage

Clone this repo and install dependencies:

`$ git clone https://github.com/prahaladbelavadi/goodreads-api`

`$ cd goodreads-api`

`$ npm install`

`$ cp ".env copy" .env`

Edit the file `.env`, and replace the dummy data. You can get your API key & secret pair from https://www.goodreads.com/api/keys . To find your User ID, go to "My Books" in Goodreads and copy the number in the URL.

Now you can run it :) 

`$ nodejs ./app.js`
