# 🎨 YouTube Clone Using the MERN 🚀

Welcome to **YouTube_Clone**, a repository containing my code and file structure of YouTube Clone🌟
This is made on 25.04.2025 for end-term exam!!

---
# Objective: 
**Create a full-stack YouTube clone where users can view and interact with videos.**
This project will help you understand how to build a real-world application using MongoDB,
Express, React, and Node.js (MERN stack).

---
# Requirements
**Front-End (React)**
1. Home Page:
○ Display a YouTube Header.
○ Display a static sidebar which you can toggle from the top hamburger menu.
○ Display filter buttons at the top.
○ Display a grid of video thumbnails.
○ Each video card should show:
■ Title
■ Thumbnail
■ Channel Name
■ Views
Sample data for videos:
Sample Data:
[ { "videoId": "video01", "title": "Learn React in 30 Minutes", "thumbnail URL":
"https://example.com/thumbnails/react30min.png", "description": "A quick tutorial to get started
with React.", "channelId": "channel01", "uploader": "user01", "views": 15200, "likes": 1023,
"dislikes": 45, "uploadDate": "2024-09-20", "comments": [ { "commentId": "comment01", "userId":
"user02", "text": "Great video! Very helpful.", "timestamp": "2024-09-21T08:30:00Z" } ] }]

2. User Authentication:
○ Allow users to register and log in with:
■ Username
■ Email
■ Password
○ Use JWT for authentication.
Before Sign In, header should have sign in button
When the user clicks on sign in, then it should take to a new URL where a google form
to login and register should be present.
User should sign in and after signing in, his/her name should be present at the top and
the home page will be displayed.Sample data for users:
{ userId: "user01", username: "JohnDoe", email: "john@example.com", password:
"hashedPassword123", avatar: "https://example.com/avatar/johndoe.png", channels:
["channel01"], }

3. Search and Filter Functionality:
○ Implement a search bar on the homepage.
This search bar is present in the header.Filter videos based on title.
○ Filter buttons should be implemented and filters should work based on category.
4. Video Player Page:
○ Display the selected video with:
■ Video player
■ Title and description
■ Channel name
■ Like and dislike buttons
■ Comment section (Ignore nested comments for now)
Users should be able to add , edit and delete comments. When a new comment is added ,
then it should be saved in the database along with that video.

---
# Steps that I used to initialise this project 🙃
1. First I created the github repo for uploading my project!.
2. Then links that repo with my new folder i.e. (YouTube_Clone)
3. Done first commit
4. Update readme with the project Objective and requirements!
5. Created the frontend folder, initialize the react by npm craete vite@latest
6. Install all required stuffs, and remove index.css and app.css.
7. Remove app.jsx file garbage code.
8. Then run the frontend to check if working fine or not!
9. Then create a new folder in (YouTube_Clone) folder and named backend npm init -y
10. Then install all the required packages and modules ex. npm i express mongoose
11. Start making app.js then require all the import functions!!
---
## 🌐 Connect with Me:
- 💼 **LinkedIn**: [Vibhu Dixit](https://www.linkedin.com/in/vibhu-dixit-b42a11251/)  
- 🐦 **Portfolio**: [vibhuportfolioo.netlify.app](https://vibhuportfolioo.netlify.app/)  
- 📧 **Email**: [vibhudixit88@gmail.com](mailto:vibhudixit88@gmail.com)  

✨ **Let’s Decode the World of Images Together!** ✨
