# Retailer Database Management System

This project is a comprehensive **Retailer Database Management System (DBMS)** developed using **Informatica PowerCenter** to integrate, manage, and analyze retail data. It facilitates the centralized storage of customer, vendor, order, and product information, ensuring data consistency and enabling business insights.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Database Structure](#database-structure)
- [Data Transformations](#data-transformations)
- [Business Insights](#business-insights)
- [Contributors](#contributors)

## Project Overview

The Retailer DBMS centralizes and manages all critical business data such as products, customers, vendors, and sales transactions. This system supports retailers by providing insights into sales trends, customer behavior, and inventory performance, empowering them to make informed business decisions.

The project leverages **Informatica PowerCenter** to automate the integration of data from various sources, transforming it into actionable insights.

## Features

- **Data Integration**: Integrates customer, vendor, product, and sales data into a unified system.
- **Data Transformation**: Data is processed and transformed using various operations like aggregation, filtering, and ranking.
- **Business Intelligence**: Generates insights from the data to evaluate business performance.
- **Automation**: Reduces manual effort in data management by automating the integration and transformation processes.
- **Real-time Analysis**: Provides updated insights into operations such as sales, customer segments, and logistics.

## Technologies Used

- **Informatica PowerCenter**: For data integration and transformation.
- **SQL**: For querying and managing database operations.
- **Database Management**: Structured storage and management of data related to customers, vendors, orders, products, and payments.

## Database Structure

### Key Entities:
1. **Customers**: Stores customer details (CNUMBER, Name, Address, Phone, etc.).
2. **Vendors**: Manages vendor details (VENDORID, Name, Office Info, etc.).
3. **Orders**: Tracks customer orders and their status.
4. **Products**: Contains product information, including pricing and categories.
5. **Payments**: Records payments related to customer orders.

### Relationships:
- Orders are linked to Customers.
- Products are linked to Vendors.
- Payments are linked to Orders.

## Data Transformations

Key transformations performed using Informatica PowerCenter:
- **Profit Analysis**: Calculating the profit of each product.
- **Customer Segmentation**: Grouping customers by geographical regions.
- **Branch Performance**: Evaluating retail branches based on sales performance.
- **Logistics Efficiency**: Identifying orders delivered on the same day.
- **Product Sales Distribution**: Understanding sales distribution across various product categories.

## Business Insights

The project provides insights into various areas of the retail business:
- **Sales Trends**: Identify the most profitable products and vendors.
- **Customer Behavior**: Analyze customer purchasing patterns based on location and sales.
- **Inventory Management**: Monitor product sales to optimize inventory.
- **Logistics**: Improve delivery and shipping efficiency by tracking order status.


## License

This project is for educational purposes as part of the Bachelor of Engineering course in Computer Science and Engineering.
