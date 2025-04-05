# My.Backend.Development.Portfolio
Welcome to my backend development project showcase!  
This repository highlights my progress in mastering backend technologies such as Node Packages (with Express.js), Embedded Javascript, Axios, APIs (Postman), API Authentication, and their RESTful practices in creating APIs.

Also, I am currently mastering SQL, PostgreSQL, & React - I will update the portfolio with these soon!

---

### 1. Band Name Generator Project
"My first dynamic web app using Express and EJS templates"

![Band Name Generator Website Screenshot](./assets/project%20previews/band-name-generator.gif)

**Key Concepts:**  
Set up a Node server using Express, and handled routing with .get() and .post() methods.

Used body-parser to parse form data from the frontend (req.body).

Used express.static() to serve static files like CSS, making the frontend styled and complete.

Rendered dynamic content on the frontend using EJS (res.render("index.ejs", {...})).

Passed variables (like generatedName) from the server to the EJS template.

Partial Templates: Learned to modularize frontend code using partials for header and footer to maintain clean and reusable layout.

Dynamic Data: Injected real-time data like the current year into the footer dynamically using JavaScript (learned new Date().getFullYear()). 

📁 [View Code](./Band%20Name%20Generator%20Project/)

---

### 2. Handling JSON-formatted data with Taco Recipe Website  
An interactive recipe website powered by structured JSON data and form-based routing.

![Taco Town Website](./assets/project%20previews/taco-town-website.gif)

**Key Concepts:**  
Loaded a large JSON string representing taco recipes and parsed it using JSON.parse() to access nested objects and arrays. Practised navigating deeply nested structures (e.g., ingredients → toppings → ingredients[]).

Handled conditional logic inside a POST route (/recipe) to respond with the correct taco object based on the user’s selection.

Passed full JavaScript objects to the EJS view (res.render("index.ejs", { clicked: recipeObj })) and learned to display specific properties in the frontend template.

Processed user-submitted form data via req.body and body-parser middleware to trigger dynamic content updates.

Used EJS to render structured recipe data like name, ingredients, preparation method, and toppings directly into HTML.

📁 [View Code](./Taco%20Recipe%20Website/)

---

### 3. Secrets API Project with Dynamic Frontend
Fetching anonymous secrets from a third-party API and displaying them live with user info.

![Secrets API Website](./assets/project%20previews/secrets-api.gif)

**Key Concepts:**  
External API Integration with Axios: Used axios.get() to asynchronously fetch data from a third-party API (https://secrets-api.appbrewery.com/random).

Using Async/Await in Routes: Leveraged async/await inside the Express GET route to ensure the response from the API was fully received before rendering the page.

Passed API response data (username + secret) into the EJS template for real-time content rendering.

Built a user-facing interface that updates every time the page is refreshed.

Integrated styling and animation effects via CS and media files from the /public folder for a modern, appealing UI.

📁 [View Code](./Secrets%20Project/)

---


### 4. Hitting API endpoints with Axios to create a Random Activity Generator Website

![Random Activity Generator Website](./assets/project%20previews/random-activity-generator.gif)

Dynamic API Querying with Axios

Integrated with the Bored API using both the /random and /filter endpoints.

Used GET requests with query parameters to generate user-specific results based on form inputs (type, participants).

Processed POST requests using form data from dropdown selections.

If no activities match the selected criteria, the app dynamically informs the user — "No activities that match your criteria."

📁 [View Code](./Random%20Activity%20Generator/)

---

### 5. Blog API Project (Custom REST API)
Designed my own RESTful API and consumed it with a blog-style frontend interface.

![Blog API Project Website](./assets/project%20previews/blog-api-project.gif)

**Key Concepts:**  
Built a RESTful API from scratch using Express.js.

Managed an in-memory list of blog posts (simulating a backend database).

Implemented full CRUD functionality:

GET /posts – Fetch all blog posts.

GET /posts/:id – Fetch a specific blog post by ID.

POST /posts – Add a new blog post.

PATCH /posts/:id – Update selected fields of an existing post.

DELETE /posts/:id – Delete a blog post.

Used middleware like body-parser to handle JSON and URL-encoded payloads.

📁 [View Code](./Blog%20API%20Project/)

---

