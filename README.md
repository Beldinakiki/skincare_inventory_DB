# 🧴 Skincare Products Inventory Management System 

## ✨ Project Overview

A comprehensive database system designed to manage inventory for skincare products, brands, suppliers, and purchase orders with ease and efficiency!

## 🌟 Features

- 📋 **Product Categorization**: Organize products into logical categories
- 🏭 **Brand Management**: Track product brands and their origin countries
- 📦 **Inventory Tracking**: Monitor product quantities across multiple locations
- 🔄 **Stock Levels**: Set reorder levels to prevent stockouts
- 🛒 **Purchase Orders**: Create and track orders from multiple suppliers
- 📊 **Location Management**: Organize inventory across warehouses, stores, and more

## 🛠️ Database Structure

The system includes 8 interconnected tables:
- Categories
- Brands
- Products
- Locations
- Inventory
- Suppliers
- Purchase Orders
- Purchase Order Items

## 🚀 Setup Instructions

### Prerequisites
- MySQL Server 5.7+ or MariaDB 10.3+
- MySQL Workbench (recommended for easy import)

### Option 1: Using MySQL Command Line 💻

1. Open your terminal or command prompt
2. Login to MySQL:
   ```bash
   mysql -u your_username -p
   ```
3. Copy and paste the entire SQL script.

### Option 2: Using MySQL Workbench 🖥️

1. Open MySQL Workbench
2. Connect to your MySQL server
3. Create a new SQL tab for executing queries (File > New Query Tab)
4. Copy and paste the entire SQL script
5. Execute the script by clicking the ⚡ lightning icon or pressing Ctrl+Shift+Enter

### Option 3: Import from SQL File 📁

1. Save the SQL script to a file.
2. In MySQL Workbench, go to Server > Data Import
3. Choose "Import from Self-Contained File" and select your file
4. Click "Start Import"

## 🎉 Getting Started After Setup

Once the database is set up, you can:

1. Add sample categories and brands
2. Create product entries
3. Set up inventory locations
4. Add suppliers
5. Create purchase orders

Happy inventory managing! ✨
