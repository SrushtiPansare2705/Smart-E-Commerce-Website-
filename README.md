# Smart E-Commerce Website

## Project Overview

The **Smart E-Commerce Website** is a full-stack Java-based application designed to manage products and user interactions efficiently. It allows admins to manage products and customers to browse and interact with products securely.

---

## Technologies Used

* **Backend:** Java, Spring Boot, Hibernate (JPA)
* **Frontend:** Thymeleaf, HTML, CSS, JavaScript
* **Database:** MySQL
* **Build Tool:** Maven

---

## Features

* **Product Management System:** Add, update, delete products
* **Secure CRUD Operations:** Proper validation and structured exception handling
* **Role-Based Authentication:** Differentiate admin and customer access
* **User-Friendly Interface:** Smooth product browsing and interaction
* **Database Integration:** Persistent storage using MySQL

---

## Project Structure

```
smart-ecommerce/
├── src/
│   ├── main/
│   │   ├── java/                # Java source code
│   │   ├── resources/           # Application properties, templates
│   │   └── webapp/              # Thymeleaf templates, static files (CSS, JS)
├── pom.xml                      # Maven configuration
└── README.md                    # Project documentation
```

---

## Setup & Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/smart-ecommerce.git
cd smart-ecommerce
```

2. **Configure Database**

   * Install MySQL and create a database named `smart_ecommerce_db`.
   * Update `application.properties` with your MySQL username and password.

3. **Build and Run the Application**

```bash
mvn clean install
mvn spring-boot:run
```

4. **Access the Application**
   Open a browser and go to `http://localhost:8080`

---

## Usage

* **Admin:** Can add, update, delete products and manage the catalog.
* **Customer:** Can view products, browse categories, and interact with the website.

---

## Future Enhancements

* Implement shopping cart functionality
* Add order management and payment gateway
* Integrate product search and filtering

---

## Author

**Srushti Pansare**

* Email: [srushtipansare859@gmail.com]
* GitHub: [https://github.com/SrushtiPansare2705]

