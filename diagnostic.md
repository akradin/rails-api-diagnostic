# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```bash
To be able to store data
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
Model
```

Which layer in the MVC pattern communicates with the model?

```bash
Controller
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
Views are mostly front end interactions with our app, we are looking mostly at the back end when it comes to the MVC
```

What does C.R.U.D stand for?

```bash
Crete Read Update Destroy
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
Controller
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```bash
Create, Get, Update, Delete, Show
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
 - User types in URL and hits enter and submits a GET request
 - Router directs GET request to proper Controller
 - Controller picks whichever model has the data the customer requested
 - Model sends data back to Controller
 - Controller sends data back to router
 - Router sends data back to User who sees it via the client
```

What is the command to generate a new rails-api app?

```bash
bundle exec rake generate
```

What is the command to start an instance of a rails server?

```bash
bundle exec rails server
```

What are the commands to drop, create and migrate a database from the command
line? (3 bullet points)

```bash
bundle exec rake db:drop
bundle exec rake db:create
bundle exec rake db:migrate
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
bundle exec rails generate scaffold Pet name:string age:integer
```
