# Point-Of-Sale

A **Point of Sale (POS)** system represents the time and place where a retail transaction occurs. At the point of sale, the merchant calculates the total amount owed by the customer, presents the bill, and offers various payment options. Once the payment is made, a receipt can be issued either on paper or electronically.

The POS system may integrate several devices such as:
- **Barcode Scanners** to read product codes.
- **Weighing Scales** for bulk or produce items.
- **Cash Registers and Receipt Printers** for billing.
- **Touch Screens and Payment Terminals** for customer interaction and transaction finalization.

This repository contains the source files, database schemas, and supporting tools for building a modern, cross-database POS application using **MagicAppBuilder**.

---

## 📦 Available Database Files

The following database files are included for use and testing:

| File Name                       | Description                                                        |
|---------------------------------|--------------------------------------------------------------------|
| `point_of_sale.mwb`             | Original MySQL Workbench design file.                              |
| `point-of-sale.sql`             | SQL export from MySQL Workbench.                                   |
| `point-of-sale-mysql.sql`       | Exported using MagicAppBuilder with 1000 sample items (MySQL).     |
| `point-of-sale-postgresql.sql`  | Exported using MagicAppBuilder with 1000 sample items (PostgreSQL).|
| `point-of-sale-sqlite.sql`      | Exported using MagicAppBuilder with 1000 sample items (SQLite).    |
| `point-of-sale-sql-server.sql`  | Exported using MagicAppBuilder with 1000 sample items (SQL Server).|

Each SQL file is compatible with its respective database engine, and includes essential tables like `products`, `categories`, `transactions`, `users`, and more.

---

## 🧩 Source Code

The application source code was generated using **MagicAppBuilder** — a visual and code-first development tool that automates CRUD interfaces, REST APIs, and data model generation.

---

## 🛠 How to Use MagicAppBuilder

1. ### 📥 Download MagicAppBuilder
   - Visit [MagicAppBuilder on GitHub](https://github.com/planetbiru/magicappbuilder).
   - Download the latest release or clone the repository:
     ```bash
     git clone https://github.com/planetbiru/magicappbuilder.git
     ```

2. ### ⚙️ Install Requirements
   MagicAppBuilder is a PHP-based tool. You need:
   - PHP 8.0+
   - Composer
   - A web server (Apache, Nginx) or use PHP built-in server

   Install dependencies using:
   ```bash
   composer install

3. ### 🚀 Start the Application

   Run MagicAppBuilder locally
   Then visit `http://localhost/MagicAppBuilder/` in your browser.

4. ### 🧱 Build Your App

   * Import one of the provided database schemas (e.g., `point-of-sale-mysql.sql`) into your database engine.
   * Open MagicAppBuilder, go to **Entity Designer**.
   * Click `Import From Database`.
   * Review and adjust entities, validation, relationships, etc.
   * Click **Generate Code** to export the application structure.

---

## 💡 Features of This POS App (via MagicAppBuilder)

* Product and category management
* Inventory tracking
* Basic transaction processing
* Cross-database compatibility
* Ready-to-deploy PHP backend with REST API support
* Entity export to HTML/Markdown/Excel
* Validation rules and relationship definitions

---

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 🤝 Contribution

Feel free to fork this project, suggest improvements, or submit pull requests. Your feedback is welcome!

---

## 📧 Contact

For questions, contact the repository maintainer or open an issue in the repository.

