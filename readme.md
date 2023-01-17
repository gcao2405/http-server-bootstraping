IAM App: http server bootstraping (practical activity)

## Question 1: please write a small paper about that naming convention.
***
The Representational State Transfer (REST) naming convention is a set of guidelines for mapping CRUD (Create, Read, Update, and Delete) operations on resources to the corresponding HTTP verbs and HTTP paths in a RESTful API. These conventions help to make the API more intuitive and easy to use by ensuring that the names of endpoints are consistent and meaningful.

One of the key principles of REST is that each resource is identified by a unique URI. This URI should be used to indicate the type of operation that is being performed on the resource, such as creating a new resource, reading an existing resource, updating an existing resource, or deleting a resource.

The HTTP verbs, such as GET, POST, PUT, and DELETE, are used to indicate the type of operation that is being performed on the resource. For example, a GET request is used to read a resource, while a POST request is used to create a new resource.

The HTTP path is used to indicate the specific resource that is being accessed. For example, a path of "/users" would indicate that the resource being accessed is a collection of users, while a path of "/users/{id}" would indicate that the resource being accessed is a specific user.

In summary, the REST naming convention is a set of guidelines for designing a RESTful API that is intuitive and easy to use. It helps to ensure that the names of endpoints are consistent and meaningful, and that the HTTP verbs and HTTP paths are used in a way that clearly indicates the type of operation that is being performed on the resource.
***
## Question 2: considering they use REST naming convention, what would do POST /web-api/users and POST /web-api/sessions endpoints ?
***
Considering that the endpoints use the REST naming convention, the POST /web-api/users endpoint would likely be used to create a new user resource. It would likely accept a JSON payload containing the user's information such as name, email, and password and return a 201 status code to indicate that a new resource has been successfully created.

The POST /web-api/sessions endpoint would likely be used to create a new session resource. It would likely accept a JSON payload containing the user's email and password, and return a 201 status code to indicate that a new session has been successfully created and a JSON containing the session token if the authentication is successful, or an error if the authentication fails.

It's important to note that the exact behavior of these endpoints would depend on the specific implementation of the API and the requirements of the project.
***
