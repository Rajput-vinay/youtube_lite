YouTube Clone
This project is a clone of the popular video-sharing platform YouTube. It is built using modern front-end technologies, including React, Redux Toolkit, TailwindCSS, and other libraries.

Features
YouTube Clone: The project replicates the YouTube platform, including its UI design and core functionalities.
YouTube Video List: Displays a paginated list of YouTube videos fetched from the YouTube API with support for lazy loading.
YouTube Video Preview: Clicking on a video opens a preview window showing the video with its title, description, and view count.
Search Suggestions: Provides a dropdown of suggested search queries as the user types in the search bar.
Optimized Search Using Caching and Debouncing: Implements debouncing for search functionality and caching for faster results on repeated searches.
Optimized API Calls Using Debouncing: Uses debouncing to minimize API calls, enhancing performance during actions like scrolling.
Comments Section: Allows users to view and post comments on videos, with comments displayed in a threaded view.
Live Chat: Real-time chat functionality implemented with API polling, continuously updating the UI with new messages.
Installation
To run this project locally, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/your-username/youtube-clone.git
Navigate to the project directory:

bash
Copy code
cd youtube-clone
Install the dependencies:

bash
Copy code
npm install
Create a .env file in the root directory and add your YouTube API key:

plaintext
Copy code
GOOGLE_API_KEY=your-api-key-here
Start the development server:

bash
Copy code
npm start
Open your web browser and go to http://localhost:3000.

Usage
Once the development server is running, you can explore the various features of the YouTube clone:

Browse videos from the YouTube API.
Use the search bar to find specific videos with search suggestions.
View video details and comments.
Participate in live chat.
Technologies Used
React: A JavaScript library for building user interfaces.
Redux Toolkit: A toolset for efficient Redux development.
TailwindCSS: A utility-first CSS framework.
Moment: A library for parsing, validating, and formatting dates.
React Icons: A library of popular icons for React.
React Router DOM: A library for routing in React applications.
Contributing
If you'd like to contribute to this project, please fork the repository and create a pull request with your changes. Contributions are welcome!

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
Special thanks to all the developers who contributed to the libraries and tools used in this project.
