# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
Backend contains all the data that corelates to the frontends UI.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
Model
```

Which layer in the MVC pattern communicates with the model?

```md
Controller
```

Why don't we use views in our interpretation of the MVC pattern?

```md
Because views represent the stored data files within the MVC pattern. For example controller & model folders can be considered "views."
```

What does C.R.U.D stand for?

```md
Create
Read
Update
Delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
Cotnrollers
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
index
update
create
show
edit
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
1. Server requests data using routes to connect with the controller
2. Controller requests the data from the model
3. Model sends data back to the controller
4. Controller sends data to the server
```

What is the command to generate a new rails-api app?

```bash
bin/rails generate
```

What is the command to start an instance of a rails server?

```bash
bin/rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
db:drop
db:create
db:migrate
db:seed
db:examples
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
name:string
age:integer
```
