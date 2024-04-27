# Library_System
Library System: C++ program for book management with features including adding, removing, renting, searching, and editing book details. Utilized advanced OOP concepts and Data Structures, implemented using Double Linked List.

LibrarySystem Class:
----------------------------------------
- Constructor: Initializes library statistics.
- addBook(): Adds a book to the library, allowing placement at the top, end, or a specific position.
- removeBook(): Removes a book from the library, from the first, last, or a specific position.
- borrowBook(): Removes a book from the library when borrowed.
- returnBook(): Adds a book back to the library after return.
- printAvailableBooks(): Prints available books in ascending or descending order.

Book Class:
----------------------------------------------------------
- Attributes: Title, author, genre, ISBN, availability.
- setAll(): Sets all book attributes.
- operator<<: Prints book details neatly.
- operator==: Compares books by title.

DataStructure Class (Generic Doubly Linked List):
--------------------------------------------------------
- Constructor/Destructor: Initializes/frees memory.
- insertAtHead(), insertAtTail(): Inserts at beginning/end.
- insertAtPosition(), removeAtPosition(): Inserts/removes at a specific position.
- printElements(), reverseElements(): Prints and reverses list.
- searchElement(), getLength(): Searches for an element and returns list length.

Node Class:
----------------------------------------------------------------------
- Template Class: Represents a doubly linked list node.
- Attributes: Key (data), next, and previous pointers.

The system efficiently manages a library collection, providing basic book operations
