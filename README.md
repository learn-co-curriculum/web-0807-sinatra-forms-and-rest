## Sinatra

## Performing CRUD Actions on a Resource

## Objectives
- Understand how the CRUD actions map to RESTful routes


### Deliverables

For each of the deliverables consider what route(s) are necessary

#### Read
- As a site visitor, I should be able to see a list of all the books
1. does my schema need to change?
yes
2. What route(s) do i need?
index
Book.all
SELECT * FROM BOOKS
GET '/books'
GET '/all_books'


- As a site visitor, I should be able to see info about an individual book
1.
show
Book.find_by(id: params[:id])
SELECT * FROM BOOKS WHERE books.id = ?, params[:id]
2. GET '/books/:id'

#### Create
- As a site visitor, I should be able to create a new book
2. GET 'books/new'  POST '/books'

#### Update
- As a site visitor, I should be able to edit an existing book

#### Destroy
- As a site visitor, I should be able to delete a book from the database


Representational State Transfer
ReST



'/teams/7/players'
