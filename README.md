# StaffEase

StaffEase is a comprehensive staffing management solution for small businesses, streamlining operations with real-time staff tracking, customer wait times, and an affordable POS system to enhance customer satisfaction and drive success.

## Features

- Real-time staff tracking and clock-in/clock-out functionality
- Customer wait time monitoring
- Affordable POS system integration
- Automated customer count
- Responsive and polished user interface
- Authentication and role-based access control
- Getting Started
- These instructions will help you set up and run the StaffEase project on your local machine for development and testing purposes.

## Prerequisites

Ensure you have the following installed on your system:

> TODO: This list is incomplete.

- Node.js (version 12.x or higher)
- npm (version 6.x or higher)
- MongoDB (version 4.x or higher)

## Deployment

> TODO: Write some better installation instructions

To deploy StaffEase to a production environment, follow the instructions provided by your preferred hosting platform, such as Heroku or AWS.

## Built With

- React - Front-end library
- Node.js - Back-end runtime environment
- Express.js - Back-end web application framework
- MongoDB - Database
- Mongoose - Object Data Modeling (ODM) library
- GraphQL - API query language

## Contributing

Please read CONTRIBUTING.md for details on our code of conduct and the process for submitting pull requests to the project.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments

> TODO: replaced Styled-components with Tailwind

- Styled-components for CSS-in-JS styling
- jsonwebtoken for authentication
- apollo-server-express for GraphQL integration

## Developed by

> TODO: Add links to developer's github profiles.

- Amish Sharma
- Jason Charney
- Joshua Norris
- Tony Mai

Deployment notes from Ellie off Linkedin
Darn it, it looks like Manav's instructions on Slack have been deleted, but I know we have a Procfile (https://github.com/luksvrd/Rally/blob/main/Procfile) in the root and this tutorial may be helpful for deploying the server side to Heroku (https://medium.com/karolis-stulgys/deploy-client-and-server-code-to-heroku-from-a-single-git-repo-44c5b65da10a)

For Netlify, I believe we had to change the base directory to /client or client, but I don't remember exactly. I can ask Lukas for some screenshots of this if it gives you trouble.

Here's the additional things we added: in main.jsx, we added the Heroku server URL
Comment image, no alternative text available

(Img of code in main jsx)

Then in the public folder under client, we added a file called \_redirects. This helps with client-side routing on Netlify (https://dev.to/chrisotto/netlify-client-side-routing-2iff)
Comment image, no alternative text available
