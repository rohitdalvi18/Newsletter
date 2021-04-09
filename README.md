# Newsletter

This is a Newsletter application built using the [Mailchimp API](https://mailchimp.com/developer/marketing/api/) and Express.js

## Getting Started

- Create a *free* Mailchimp Account. Find more information here: [Get Started with the Mailchimp API](https://mailchimp.com/developer/)  
- Once created, note all of your Mailchimp authorisation credentials. 

## Usage

- Download or Clone the repo and then move into the `Newsletter` directory.
- Install all dependencies:
  ```shell
  $ npm i
  ```

- Create a file `.env` for environment variables and put the following into it:

  ```text
  API_KEY=13ugt3i813ee6429geacc73748aae5a-us9
  LIST_ID=aer024f6ee
  USER=yourUsername
  US_SERVER=US9
  ```

  _Make sure to put real values, the above values are just an example_

- To run the app in the development mode:
  ```
  $ nodemon app.js
  ```

  Open [localhost:3000](http://localhost:3000) to view it in the browser.
