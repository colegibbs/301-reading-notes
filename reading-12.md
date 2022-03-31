# Reading 12: CRUD

## [Reading: Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

### In your own words, describe what each group of status code represents

- 100’s = Informational Status Codes
- 200’s = Success Codes
- 300’s = Redirection Codes
- 400’s = Client Error Codes
- 500’s = Server Error Codes

### What is a status code 202?

This is an accepted status. It means that the clients request has been sent, but will be proccessed asyncronosly.

### What is a status code 308?

This is a permanent redirect. It means that the client needs to use a different url to access the resource they are after.

### What code would you use if an update didn’t return data to a client?

204

### What code would you use if a resource used to exist but no longer does?

308

### What is the ‘Forbidden’ status code?

The client doesn't have authorization to access the resource.

## [Video: Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

### Why do we need to pull our MongoDB database string out of our server and put it into our .env?

So that users and other devs don't have access to the db string.

### What is middleware?

Middle ware are router files.

### What does app.use(express.json()) do?

This allows are server to accept json as a body.

### What does the /:id mean in a route?

It means that this route will come in with an id at this location which can be accessed with req.params.id.

### What is the difference between PUT and PATCH?

PUT writes over the entire data object while PATCh replaces different properties of the data object.

### How do you make a default value in a schema?

default: 'whatevery you want' inside the data schema object.

### What does a 500 error status code mean?

Error on the server.

### What is the difference between a status 200 and a status 201?

201 is successfully created an object whil 200 is the request was successful.
