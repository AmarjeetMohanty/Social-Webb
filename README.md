# Social-Webb


Social-Webb is a social media web application developed using modern web technologies. It allows users to connect with friends, share updates, post photos, and interact with each other through comments and likes.

## Features

- **User Registration and Authentication**: Users can create an account and log in securely to access the application's features.
- **User Profiles**: Each user has a profile that displays their information, profile picture, and posts.
- **Post Creation and Sharing**: Users can create posts, add captions, and share them with their friends.
- **News Feed**: The application provides a news feed where users can see the latest posts from their friends and the people they follow.
- **Likes and Comments**: Users can like and comment on posts to engage with other users.
- **Friendship System**: Users can send friend requests and accept or reject requests from others.
- **Notifications**: Users receive notifications for new friend requests, likes, and comments on their posts.
- **Search Functionality**: Users can search for other users by their username or name.
- **Privacy Settings**: Users can control their privacy settings to manage who can view their posts and profile.
- **Responsive Design**: The application is designed to be responsive and accessible across different devices.

## Installation

To run the Social-Webb application locally, follow these steps:

1. Clone the repository:

```
git clone https://github.com/AmarjeetMohanty/Social-Webb.git
```

2. Navigate to the project directory:

```
cd Social-Webb
```

3. Install the dependencies:

```
npm install
```

4. Create a `.env` file in the root directory and provide the following environment variables:

```
MONGO_URL=<your_database_url>
JWT_SECRET=<your_session_secret>
PORT=<Port Number>
```

5. Start the application:

```
npm start
```

6. Open your browser and visit `http://localhost:3000` to access the Social-Webb application.

## Technologies Used

- **Node.js**: Server-side JavaScript runtime environment.
- **Express.js**: Web application framework for Node.js.
- **MongoDB**: NoSQL database used for storing user information and posts.
- **Mongoose**: Object Data Modeling (ODM) library for MongoDB.
- **Passport.js**: Authentication middleware for Node.js.
- **EJS**: Templating engine for generating dynamic HTML pages.
- **Bootstrap**: Front-end framework for building responsive and mobile-first websites.
- **Multer**: Middleware for handling file uploads.
## Updates
SignIn functionality still to be implemented.Meanwhile you can try a mock account 

- **email**: janedoe@gmail.com
- **password**: hello



## Contributing

Contributions to Social-Webb are welcome! If you find a bug or have a suggestion for a new feature, please open an issue or submit a pull request. Make sure to follow the existing code style and include relevant tests when submitting a pull request.


## License

Social-Webb is released under the [MIT License](LICENSE).


