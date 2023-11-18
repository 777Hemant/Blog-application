Project Structure
app.js: Entry point of the application.
routes/blog.js: Contains API routes for blog functionality.
config/database.js: Connects to the MongoDB database.
models/commentModel.js, models/likeModel.js, models/postModel.js: MongoDB models for comments, likes, and posts.
controllers/CommentController.js, controllers/LikeController.js, controllers/PostController.js: Business logic for handling comments, likes, and posts.
API Endpoints
GET /api/v1/dummyroute: Dummy endpoint for testing.
POST /api/v1/comments/create: Create a new comment.
POST /api/v1/posts/create: Create a new post.
GET /api/v1/posts: Get all posts with likes and comments.
POST /api/v1/likes/like: Like a post.
POST /api/v1/likes/unlike: Unlike a post.
Dependencies
express: Web framework for Node.js.
mongoose: MongoDB object modeling tool.
dotenv: Loads environment variables from a .env file.
