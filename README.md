
# Northwind Traders - IEC Portfolio 1

## Authors
- Sidra Nasir
- Danish Younas Khan
- Ghulam Nabi

## Table of Contents
- [Project Overview](#project-overview)
- [Data Dictionary](#data-dictionary)
- [Sales Analysis](#sales-analysis)
- [Inventory Management](#inventory-management)
- [Product & Customer Analysis](#product--customer-analysis)
- [Freight Analysis](#freight-analysis)
- [Recommendations](#recommendations)

## Project Overview
This project is part of the IEC Portfolio 1 and aims to analyze various datasets from Northwind Traders to derive insights for improving business processes. The analysis includes sales trends, inventory management, customer purchasing behavior, and freight cost optimization.

## Data Dictionary
The project uses several tables from the Northwind Traders database, including:

- **Categories**[Portfolio 1 Final report.docx](https://github.com/user-attachments/files/16188559/Portfolio.1.Final.report.docx)

  - `CategoryID`: int - Unique identifier for each category.
  - `CategoryName`: text - Name of the category.
  - `Description`: text - Description of the category.
  - `Picture`: BLOB - Picture representing the category.

- **Customers**
  - `CustomerID`: text - Unique identifier for each customer.
  - `CompanyName`: text - Name of the customer company.
  - `ContactName`: text - Name of the contact person.
  - `ContactTitle`: text - Title of the contact person.
  - `Address`, `City`, `Region`, `PostalCode`, `Country`, `Phone`, `Fax`: text - Various contact details of the customer.

- **Employees**
  - `EmployeeID`: int - Unique identifier for each employee.
  - `LastName`, `FirstName`, `Title`, `TitleOfCourtesy`, `BirthDate`, `HireDate`, `Address`, `City`, `Region`, `PostalCode`, `Country`, `HomePhone`, `Extension`, `Photo`, `Notes`, `ReportsTo`, `PhotoPath`, `Salary`: various types - Detailed information about employees.

- **Orders**
  - `OrderID`: int - Unique identifier for each order.
  - `CustomerID`, `EmployeeID`, `OrderDate`, `RequiredDate`, `ShippedDate`, `ShipVia`, `Freight`, `ShipName`, `ShipAddress`, `ShipCity`, `ShipRegion`, `ShipPostalCode`, `ShipCountry`: various types - Detailed information about orders.

- **Order Details**, **Products**, **Suppliers**, **Shippers**, **Regions**, **Territories**: Similar detailed information about order details, products, suppliers, shippers, regions, and territories.

## Sales Analysis
### Monthly Sales Trends
- **Objective**: Identify total sales for each month over the past year.
- **Result**: Helps in understanding seasonal trends and planning inventory and promotions.

### Yearly Sales Growth
- **Objective**: Analyze total sales revenue growth year over year.
- **Result**: Understand the business's growth trajectory.

## Inventory Management
### Inventory Turnover Rate
- **Objective**: Calculate inventory turnover rate for each product over the past year.
- **Result**: Indicates how efficiently inventory is managed.

### Reorder Frequency
- **Objective**: Determine reorder frequency for each product.
- **Result**: Ensures adequate inventory management.

## Product & Customer Analysis
### Total Sales by Product and Customer
- **Objective**: Determine total sales of each product and identify corresponding customers.
- **Result**: Provides insights into consumer purchasing behavior.

### Category-wise Breakdown of Products and Sales
- **Objective**: Analyze total sales of products within each category.
- **Result**: Assesses category performance and identifies high-performing categories.

### Quantity-wise Breakdown
- **Objective**: Examine the breakdown of product quantities available.
- **Result**: Aids in inventory management decisions.

## Freight Analysis
### Shipping Details for Each Order
- **Objective**: Calculate average freight cost for each shipper over time.
- **Result**: Identifies trends and potential cost optimization strategies.

### Shipping Cost Summary by Company
- **Objective**: Analyze freight costs associated with different shipping companies.
- **Result**: Assesses cost-effectiveness of shippers.

### Monthly Average Freight Cost
- **Objective**: Analyze average freight cost per month for each shipping company.
- **Result**: Identifies trends in shipping expenses.

## Recommendations
Based on the analysis, the following recommendations are provided:
- **Peak Sales Periods**: Ensure sufficient inventory levels and plan targeted promotions.
- **Slow Sales Periods**: Implement special promotions or marketing efforts.
- **Inventory Management**: Adjust inventory levels based on demand patterns.
- **Sales Strategies**: Implement promotional strategies for slow-moving products.
- **Shipping Optimization**: Optimize shipping routes and negotiate better rates with carriers.

---