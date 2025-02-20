This project showcases a number of TypeScript capabilities, such as classes, generics, interfaces, async/await, and type annotations. It includes several challenges that demonstrate key TypeScript features.

Features Put into Practice

Section 1: Functions & Type Annotations

Task 1: CapitalizeWords Utility Function

capitalizes every word in a string by implementing a function.

uses TypeScript type annotations correctly.

appropriately handles empty strings.

Task 2: isValidNumber, a Number Validator Function

accepts an unknown-type value.

If the value is a valid number, it returns true; if not, it returns false.

Section 2: Types of Objects and Interfaces

Third Task: User System

provides the following properties to define an interface user: id, name, email, and an optional isAdmin.

implements the createUser method, which returns a success message after receiving a User object.

Section 3: OOP & Classes

Task 4: Classification of Products

implements a product class with the following attributes: category, price, and name.

These attributes are initialized via a constructor.

To determine the discounted price, use the getDiscountedPrice function.

puts public and private access modifiers into practice.

Section 4: Utility Types & Generics

Task 5: FilterArray Generic Function

FilterArray<T> is implemented as a generic function.

accepts as inputs a predicate function and an array.

Only the elements that satisfy the predicate requirement are returned.

Section 5: Async/Await in TypeScript

Task 6: Retrieve and Present Users

To obtain user information from https://jsonplaceholder.typicode.com/users, use fetch.

identifies, names, and emails of user objects in an array that is parsed and returned.

carries out error management for unsuccessful requests.

Utilized Technologies

TypeScript: JavaScript that is strongly typed.

To define the Product class, use object-oriented programming, or OOP.
Structured objects, such as users, are defined using interfaces.

Implemented in the filterArray function are generics.

Asynchronous user data retrieval is accomplished with Async/Await.


Try-catch is used to handle request failures in the async method used to get users.
