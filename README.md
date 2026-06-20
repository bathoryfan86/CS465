Module 8 Journal 

**Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).**

- Express server: routing, middleware, REST endpoints; renders JSON not HTML by default; handles auth, validation.

- Client SPA (HTML/CSS/JavaScript): React/Vue/vanilla JS manages state, routing in-browser, fetches data via AJAX/fetch.

**Why did the backend use a NoSQL MongoDB database?**

The backend used a NoSQL MongoDB database because of how easily it was to change the scaling and functionality of the app.  You would also horizontally change the scale pretty quickly because of the relation to the database.

**How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?**

JSON is a lightweight text format used for data exchange, whereas JavaScript is a fully functional programming language. JSON ties frontend and backend together by acting as a universal translator; when the frontend requests data, the backend queries the database and formats the results as a JSON string to update the webpage.

**Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.**

- In a full‑stack e‑commerce app, the original cart total function combined item pricing, discount logic, and validation in one monolithic block. This made it hard to test, extend, and maintain.

- In a multi‑page dashboard, repeated “user profile” sections were implemented in HTML/React templates for each page.

**Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.**

In a full stack application, API testing of endpoints for request and retrieval ensures that the frontend and backend communicate accurately and securely. Testing becomes difficult with added security layers, as it requires validating complex authentication and protecting against vulnerabilities without disrupting legitimate user flows.

**Reflections**

This course has helped me with building a website and understanding the various methods of testing. I have also had to grasph with what the stakeholders want and do certain tasks from their point of view. 
