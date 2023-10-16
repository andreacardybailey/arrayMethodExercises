# Exercise: Bookstore Inventory Management

### Introduction:
You are given a list of books in a bookstore's inventory. Each book is represented as an object with a title, author, price, and sold status. Your task is to create a series of functions that will help manage this inventory using some of the provided array methods.

### Given:
Here's an example of the array representing the bookstore's inventory:

```javascript
const inventory = [
  { title: 'Harry Potter', author: 'J.K. Rowling', price: 10.99, sold: false },
  { title: 'Lord of the Rings', author: 'J.R.R. Tolkien', price: 15.99, sold: true },
  { title: 'Dune', author: 'Frank Herbert', price: 12.99, sold: false }
];
```

## Tasks:

### Adding a Book

Write a function named addBook that has two parameters: an inventory array and a book object. The function should add the book to the end of the inventory array and return the updated inventory.

**Use:** push

### Selling a Book

Write a function named sellBook that has two parameters: an inventory array and a book object. If the book is found, mark it as sold (by updating its "sold" property) and return the updated inventory.

**Use:** find

### Removing Last Added Book

Write a function named removeLastAdded that has one parameter: an inventory array. The function removes the most recently added book. Return the updated inventory.

**Use:** pop

### List all Authors

Write a function named listAllAuthors that has one parameter: an inventory array. It returns an array of all unique authors in the inventory.

**Use:** map and filter

### Total Inventory Value

Write a function named totalValue that has one parameter: an inventory array. It returns the total price of all unsold books in the inventory.

**Use:** filter and reduce

### First 3 Expensive Books

Write a function named top3Expensive that has one parameter: an inventory array. It returns an array of titles of the 3 most expensive unsold books.

**Use:** filter, sort, and slice
