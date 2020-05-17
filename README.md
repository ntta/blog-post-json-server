# JSON Server for Blog Post

* Change directory to blog-post-json-server
* Run `npm install` to install required packages, including `json-server` and `ngrok`
* Open terminal to run `npm run db` and leave it runnin*g
* Open another terminal to run `npm run tunnel`
* The forwarding section of the second terminal will be the API endpoint

## Change port
The default port of both json-server and ngrok is 3000, to change it to another port, modify `scripts` in `package.json`.
For example:
```
"db": "json-server -w db.json -p 3001",
"tunnel": "ngrok http 3001"
```
