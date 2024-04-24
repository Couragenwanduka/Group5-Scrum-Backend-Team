# SUB-DOCUMENTATION ECO-AGRIC BACKEND

## Purpose

This repository focuses on recent Scrum development for the backend of Eco-Agric.

## Introduction

Welcome to our Backend Documentation! This guide provides a detailed overview of our backend system, including architecture, APIs, database schema, and deployment processes. Whether you're a new developer, team member, or contributor, this document will help you understand and work effectively with our backend components. Dive in to explore the technologies we use, API documentation, database structure, security considerations, deployment guides, and contribution guidelines. Let's build great things together!

# Routes

### Create Farmer

* Endpoints: `/api/v1/agrico-blog`

    - POST `/api/v1/agrico-blog/saveFamer`: Farmers can sign up to the agrico-blog.
    - POST `/api/v1/agrico-blog/logiFamer`: Farmers can log in.

### Create User

* Endpoint: `/api/v1/agrico-blog/user`

    - POST `/api/v1/agrico-blog/user/createUser`: Users can sign up.
    - POST `/api/v1/agrico-blog/user/login`: Users can log in.

### Create Post

* Endpoint: `/api/v1/agrico-blog/post`

    - POST `/api/v1/agrico-blog/post/createPost`: Farmers can create a post to a blog.
    - PATCH `/api/v1/agrico-blog/post/editPost:id`: Farmers can edit a post with post ID.
    - DELETE `/api/v1/agrico-blog/post/deletePost:id`: Farmers can delete a post with post ID.
    - GET `/api/v1/agrico-blog/post/getPost`: Used to display post information.

### Comment

* Endpoint: `/api/v1/agrico-blog/post/comment`

    - POST `/api/v1/agrico-blog/post/comment/createComment:id`: Users can create a comment with user id.
    - GET `/api/v1/agrico-blog/post/comment/showComment`: For displaying user Comment information.
    - DELETE `/api/v1/agrico-blog/post/comment/deleteComment:id`: Users can delete a comment using the comment id.
    - PATCH `/api/v1/agrico-blog/post/comment/editComment:id`: Users can edit a comment using the comment id.
