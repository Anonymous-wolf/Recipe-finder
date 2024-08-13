<h1>Recipe Finder</h1>

<p><strong>Recipe Finder</strong> is a web application that allows users to search for recipes by keyword or ingredient. It fetches data from the Edamam API, displaying a list of matching recipes and providing detailed views with ingredients, calorie count, and instructions. The app integrates a Node.js backend with MongoDB for data persistence and uses a responsive frontend built with HTML, CSS, and JavaScript.</p>

<h2>Features</h2>
<ul>
    <li><strong>Search Recipes:</strong> Users can search for recipes using keywords or ingredients.</li>
    <li><strong>Recipe List:</strong> Displays a list of recipes matching the search criteria with at least five results.</li>
    <li><strong>Recipe Details:</strong> Detailed information about each recipe, including ingredients and calorie count.</li>
    <li><strong>MongoDB Integration:</strong> Stores user search queries and other relevant data.</li>
    <li><strong>Responsive Design:</strong> Adapts to different screen sizes for optimal viewing on any device.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
    <li><strong>Frontend:</strong> HTML, CSS, JavaScript</li>
    <li><strong>Backend:</strong> Node.js, Express</li>
    <li><strong>Database:</strong> MongoDB</li>
    <li><strong>API:</strong> Edamam API</li>
</ul>

<h2>Setup Instructions</h2>
<h3>Clone the Repository:</h3>
<pre><code>git clone https://github.com/yourusername/recipeFinder.git
cd recipefinder</code></pre>

<h3>Install Dependencies:</h3>
<pre><code>npm install</code></pre>

<h3>Configure Environment Variables:</h3>
<p>Create a <code>.env</code> file in the root directory and add your Edamam API credentials:</p>
<pre><code>APP_ID=your_app_id
APP_KEY=your_app_key
MONGODB_URI=your_mongodb_connection_string</code></pre>

<h3>Run the Application:</h3>
<pre><code>npm start</code></pre>

<p>Access the App:</p>
<p>Open your browser and navigate to <a href="http://localhost:4000">http://localhost:4000</a>.</p>

<h2>Deployment</h2>
<p>To deploy this application using Vercel:</p>

<h3>Install the Vercel CLI:</h3>
<pre><code>npm install -g vercel</code></pre>

<h3>Run the deployment command:</h3>
<pre><code>vercel</code></pre>

<p>Follow the prompts to deploy your application.</p>

<h2>Contributing</h2>
<p>Contributions are welcome! Feel free to open issues or submit pull requests.</p>

<h2>License</h2>
<p>This project is licensed under the MIT License. See the LICENSE file for more details.</p>
