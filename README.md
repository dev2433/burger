# burger

A simple app using [Node.js](https://nodejs.org/en/),
[Express](http://expressjs.com/), [Handlebars](http://handlebarsjs.com/), and
[MySQL](https://github.com/mysqljs/mysql).


# API

A user can select the `API Burgers List` in the footer to view all of the burger
data in the database. This is done through a `GET` request. This route is
`api/burgers`.

# Data

Each burger has an `id`, `burger_name`, `devoured`, and `created_at`. The `id`
is the primary key and is auto-incremented.
