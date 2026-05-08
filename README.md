# DjangoBlog Enhanced

A Django-based blog website inspired by *Django for Beginners* by William S. Vincent, extended with authentication-based ownership permissions, automatic author assignment, and custom error handling.

---

# Project Description

This project is a personal portfolio application developed using Django and based on the blog tutorial presented in the book *Django for Beginners (5th Edition)* by William S. Vincent.

The application started from the examples provided in Chapters 6, 7, and 8 of the book, but it was extended with several custom features and logical improvements to enhance usability, security, and user experience.

This repository serves as part of my personal software development portfolio and demonstrates practical Django development concepts including:

- User authentication and registration
- CRUD operations
- Authorization and permissions
- Django class-based views
- Templates and routing
- Custom error handling

---

# Based On

This project was developed following the examples from the book:

**Django for Beginners (5th Edition)**  
By William S. Vincent  
ISBN: 9781735467269

The original tutorial chapters used as the base were:

- Chapter 6: Blog Website  
  https://github.com/wsvincent/djangoforbeginners/tree/main/ch06-blog

- Chapter 7: Forms  
  https://github.com/wsvincent/djangoforbeginners/tree/main/ch07-blog-forms

- Chapter 8: User Accounts  
  https://github.com/wsvincent/djangoforbeginners/tree/main/ch08-blog-users

---

# Custom Improvements and Modifications

The original tutorial project was extended with several custom improvements:

## Automatic Author Assignment

When creating a new blog post, the application no longer asks the user to select an author from a dropdown list containing all registered users.

Instead, the application automatically assigns the currently logged-in user as the author of the new post.

---

## Authorization for Editing and Deleting Posts

To edit or delete a blog post:

- The user must be authenticated (logged in)
- The user must be the original author of the post

Unauthorized users are prevented from modifying or deleting content created by others.

---

## Custom "Page Not Found" Handling

A custom **404 Page Not Found** page was added to improve the user experience when attempting to access a blog post or page that does not exist.

---

# Screenshots

## Home Page

![Home Page](assets/Screenshot_01_home_page.png)

---

## Login Page

![Login Page](assets/Screenshot_02_login_page.png)

---

## Signup Page

![Signup Page](assets/Screenshot_03_signup_page.png)

---

## New Post Page

![New Post Page](assets/Screenshot_04_new_post_page.png)

---

## New Post Page With Data

![New Post Page With Data](assets/Screenshot_05_new_post_page_with_data.png)

---

## Detail Post Page

![Detail Post Page](assets/Screenshot_06_detail_post_page.png)

---

## Edit Post Page

![Edit Post Page](assets/Screenshot_07_edit_post_page.png)

---

## Edit Post Page - User Not Logged In

![Edit Post Page Not Logged In](assets/Screenshot_08_edit_post_page_not_loggedin.png)

---

## Edit Post Page - No Permission

![Edit Post Page No Permission](assets/Screenshot_09_edit_post_page_no_permission_to_edit.png)

Please note that the user attempting to edit the post is not the original author of the post.

---

## Delete Post Page

![Delete Post Page](assets/Screenshot_10_delete_post_page.png)

---

## Delete Post Page - User Not Logged In

![Delete Post Page Not Logged In](assets/Screenshot_11_delete_post_page_not_loggedin.png)

---

## Delete Post Page - No Permission

![Delete Post Page No Permission](assets/Screenshot_12_delete_post_pageno_permission_to_delete.png)

Please note that the user attempting to delete the post is not the original author of the post.

---

## Custom 404 Page

![Page Not Found](assets/Screenshot_13_page_not_found.png)

---

# Technologies Used

- Python
- Django
- HTML
- CSS
- SQLite

---

# Learning Objectives

This project helped reinforce knowledge in:

- Django authentication system
- User authorization and permissions
- CRUD application development
- Django generic views
- URL routing
- Templates inheritance
- Error handling
- Secure application logic

---

# Future Improvements

Potential future improvements may include:

- Comment system
- User profile pages
- Rich text editor
- Post categories and tags
- Search functionality
- Responsive UI improvements
- Deployment to a cloud platform

---

# Author

Fausto Gonzalez

This project is part of my personal software development portfolio.