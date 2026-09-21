# Online Beadwork Store “Flames of Darkness”

## 📝 Project Overview
**Flames of Darkness** is an e-commerce platform dedicated to showcasing and selling unique, handcrafted Ukrainian beadwork products. The platform expands the artisan's market reach, automates sales workflows, and promotes authentic handmade crafts internationally.

### 🎯 Topic & Scope
* **Tech Stack Focus:** HTML document tags, attributes, and structural semantic markup.
* **Version Control:** GIT & GitHub workflow, working with repositories.
* **Core Application:** Complete logic description of a personal web application.

---

## 💡 System Analysis

### Relevance of the Topic
With the rapid growth of e-commerce, digital solutions for handmade and artisan sectors are highly sought after. Beadwork jewelry is increasingly popular among youth and collectors looking for unique pieces that emphasize individuality. 

* **Object of the Work:** An e-commerce information system for selling beadwork products.
* **Subject of the Work:** Software architecture managing sales, inventory, orders, and customer relationships.

### Purpose & Objectives
The primary goal is to simplify, digitalize, and accelerate the process of browsing, selecting, and ordering custom beadwork jewelry.

* **Audience:** Analyze target market needs and demands.
* **UI/UX:** Develop an intuitive, visually stunning interface.
* **Catalog:** Implement a dynamic product display with images, specs, and pricing.
* **Sales Pipeline:** Create an integrated shopping cart, checkout system, and secure order processing.
* **Admin Ecosystem:** Build an administrative panel for seamless product and order management.

---

## ⚙️ Business Logic & Operations
* **Authentication:** Users must register or log in to complete a purchase or place a customized pre-order.
* **Order Expiration:** Cart checkouts and unpaid orders expire automatically within **24 hours** of placement.
* **Custom Logistics:** Customers can manually schedule the date/time of delivery and attach personalized production notes.
* **Loyalty Program:** Automated discount engines applied for regular customers alongside active seasonal promo codes.

---

## 🗺️ Main Functionality & Architecture

### 1. Home Page
Serves as the main landing node containing three core semantic blocks:
* **Header:** Global search bar, dynamic category routing, and user profile management (Login/Registration).
* **Main Section:** 
  * *Categories block* for intuitive store assortment exploration.
  * *Product gallery carousel* to highlight trending designs.
  * *Brand History section* focused on the shop's origin and individual artisans.
* **Footer:** Operational contacts, corporate location, policy details, and social channels.

### 2. Categories Page
Triggers once a specific type of product is selected:
* **Left Sidebar:** Search criteria, dynamic filtering (price, color, material type).
* **Right Workspace:** Product display grid showcasing names, primary images, and prices.

### 3. Product Page
Displays deep-dive item characteristics:
* Title, HD item gallery, description tab, technical dimensions, exact pricing, and available delivery lines.

### 4. User Dashboard
Personalized area separated into twin blocks:
* **Personal Data:** Profile information editing (Name, phone, email, avatar).
* **Order History:** Tracking system for active, pending, and past fulfillments.

---

## 📋 System Requirements

### Functional Requirements
1. Guest users can access and browse all catalog items, categories, and brand details without strict login.
2. System includes authorization modules separating Guests, Users, and Administrators.
3. Users can dynamically add, remove, and update quantities within the shopping cart.
4. Checkout processes require explicit payment integration selection and final user confirmation.
5. Administrators maintain absolute control over product metrics, active stocks, catalog statuses, and promotion panels.

### Non-Functional Requirements
* **Scalability:** Built to support at least **1,000 concurrent users** seamlessly.
* **Security:** Complete customer confidentiality via strict end-to-end data encryption and hashed user password storage.
* **Responsiveness:** Fluid grid interface tailored for standard Desktops, Tablets, and Mobile screens.

---

## 👥 Use Case Architecture

* **Administrator:** Manages internal stock availability, coordinates assortment variants, configures dynamic holiday campaigns, and monitors registered profiles.
* **User (Guest):** Explores landing resources, triggers catalog search inquiries, and relies on multi-layer filtering tools.
* **Registered User:** Keeps an individual account footprint, performs secure checkout flows, manages personal data, and contributes to product ratings/reviews.
