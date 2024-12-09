<!DOCTYPE html>
<html>
<head>
    <title>README - MovieLand</title>
</head>
<body>
    <h1>🎥 MovieLand</h1>
    <p>
        MovieLand is a simple and responsive movie search app built using <strong>React.js</strong> and the <strong>OMDb API</strong>. 
        It allows users to search for movies, view their details, and explore random movie suggestions when the app loads.
    </p>

    <h2>🚀 Features</h2>
    <ul>
        <li>🔍 <strong>Search Movies</strong>: Search for movies by title using the OMDb API.</li>
        <li>🎲 <strong>Random Suggestions</strong>: Displays random movies on the app load.</li>
        <li>🖼️ <strong>Responsive UI</strong>: Optimized for both desktop and mobile devices.</li>
        <li>❌ <strong>Error Handling</strong>: Gracefully handles cases when movies are not found.</li>
    </ul>

    <h2>📸 Screenshots</h2>
    <h3>Home Page</h3>
    <img src="https://via.placeholder.com/800x400?text=Screenshot+Placeholder" alt="MovieLand Homepage">
    <h3>Search Results</h3>
    <img src="https://via.placeholder.com/800x400?text=Screenshot+Placeholder" alt="MovieLand Search">

    <h2>🛠️ Tech Stack</h2>
    <ul>
        <li><strong>Frontend</strong>: React.js, CSS</li>
        <li><strong>API</strong>: <a href="https://www.omdbapi.com/" target="_blank">OMDb API</a></li>
        <li><strong>Hosting</strong>: Netlify</li>
    </ul>

    <h2>🔧 Installation and Setup</h2>
    <p>Follow these steps to set up the project locally:</p>
    <ol>
        <li><strong>Clone the Repository</strong>:
            <pre>
git clone https://github.com/your-username/MovieLand.git
cd MovieLand
            </pre>
        </li>
        <li><strong>Install Dependencies</strong>:<br>
            Make sure you have Node.js installed, then run:
            <pre>
npm install
            </pre>
        </li>
        <li><strong>Set Up the OMDb API Key</strong>:<br>
            - Sign up for an API key at <a href="https://www.omdbapi.com/apikey.aspx" target="_blank">OMDb API</a>.<br>
            - Create a <code>.env</code> file in the project root and add:
            <pre>
REACT_APP_OMDB_API_KEY=your_api_key
            </pre>
        </li>
        <li><strong>Run the App Locally</strong>:
            <pre>
npm start
            </pre>
            The app will run on <code>http://localhost:3000</code>.
        </li>
        <li><strong>Build for Production</strong>:
            <pre>
npm run build
            </pre>
        </li>
    </ol>

    <h2>🌐 Deployment</h2>
    <ol>
        <li><strong>Generate the Build Folder</strong>:
            <pre>
npm run build
            </pre>
        </li>
        <li><strong>Upload to Netlify</strong>:
            <ul>
                <li>Drag and drop the <code>build</code> folder to the Netlify dashboard.</li>
                <li>Alternatively, use the Netlify CLI:
                    <pre>
netlify deploy
                    </pre>
                </li>
            </ul>
        </li>
    </ol>

    <h2>📂 Folder Structure</h2>
    <pre>
MovieLand/
├── public/         # Static assets (index.html, favicon, etc.)
├── src/
│   ├── components/ # Reusable React components (e.g., MovieCard)
│   ├── App.css     # App styles
│   ├── App.js      # Main application logic
│   └── index.js    # React DOM rendering
├── .gitignore      # Git ignore file
├── package.json    # Project metadata and dependencies
├── README.md       # Project documentation
    </pre>

    <h2>📝 API Reference</h2>
    <ul>
        <li><strong>Base URL</strong>: <code>https://www.omdbapi.com/</code></li>
        <li><strong>Endpoints</strong>:
            <ul>
                <li><code>GET /?apikey=[YOUR_API_KEY]&s=[TITLE]</code>: Search movies by title.</li>
                <li><code>GET /?apikey=[YOUR_API_KEY]&i=[ID]</code>: Fetch detailed movie information by ID.</li>
            </ul>
        </li>
    </ul>

    <h2>🎯 Future Enhancements</h2>
    <ul>
        <li>✨ Add movie details page for more in-depth information.</li>
        <li>✨ Implement sorting and filtering for search results.</li>
        <li>✨ Add user authentication for personalized watchlists.</li>
    </ul>


</body>
</html>
