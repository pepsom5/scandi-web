 Product Management Application

This repository contains a simple product management application built with HTML, JavaScript, and Tailwind CSS. The application consists of two main pages:

- Product List Page
- Product Add Page

## Features

### Product List Page

- Displays a list of products with details such as SKU, Name, Price, and product-specific attributes.
- Allows for mass deletion of products using checkboxes.
- Navigation to the Product Add page via an "ADD" button.

### Product Add Page

- Provides a form (`#product_form`) for adding new products with fields for SKU (`#sku`), Name (`#name`), and Price (`#price`).
- Includes a product type switcher (`#productType`) with options for DVD, Book, and Furniture, which dynamically displays the corresponding attribute fields.
- Validates input data and displays notifications for missing or invalid data without page reloads.
- "Save" button to save new products and return to the Product List page.
- "Cancel" button to discard changes and return to the Product List page.
