# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.


What is the purpose of a backend?

```bash
// The purpose of the backend is to store and maintain the data needed
// for the frontend
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
// The model layer
```

Which layer in the MVC pattern communicates with the model?

```bash
// The controller is the only layer to communicate with the model
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
// Because we are building single page applications
```

What does C.R.U.D stand for?

```bash
// Create, Read, Updae, Delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
// The controller
```

A user action fires a `GET` request for `person/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
// The controller gets the request from the browser and fomulates the // request to the model layer. The model retrieves the request and   retrieves it from the database and returns it back to the controller which then sends the data to the browser
```

What is the command to generate a new rails-api app?

```bash
// rails-api new "app_name"
```

What is the command to start an instance of a rails server?

```bash
// rails s || rails server
```

What are the commands to drop, create and migrate a database? (3 bullet points)

```bash
// rake db:drop
rake db:create
rake db:migrate
```

What is the command to scaffold a pet with a name and an age?

```bash
// rails-api g scaffold pet name:string age:int
```

List two advantages of using serializers? (2 bullet points)

```bash
// 1) It ensures uniqueness between rows
2) Easy to retieve data
```
