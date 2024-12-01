
# Smart Inventory and Order Management System (SIOMS)

## **Overview**
The **Smart Inventory and Order Management System (SIOMS)** project is designed to enable businesses to efficiently manage inventory, handle orders, and track deliveries. It incorporates various user roles, including Admin, Supplier, and Customer, to ensure seamless operations across multiple functionalities. The system is structured using the MVC framework and follows GRASP principles to maintain low coupling and high cohesion.

---

## **Team Members**
- **Amna Jamil** (ID: 44937) - amnajamil@gmail.com
- **Maryam Safdar** (ID: 46481) - maryamsafdar@gmail.com  
- **Sabahat Qadeer** (ID: 47235) - sabahatqadeer@gmail.com    
- **Nimra Gul** (ID: 47054) - nimragul@gmail.com  

---

## **Documentation Details**
This repository contains all the artifacts and documentation required for the development and understanding of the SIOMS project. Below are the detailed descriptions of the contents included:

### **Artifact 1: Use Case Diagram**
- **Use Case Diagram**: Visual representation of system functionalities.  
- **Actors**:
  - **Admin**: Manages system configurations and user roles.  
  - **Supplier**: Handles inventory management and order fulfillment.  
  - **Customer**: Places orders and tracks delivery status.  
- **Key Use Cases**:  
  1. Login: Required for all actors to access functionalities.  
  2. Manage Users (Admin): Add/Delete users such as Suppliers and Customers.  
  3. Inventory Management: Add, Edit, Remove products, and Track stock levels.  
  4. Order Management: Place Orders, Update Order Status, and View Order History.  
  5. Reports: Generate inventory and sales analytics.

---

### **Artifact 2: Fully Dressed Format of Use Cases**
- **Detailed Use Cases**:
  - **UC-01**: User Authentication and Role-Based Access Control.  
  - **UC-02**: Inventory Management by Suppliers.  
  - **UC-03**: Order Placement and Tracking.

---

### **Artifact 3: Domain Modeling**
- **Key Components**: Users, roles, products, orders, and reports.  
- **Domain Model Diagram**: Represents entities and their relationships.  
- **Main Entities**:
  - **Users**: Central table managing roles (Admin, Supplier, Customer).  
  - **Products**: Includes attributes like name, stock quantity, and price.  
  - **Orders**: Tracks order details, including status and total amount.  

---

### **Artifact 4: Class Diagram**
- **Key Classes**:
  - **User**: Handles login, logout, and profile management.  
  - **Product**: Tracks product details like stock quantity and price.  
  - **Order**: Links customers, products, and order statuses.  
  - **Admin**: Manages users and generates reports.

---

### **Artifact 5: Activity Diagram**
- **Workflows**:
  - **Admin**: Manages users, oversees orders, and generates reports.  
  - **Supplier**: Updates inventory and restocks products.  
  - **Customer**: Searches products, places orders, and tracks delivery.  

---

### **Artifact 6: Sequence Diagram**
- **Key Scenarios**:
  - Admin requests product updates.  
  - Supplier updates inventory and provides listings.  
  - Customer browses products, places orders, and tracks order status.

---

### **Artifact 7: State Transition Diagram**
- **System States**:
  - Login and authentication for role-based access.  
  - Order transitions through statuses (Placed → Processed → Shipped → Delivered).  
  - Inventory updates as products are added, edited, or removed.

---

### **Artifact 8: MVC Framework**
- **Application in SIOMS**:
  - **Model**: Handles business logic and data (e.g., User, Product, Order classes).  
  - **View**: Manages user interfaces like LoginView and InventoryView.  
  - **Controller**: Coordinates user inputs and system updates (e.g., LoginController, InventoryController).

---

### **Artifact 9: GRASP Pattern**
- **Principles Applied**:
  - **Creator**: Handles object creation, such as OrderManager for Orders.  
  - **Information Expert**: Assigns responsibilities to classes that manage relevant data (e.g., Product and Inventory).  
  - **Low Coupling**: Reduces dependencies between components for better maintainability.  
  - **Controller**: Defines the flow of operations and user interactions.

---

## **References**
Comprehensive references are provided for all artifacts and design principles to aid in further research and understanding. These include use case diagrams, domain and class modeling, activity and sequence diagrams, MVC framework implementation, and GRASP patterns.  

---

