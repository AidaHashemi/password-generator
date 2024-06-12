# JSON Server

This project is a very simple JSON server that is mostly used for testing and development. You can create a local server on your computer using JSON Server, which uses a JSON file as its database.

## Installation

To install JSON Server, first install Node.js. Then, install JSON Server globally using npm:

```bash
npm install \-g json\-server
```

## Usage

To run JSON Server, prepare your JSON file and then enter the following command in the terminal:

```bash
json\-server \-\-watch db\.json
```

Here, `db.json` is the name of your JSON file. You can change the file name as you like.

Now your JSON Server is ready to use. You can visit `http://localhost:3000` to view and use your data.

##Running
you should run this server with `npm start`
