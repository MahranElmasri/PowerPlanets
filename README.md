# Front-End Task

Front-End Task
![here](http://g.recordit.co/2A8FMvQO4l.gif)

## dependancies

- Node

- npm

## Installation

1. Clone the project.

2. cd dev and run `npm install`.

3. cd client and run `npm install`.

4. Get the API key

- You must have at least one API key associated with your project.

### To get an API key:

Go to the Google Cloud Platform Console.

Click the project drop-down and select or create the project for which you want to add an API key.

Click the menu button and select APIs & Services > Credentials.
On the Credentials page, click Create credentials > API key.
The API key created dialog displays your newly created API key.

Click **Close**.

The new API key is listed on the Credentials page under API keys.

`(Remember to restrict the API key before using it in production.)`

> Add the API key to your request
> You must include an API key with every Maps JavaScript API request. In the following example, replace YOUR_API_KEY with your API key.

Replace the **API Key** in inside `client/PowerMap` component

> googleMapURL="https://maps.googleapis.com/maps/api/js?key="YOUR_API_KEY"&v=3.exp&libraries=geometry,drawing,places"

## development

1. open first terminal and write `cd dev` && `npm run dev`.

2. open second terminal and write `cd client` && `npm start`.

## Testing

1. run `npm test`
