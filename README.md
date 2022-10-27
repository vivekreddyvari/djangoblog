# djangoblog
Blog with Api


Backend Blog + API

Web app and API that presents Blog Posts in a feed on a web page. Clicking into a blog post should go to a page dedicated to the blog post.

Requirements:
- Django Python with a database of your choice
- No crashes, compiler errors, or warnings
- Must compile and run locally

- Easy and intuitive to use:
— API that provides a feed of blog posts with one endpoint, detailed blog post data with another endpoint, and the ability to create blog posts with an authenticated endpoint (e.g. tokens)
— Website displays a feed of blog posts, with ability to manually refresh with a UI element on the page itself
— Supports account login (and log out) and sign up, allowing a signed in user to post a blog post (first name, email, password)
— Display vital blog post information in the feed (image, headline, a few lines of text from the blog post, date, author name, etc)
— Clicking a post should open into the full view for the blog post
— Ability to leave the blog post and go back to the feed
- Best practices for separation of concerns, handling of secrets, etc
- A handful of unit and integration tests
- Handling of bad or malformed data, injection and XSS attacks and other security concerns, good error handling, other real world situations that may arise
