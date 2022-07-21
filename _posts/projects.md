### Each resource structured in 4 modules
- Router
- Model
- Controller
- View

## Accessing the API 
### Book routes
| Methods | Endpoints                          | Access  | Description                              |
| ------- | ---------------------------------- | ------- | ---------------------------------------- |
| GET     | /                                  | Public  | View home page                           |
| GET     | /book/:id/create                   | Public  | Get HTML form to add a book              |
| POST    | /book/:id/create                   | Public  | Add a book                               |
| GET     | /book/:id/delete                   | Public  | Get HTML form to delete a book           |
| POST    | /book/:id/delete                   | Public  | Delete a book                            |
| GET     | /book/:id/update                   | Public  | Get HTML form to update a book           |
| POST    | /book/:id/update                   | Public  | Update a book                            |
| GET     | /book/:id                          | Public  | View a book                              |
| GET     | /books                             | Public  | View list of all books                   |

### Author routes
| Methods | Endpoints                          | Access  | Description                              |
| ------- | ---------------------------------- | ------- | ---------------------------------------- |
| GET     | /author/:id/create                 | Public  | Get HTML form to add an author           |
| POST    | /author/:id/create                 | Public  | Add an author                            |
| GET     | /author/:id/delete                 | Public  | Get HTML form to delete an author        |
| POST    | /author/:id/delete                 | Public  | Delete an author                         |
| GET     | /author/:id/update                 | Public  | Get HTML form to update an author        |
| POST    | /author/:id/update                 | Public  | Update details of an author              |
| GET     | /author/:id                        | Public  | View details of an author                |
| GET     | /authors                           | Public  | View list of all authors                 |

### Genre routes
| Methods | Endpoints                          | Access  | Description                              |
| ------- | ---------------------------------- | ------- | ---------------------------------------- |
| GET     | /genre/:id/create                  | Public  | Get HTML form to add a genre             |
| POST    | /genre/:id/create                  | Public  | Add a genre                              |
| GET     | /genre/:id/delete                  | Public  | Get HTML form to delete a genre          |
| POST    | /genre/:id/delete                  | Public  | Delete a genre                           |
| GET     | /genre/:id/update                  | Public  | Get HTML form to update a genre          |
| POST    | /genre/:id/update                  | Public  | Update a genre                           |
| GET     | /genre/:id                         | Public  | View all books of the genre              |
| GET     | /genres                            | Public  | View list of all genres                  |