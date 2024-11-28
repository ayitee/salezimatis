# Salezi - API Backend Project
 
## Overview
 
Salezi is a backend API project designed to manage stocks and sales for FNAC's partner sellers. Built using Strapi and SQLite, it ensures secure, efficient, and role-based management of product inventories and transactions. This Minimum Viable Product (MVP) focuses solely on back-office functionality.
 
---
 
## Features
 
- **Role-Based Access Control:**
 
  - **Super Admin:** Full access to all application features.
  - **FNAC Manager:** Can view and edit all data, validate seller transactions, and access the Admin Panel.
  - **Seller:** Can manage their own products, request new transactions, and view other sellers' items without editing them.
 
- **Dynamic Inventory Management:**
 
  - Sellers can add or sell products while maintaining a positive stock balance.
 
- **Customizable Data Structures:**
 
  - Anticipates the addition of new product types beyond books, CDs, and electronics.
 
- **Strapi Admin Panel:**
 
  - Super Admin and FNAC Manager roles can access the panel for management.
 
- **Database:** SQLite integration for efficient and lightweight data management.
 
- **API Testing:** Postman collection provided for testing API endpoints.
 
---
 
## Installation
 
### Prerequisites
 
- Node.js installed on your system.
- A GitHub account to access the project repository.
 
### Steps
 
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd salezi-backend
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the Strapi development server:
   ```bash
   npm run develop
   ```
5. Access the Strapi Admin Panel at:
   ```
   http://localhost:1337/admin
   ```
 
---
 
## Database
 
- **Type:** SQLite (default Strapi database for development).
- **File Location:** `./data/database.sqlite` within the project directory.
 
---
 
## API Usage
 
### Roles and Permissions
 
- Ensure roles and permissions are set up in the Strapi Admin Panel.
- Configure Seller-specific permissions to restrict access to other sellers' data.
 
### Postman Collection
 
- Import the provided Postman collection to test API endpoints.
- The collection includes tests for all relevant routes, focusing on Seller functionality.
 
### API Routes
 
- **Products:** Manage inventory, create, edit, or delete items.
- **Transactions:** Handle sales and requests for new transactions.
- **Dashboard:** View summarized stock and sales data (if implemented).
 
---
 
### What the delivery includes :
 
- A fully functional Strapi backend application with an SQLite database.
- A comprehensive README file for launching and using the API.
- Postman collection in JSON format for API testing.
 
---
 
 
# salezimatis
### SALEZI
 
john doe's http://localhost:1337/admin/auth/register?registrationToken=808c56966f49e5a6b34c6fb94269612d1739a392
jane doe's http://localhost:1337/admin/auth/register?registrationToken=f4a232cd71f85440ef81109426e2017c044ce639


role : seller : id = mars@seller.com      mdp : teoteo
       admin  : id = mars@admin.com       mdp : teoteo
