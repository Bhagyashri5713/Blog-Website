Instruction to Run the Blog Application:-

To run the backend, use the command npm start. The backend is built using Node.js and Express.js, with MongoDB as the database. And the Front end is build using React and Tailwind CSS.

Authentication endpoints:

	1. Signup: To sign up, send a POST request to http://localhost:8000/api/auth/signup.

	2. Sign in: To sign in, send a POST request to http://localhost:8000/api/auth/signin.

User endpoints:

	1. Get a user: To retrieve a user by their ID, send a GET request to http://localhost:8000/api/users/find/{userId}.

	2. Update a user: To update a user by their ID, send a PUT request to http://localhost:8000/api/users/{userId}.

	3. Delete a user: To delete a user, send a DELETE request to http://localhost:8000/api/users/{userId}.

	4. Follow a user: To follow a user, send a PUT request to http://localhost:8000/api/users/follow/{userId}.

	5. Unfollow a user: To unfollow a user, send a PUT request to http://localhost:8000/api/users/unfollow/{userId}.

Post endpoints:

	1. Create a post: To create a post, send a POST request to http://localhost:8000/api/posts/.

	2. Delete a post: To delete a post, send a DELETE request to http://localhost:8000/api/posts/{postId}.

	3. Like/Dislike a post: To like or dislike a post, send a PUT request to http://localhost:8000/api/posts/{postId}/like.

	4. Get all timeline posts: To get all posts from the user's timeline, send a GET request to http://localhost:8000/api/posts/{userId}/timeline.

	5. Get user's posts only: To get posts from a specific user, send a GET request to http://localhost:8000/api/posts/user/all/{userId}.

	6. Explore all posts: To explore all posts, send a GET request to http://localhost:8000/api/posts/explore.

Note: All endpoints require a JWT token for security purposes.
