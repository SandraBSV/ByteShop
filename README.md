# "ByteShop" Tech Online Store

Report on practical works for the discipline **"Internet Technologies and Web Application Design"**.  
**Created by:** Aleksandra Butko, 2nd-year student, group IS-44.  
**Supervised by:** Svitlana Leonidivna Proskura, Senior Lecturer of the IST Department.  
**National Technical University of Ukraine "Igor Sikorsky Kyiv Polytechnic Institute"**  
**Faculty of Informatics and Computer Science | Department of Information Systems and Technologies**

---

## 📝 Project Overview
**"ByteShop"** is a modern e-commerce web application designed for selling digital devices and home appliances. The project covers the full development lifecycle: from business logic design and responsive layout implementation to creating a relational database, deploying a backend server, and integrating an authentication system with role-based access control.

---

## 💻 Tech Stack
* **Frontend:** HTML5 (semantic markup), CSS3 (responsive design, Flexbox, `@media` queries), JavaScript (server integration, animations, carousel slider).
* **Backend:** Node.js / Express (server-side runtime, REST API handling CRUD operations).
* **Database:** Relational DB (designed according to the ER model, implementing tables, relations, and PK/FK constraints; tested via sample SELECT queries).
* **Version Control:** Git & GitHub.

---

## ⚙️ Business Logic & System Architecture

### Features and Page Structure:
1. **Home Page (`index.html`):**
   * **Header:** Features the "BYTE SHOP" logo, a search field (`searchInput`), a responsive hamburger menu (optimized for screens under 900px), and quick navigation buttons ("Catalog", "Information", "Registration/Dashboard").
   * **Main Content:** Includes a promotional block (image carousel/slider showcasing active deals across 24 slots), a responsive product category grid (Smartphones, Tablets, Headphones, Laptops, etc.), and an informative "About the Store" background section.
   * **Footer:** Displays business contacts, store address (64/85 Petra Sahaidachnoho St.), an interactive map, and basic delivery parameters.
2. **Category Page (`phone.html`, etc.):**
   * **Left Block:** Dedicated search and filtration system (sorting by price, filtering by brands, colors, storage size, and stock availability built using `<fieldset>` and `<legend>` nodes).
   * **Right Block:** A fluid grid canvas (`all-products`) rendering standalone product cards containing item titles, prices, and clickable image routes.
3. **Product Page (`phoneP.html`):**
   * **Deep-Dive Workspace:** Displays individual item details, media galleries, price points, and interactive parameter toggles (color variants, memory capacities). Includes technical specs, delivery routes, payment frameworks (featuring Monobank's "Purchase in Installments" integration), and warranty policies.
4. **User Dashboard:**
   * Divided into two specific operational blocks: "Personal Data" (Full Name, phone number, email, profile picture) and "Orders" (comprehensive log and archive of historical checkouts).
5. **Authentication Workspace:**
   * Input forms for user registration and system login to provision dashboard spaces.

### Operational Business Rules:
* Once an order invoice is initialized, checkout payments must be settled within **24 hours**.
* Registered long-term buyers gain automatic access to a built-in loyalty program and active seasonal promotional codes via their account space.

---

## 📋 System Requirements

### Functional Requirements:
* Guests can freely explore the landing pages, navigate product categories, and inspect comprehensive technical data tabs.
* Standard users can register accounts, alter cart metrics, adjust shipping lines, select payment platforms, and verify checkouts.
* Administrators rely on a dedicated dashboard to safely modify product catalogs, update physical stock counts, and supervise active accounts.

### Non-Functional Requirements:
* **Performance:** Architected to handle a minimum threshold of **1,000 concurrent active users**.
* **Security:** Strict data privacy rules enforced via structural end-to-end encryption alongside strictly hashed account password records.
* **Responsiveness:** Interface scaling optimized across Desktop platforms and Mobile layouts driven by relative viewport sizing units and conditional media rules.

---

## 🛠️ Practical Works Breakdowns

* **Practical Work 1:** Subject area modeling, target scope validation, creation of the core Use Case architecture, and initial ER diagram outlining entities.
* **Practical Work 2:** Design and assembly of the responsive frontend components (`header`, `main`, `footer`, category flows, dynamic item filters) using semantic HTML5 and tailored CSS3 style sheets.
* **Practical Work 3:** Implementation of administrative views and logic managing conditional interface states based on active clearance (Guest / Registered User / Admin).
* **Practical Work 4:** Building core database structures (Buyer, Invoice, Row Item, Product, Warehouse, Stock Tracking) aligned with the target ER template. Enforcing table dependencies, index models, and cascade execution parameters (`ON DELETE/UPDATE`) alongside rigorous validation via advanced `SELECT` query scripts.
* **Practical Work 5:** Setting up the server environment running on Node.js. Structuring full database connectivity and building a standard REST API implementing a complete CRUD matrix (`GET/READ`, `POST/CREATE`, `PUT/UPDATE`, `DELETE`) to wire frontend components.
* **Practical Work 6:** Coding the system authentication layer, deploying the data schemas governing operational users and system access roles, and isolating secure API paths with fallback exception handling.
