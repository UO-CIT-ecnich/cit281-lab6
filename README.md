# Description

In this lab, my main goal was to create a digital book library using JavaScript classes. It involved several steps, so let me break it down for you:

First, I joined GitHub and went through the Introduction to GitHub course. This was important because GitHub would be used in the lab and it helped me understand the basics of version control and collaboration.

Next, I created a new file called "lab-06.js" in the cit281/p5/lab-06 folder. This was the file where I would be implementing the classes for the book library.

I then learned about the two main classes: Book and Library. The Book class had properties such as title, author, and publication date. The Library class had properties for the library name and an array to store the books. Additionally, the Library class had methods like count (to return the number of books), books (to return a copy of the book array), addBook (to add a book to the library), and listBooks (to display the details of each book in the library).

I started by implementing the Book class, creating an instance of a book called "atomicHabits" with its title, author, and publication date. This allowed me to test the Book class and ensure that it was working correctly.

After that, I implemented the Library class, including all the methods mentioned earlier. I created a Library instance called "library" with the name "New York Times Best Seller List". Then, I added the "atomicHabits" book to the library using the addBook method and tested the count and listBooks methods to make sure they were functioning as expected.

To expand the library, I added at least two more books to the library by creating new instances of Book and using the addBook method to add them to the library.

Finally, I made some modifications to the classes. I added an ISBN property to the Book class to serve as a unique identifier for each book. Additionally, I implemented the deleteBook method in the Library class, which allowed me to remove a book from the library by providing its ISBN.

To test these changes, I created new instances of books with their respective titles, authors, publication dates, and ISBNs. I added these books to the library using the addBook method, and then I tested the count, listBooks, and deleteBook methods to ensure that the modifications were successful.

Throughout the lab, I gained experience in creating and working with JavaScript classes, understanding their properties and methods, and utilizing them to build a functional book library. I also learned how to test the code and make necessary modifications to enhance the functionality. These skills are valuable for creating well-structured and maintainable code in JavaScript projects.
