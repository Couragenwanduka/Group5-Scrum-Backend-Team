# SUB-DOCUMENTATION ECO-AGRIC BACKEND

## Purpose

This repository focuses on recent Scrum development for the backend of Eco-Agric.

## Introduction

Welcome to our Backend Documentation! This guide provides a detailed overview of our backend system, including architecture, APIs, database schema, and deployment processes. Whether you're a new developer, team member, or contributor, this document will help you understand and work effectively with our backend components. Dive in to explore the technologies we use, API documentation, database structure, security considerations, deployment guides, and contribution guidelines. Let's build great things together!

# Routes

### Create Farmer

* Endpoints: `/api/v1/agrico-blog`

    - POST `/api/v1/agrico-blog/saveFamer`: Farmers can sign up to the agrico-blog.
    - POST `/api/v1/agrico-blog/loginFamer`: Farmers can log in.
    - POST `/api/v1/agrico-blog/verifierFamer`: Famer can verify their account.
    - patch `/api/v1/agrico-blog/updatePassword`: Famer can update their password
    - Delete `/api/v1/agrico-blog/deleteAccount`: Famer can delete their account


### Create User

* Endpoint: `/api/v1/agrico-blog/user`

    - POST `/api/v1/agrico-blog/user/createUser`: Users can sign up.
    - POST `/api/v1/agrico-blog/user/login`: Users can log in.
    - GET `/api/v1/agrico-blog/user/getallLikedposts`: Users can get all posts they liked.
    - GET `/api/v1/agrico-blog/user/getallcomments`: Users can get all comments
    - patch `/api/v1/agrico-blog/user/updatePassword`: User can update their password
    - Delete `/api/v1/agrico-blog/user/deleteAccount`: User can delete their account
    - POST `/api/v1/agrico-blog/user/followFamer`: User can follow Farmer
    - Delete `/api/v1/agrico-blog/user/unfollowFamer`: user can unfollow Farmer

### Create Post

* Endpoint: `/api/v1/agrico-blog/post`

    - POST `/api/v1/agrico-blog/post/createPost`: Farmers can create a post to a blog.
    - POST `/api/v1/agrico-blog/post/preorder`: Users can preorder crops or seeds
    - PATCH `/api/v1/agrico-blog/post/editPost:id`: Farmers can edit a post with post ID.
    - DELETE `/api/v1/agrico-blog/post/deletePost:id`: Farmers can delete a post with post ID.
    - GET `/api/v1/agrico-blog/post/getPost`: Used to display post information.

### Comment

* Endpoint: `/api/v1/agrico-blog/post/comment`

    - POST `/api/v1/agrico-blog/post/comment/createComment:id`: Users can create a comment with user id.
    - GET `/api/v1/agrico-blog/post/comment/showComment`: For displaying user Comment information.
    - DELETE `/api/v1/agrico-blog/post/comment/deleteComment:id`: Users can delete a comment using the comment id.
    - PATCH `/api/v1/agrico-blog/post/comment/editComment:id`: Users can edit a comment using the comment id.

### Message

* Endpoint: `/api/v1/agrico-blog/message/`

  - POST `/api/v1/agrico-blog/message/createMessage:id`:User can create and send messages to Famers
 - PATCH `/api/v1/agrico-blog/message/editMessage:id`: User can edit messages using the message id
 - DELETE `/api/v1/agrico-blog/message/delete:id`: Users can delete a message using the message id


