<h1>Food Delivery Application</h1>

<h2>Project Description</h2>
<p>This is a Spring Boot-based food delivery application that allows users to order food, update their orders, and manage their accounts. The application includes an authentication system to ensure that only authorized customers can access order-related services. The app leverages modern technologies like Spring MVC, Spring Data JPA, and Swagger for API documentation, making it robust and easy to interact with.</p>

<h2>Features</h2>
<ul>
    <li>User authentication and authorization.</li>
    <li>Place an order for food from a catalog.</li>
    <li>Update existing orders.</li>
    <li>Validation of user inputs using Validation API.</li>
    <li>Detailed API documentation via Swagger.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
    <li><strong>Spring MVC</strong>: For managing the web layer.</li>
    <li><strong>Spring Boot</strong>: For rapid application development.</li>
    <li><strong>Spring Data JPA</strong>: For managing database interactions.</li>
    <li><strong>Swagger</strong>: For automatic generation of API documentation.</li>
    <li><strong>Validation API</strong>: To validate user input.</li>
</ul>

<h2>Installation and Setup</h2>
<p>To run this project locally, follow these steps:</p>
<ol>
    <li>Clone the repository:
        <pre><code>git clone git@github.com:BharathChavala1/Food_Devlivery_Project.git</code></pre>
    </li>
    <li>Navigate to the project directory:
        <pre><code>cd food-delivery-app</code></pre>
    </li>
    <li>Build the project using Maven:
        <pre><code>mvn clean install</code></pre>
    </li>
    <li>Run the application:
        <pre><code>mvn spring-boot:run</code></pre>
    </li>
</ol>
<p>The application will be available at <code>http://localhost:8008</code>.</p>

<h2>Usage</h2>
<ol>
    <li><strong>Authentication</strong>: 
        <ul>
            <li>Register a new user or log in with existing credentials.</li>
            <li>After authentication, a token will be provided to access protected endpoints.</li>
        </ul>
    </li>
    <li><strong>Placing an Order</strong>: 
        <ul>
            <li>Browse available food items and add them to your cart.</li>
            <li>Submit the order once all items have been added.</li>
        </ul>
    </li>
    <li><strong>Updating an Order</strong>: 
        <ul>
            <li>Update the order by adding/removing items from the order list.</li>
        </ul>
    </li>
    <li><strong>Swagger Documentation</strong>: 
        <ul>
            <li>Access the API documentation at <code>http://localhost:8008/swagger-ui.html</code> for detailed API endpoints and usage.</li>
        </ul>
    </li>
</ol>

<h2>API Endpoints</h2>
<ul>
    <li><strong>POST /auth/login</strong>: User login</li>
    <li><strong>POST /orders</strong>: Create a new order</li>
    <li><strong>PUT /orders/{id}</strong>: Update an existing order</li>
    <li><strong>GET /orders</strong>: List all orders</li>
</ul>
