# ASPNET Blog

[![licence mit](https://img.shields.io/badge/licence-MIT-blue.svg)](https://github.com/louresb/TodoApp/blob/main/LICENSE)
![Development Status Badge](https://img.shields.io/badge/Status-Completed-green)

This repository contains the source code for a blog application developed using ASP.NET Core. The application allows users to register, log in, create blog posts, manage categories, and upload images for their profile. The codebase follows the MVC (Model-View-Controller) architectural pattern and utilizes Entity Framework Core for data access.

## Features

- **User Registration and Login:**
Users can register an account by providing their name, email, and password.
Passwords are securely hashed using a password hashing algorithm.
Registered users can log in to the application using their email and password.

- **Blog Posts:**
Authenticated users can create new blog posts.
Each blog post has a title, summary, body content, and associated category.
Posts can be edited and deleted by the author.

- **Categories:**
Users can manage categories for organizing blog posts.
Categories have a name and a slug for identifying them.
Categories are stored in the database and can be created, updated, and deleted.

- **Image Upload:**
Authenticated users can upload an image to use as their profile picture.
Uploaded images are stored in the database or file system, depending on the application's configuration.

## Screenshots

<div align="center">

<img src="https://github.com/louresb/ASPNET6-Blog/assets/103293696/5dfb4618-3179-4ab9-b877-a07eb395b954" width="400" height="140"> <img src="https://github.com/louresb/ASPNET6-Blog/assets/103293696/cf7d103a-5476-4051-9c78-1c2d2b1d2bb3" width="400" height="140">

<img src="https://github.com/louresb/ASPNET6-Blog/assets/103293696/bd1a57ff-8f45-4cec-8f3e-14cbfd888782" width="400" height="140"> <img src="https://github.com/louresb/ASPNET6-Blog/assets/103293696/89b3a4ec-c41c-4862-ba46-3205d59f1f65" width="400" height="140">
  
</div>

## Learning resources

This API was created using [Balta.io](https://balta.io/)'s backend course. I recommend checking it out if you're interested in learning about .NET programming.

## License
[MIT License](https://github.com/louresb/ASPNET6-Blog/blob/main/LICENSE) © [Bruno Loures](https://github.com/louresb)
