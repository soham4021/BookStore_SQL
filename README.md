
# Project Title

 A Book Store web application which fetches data from a SQL database and displays them ans also performe some basic SQL fucntionalities like Updating and Deleting books from the database.







# API Reference


## Get all items

```http
  GET /books
```

#### Fetches all the books from the database using the SQL command      
    const q = "SELECT * FROM books";

## Add a book to the database

```http
  POST /books
```

#### Adds a new book to the SQL database using the SQL command
    const q = "INSERT INTO books() VALUES (?)";

## Delete a book

```http
  DELETE /books/:id
```

#### Deletes a certain book from the SQL database using the SQL command 
    const q = " DELETE FROM books WHERE id = ? ";

## Update a book

```http
  PUT /books/:id
```
#### Updates a certain book from the SQL database using the SQL command
    const q = "UPDATE books SET `title`= ?, `decr`= ?, `price`= ?, `cover`= ? WHERE id = ?";
    
![Book_SQL](https://github.com/soham4021/BookStore_SQL/assets/92176024/c4b6acfe-4ae9-41ec-9731-2d082e92d721)



![Update_Book_SQL](https://github.com/soham4021/BookStore_SQL/assets/92176024/2f9115d3-767a-4550-a14a-a2cfcaaeda41)


![Add_Book_SQL](https://github.com/soham4021/BookStore_SQL/assets/92176024/e2dd524f-888f-415a-a9a3-a7483802f427)

