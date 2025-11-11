# 📚 PeekABook: A Java NetBeans-Based Online Bookshop Application

**PeekABook** is a Java NetBeans-based application designed to offer book lovers a seamless and user-friendly online purchasing experience. It aims to shift the traditional browsing and purchasing of books to a convenient, digital platform.

Customers can use the application to browse a vast selection of books, make purchases, and manage their personal information from the comfort of their own homes.

---

## 💡 Vision and Mission

### Vision
* Our vision is to develop a bookshop application that serves as a **digital haven for book enthusiasts**.
* To nurture a thriving and diverse community of readers.
* We strive to revolutionize how people discover, explore, and interact with books in the modern era, fostering a passion for reading and exploring.

### Mission 
* Our mission is to provide a purchasing experience for books that **transcends the traditional shops' store**.
* We are committed to assembling a vast collection of diverse and captivating books that appeal to a variety of interests, ages, and reading preferences.
* By leveraging the power of technology, we intend to develop a platform that enables customers to explore, discover, and interact with written work in a personalized and meaningful manner.

---

## ✨ Notable Features

* **User Registration & Login**
* **Book Catalog & Recommendations**
* **Shopping Cart & Payment Integration**
* **Wishlist & Favorites**

---

## 🛠️ Technical Details (Code Snippets)

The application is based on Java NetBeans.

### Database Connection 
* The `MyConnection` class provides a way to obtain a database connection to a MySQL database.
* It encapsulates the necessary steps to load the driver (`com.mysql.cj.jdbc.Driver`) and establish the connection.
* It follows the singleton pattern, ensuring a single point of connection and reusability.

### User Authentication
* **Login:** The code snippet is used for verifying user credentials by executing an SQL query against a database table. If the credentials match, it opens a new window (`LoginSuccess`) and passes relevant information to it.
* **Register:** The code validates user input for a registration form by checking if the username, email, password, and password confirmation fields are filled correctly. Otherwise, it prepares an SQL statement to insert the user's information into a database table called `register`.

### Shopping and Catalog Features
* **Image Slider:** An array of images is initiated, and two buttons ("previous" or "next" function) are used to accomplish the image slider slideshow.
* **Quantity & Price, Add to Cart:** This code handles the logic for updating the quantity, price, and total price of a book in a shopping cart. It uses a `JSpinner` to allow the user to select the desired quantity.
* **Wishlist & Cart Placement:** Methods (`WishPlacement` and `CartPlacement`) dynamically add panels to specific container panels (`WishlistPanel` and `CartPanel`) in the GUI.
* **Book List Array:** The application sets up an array of `BookList` objects with predefined book titles and prices.

---

## 🖼️ Application Screenshots

![Screenshot 2025-03-08 162143](https://github.com/user-attachments/assets/4bd5396f-4d6e-4c20-b3a9-bc3c956a59b8)

![Screenshot 2025-03-08 160315](https://github.com/user-attachments/assets/debb8077-e41a-4860-b43b-fcbe850f8ecc)
