\# Blog Post App

A full-stack blog application built to explore and practice backend development technologies. This application provides a platform for creating and managing blog posts with user authentication.

\## Features

\- Create, read, update, and delete blog posts

\- User authentication and authorization

\- Responsive design optimized for various devices

\## Technologies Used

\- \*\*Backend:\*\* Node.js, Express.js

\- \*\*Frontend:\*\* EJS templates

\- \*\*Database:\*\* SQLite

\- \*\*Authentication:\*\* Passport.js

\## Installation

1\. Clone the repository:

\`\`\`markdown

git clone https://github.com/JashawnRogers/blog.git

cd blog

\`\`\`

2\. Install dependencies:

\`\`\`markdown

npm install

\`\`\`

3\. Set up environment variables:

\`\`\`markdown

\# Create a .env file in the root directory and add:

DATABASE\_URL=your\_database\_url

SESSION\_SECRET=your\_session\_secret

\`\`\`

4\. Start the application:

\`\`\`markdown

npm start

\`\`\`

The application will be running at \`http://localhost:3000\`.

\## Usage

Navigate to \`http://localhost:3000\` to view the homepage.

To create and manage blog posts:

1\. Register a new account or log in

2\. Click "New Post" to create content

3\. Use the dashboard to manage your posts

\## Folder Structure

\`\`\`markdown

blog/

├── node\_modules/ # Project dependencies

├── public/ # Static assets

│ ├── css/ # Stylesheets

│ └── images/ # Image assets

├── views/ # EJS templates

├── .env # Environment variables

├── package.json # Project metadata and dependencies

└── server.js # Main application file

\`\`\`

\## Contributing

1\. Fork the repository

2\. Create a new branch for your feature

3\. Commit your changes

4\. Push to your branch

5\. Submit a pull request

\## License

This project is licensed under the MIT License. See the \[LICENSE\](LICENSE) file for details.

\## Support

If you encounter any issues or have questions, please \[open an issue\](https://github.com/JashawnRogers/blog/issues) on the GitHub repository.