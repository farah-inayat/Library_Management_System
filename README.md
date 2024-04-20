##### *Made this for a group project for data structures course in my university. the group compromised of 3 people including me*
##### A description of the system is as follows
##### This library management system based on my small business Preloved Bookstore
###### -Our main moto is **You name it, we have it** To achieve this, we have created a comprehensive database of 5000+ books and 1000 users
###### -Details of the book include name, author, genre, rating, quantity, availability and a brief synopsis of the book.
###### -We have tried to make it as user-friendly as we can to encourage more people to read and enjoy books.
###### -To store 5000+ books data we have used hashtable. The size of the array is 26 as there are 26 alphabets. Consider the index 0 where all books whose name start with the alphabet “A” are stored in a binary tree
######
###### -User data is implemented using open address hashing with quadratic probing. The size of the hashtable is 1000 + 1/3(1000) User data contains name, ID, password, email address, home address and image The user can login into the portal, browse for books issue them and return them. When the user issues a book it stores the book in currently issued books linked list There is a check that the user can issued at most three books at a time. When the user returns the book it is removed from the currently issued book linkeds list and stored in history of issued books linked list
###### -Admin is the boss ! It has the methods to manage both user and books. It can add and delete a book. It can add a user. It can update both books and users information
