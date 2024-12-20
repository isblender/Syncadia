# Image-to-Song App

This is the full-stack implementation for the **Image-to-Song** iOS app, which allows users to take a picture, apply an algorithm on it, and get a song that resembles the image. The backend is built with **Node.js** and **Express**, and it uses **MongoDB and AWS S3** for user data management and storage of image history and song recommendations. The frontend is built with React Native.

## Features

- **Image Processing**: Receives image data from the iOS app for processing to generate song recommendations.
- **Song Recommendation**: Uses an algorithm to analyze the image and recommend a song that reflects the visual qualities of the image.
- **User Management**: Supports user data storage via MongoDB, including user authentication and personalized history of images and song responses.
- **Image and Song History**: Stores each user’s image-to-song history for easy retrieval and future reference.
