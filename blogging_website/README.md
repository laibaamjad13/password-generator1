# Complete Blogging Website

A full-featured blogging platform built using Django, where users can register, create, edit, and delete their own posts. The platform includes categories, tags, a search bar, and a comment system.

## Features

### **1. User Features**
- **User Authentication**
  - Register, login, and logout functionality.
  - Password reset functionality.
- **Post Management**
  - Users can create, edit, and delete their own posts.
  - Posts contain a title, content, timestamp, and optional images.
  - Posts can be categorized using categories or tags.
- **Post Listing and Filtering**
  - Homepage displays all posts.
  - Filter posts by category, tag, or author.
  - Search bar to find posts by title or content.
- **Post Ownership**
  - Users can only edit or delete their own posts.
- **Comment System**
  - Users can add comments on posts.
  - Display comments below each post.

### **2. Templates and Static Files**
- **Navigation Bar**
  - Includes links for *Home, Create Post, Login, Logout, and Register*.
  - Displays the logged-in user's name.
- **Styling**
  - Uses Bootstrap for styling.
  - Clean and user-friendly layout.

### **3. Admin Features**
- Django’s admin panel allows management of posts, users, and comments.

### **4. Security**
- Restricts non-owners from editing or deleting posts.

---

## **Installation and Setup**

### **1. Clone the Repository**
```sh
git clone https://github.com/laibaamjad13/password-generator1/tree/main/blogging_website
cd blogging-website
