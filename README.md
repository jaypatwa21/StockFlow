# StockFlow
A lightweight Odoo-inspired inventory system for managing stock, warehouses, and product movements.

📖 Project Description:
StockFlow is a lightweight inventory and warehouse management system inspired by Odoo. 
It helps businesses manage products, track stock levels, handle incoming and outgoing inventory, 
and maintain a complete history of stock movements.

The system provides a simple dashboard where users can monitor inventory operations such as 
receipts (incoming stock) and deliveries (outgoing stock). It also supports warehouse and 
location management to organize products efficiently.

🎯 Problem Statement:
Many small businesses struggle to manage inventory efficiently. 
Manual tracking leads to stock mismatches, lost products, and inefficient operations.

Existing ERP systems like Odoo are powerful but complex for small teams or quick setups.

🏗 System Architecture:
Frontend
React + TailwindCSS

Backend
Node.js + Express.js

Database
SQLite

ORM
Prisma

📊 System Workflow:
Login
   ↓
Dashboard
   ↓
Create Products
   ↓
Create Warehouse
   ↓
Create Locations
   ↓
Add Receipt (Incoming Stock)
   ↓
Stock Increased
   ↓
Create Delivery (Outgoing Stock)
   ↓
Stock Reduced
   ↓
Movement Stored in History
