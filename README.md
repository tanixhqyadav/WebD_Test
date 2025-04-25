Youtube Clone  With Follwoing funcanalties Capstone Project: Develop a YouTube Clone Using the MERN
Stack (400 marks)
Objective: Create a full-stack YouTube clone where users can view and interact with videos.
This project will help you understand how to build a real-world application using MongoDB,
Express, React, and Node.js (MERN stack).
Requirements:
Front-End (React)
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
the home page will be displayed.
