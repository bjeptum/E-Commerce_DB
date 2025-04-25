# E-Commerce_DB

## 🎯 Objective

The goal of this project is to design and implement a relational database system for an e-commerce platform. 
This challenge helped us (collaborators) to strengthen our understanding of database modeling, normalization, and collaborative development practices.

## 📈 ERD Diagram

The ERD that represents the structure of the database:

![image alt](https://github.com/bjeptum/E-Commerce_DB/blob/41f3ba7931adadd425bce521de1620562d63862c/Ecommerce%20Database.png)

## 🗂️ Database Tables

Here is the list of tables and their purpose within the e-commerce schema:

| Table Name           | Description |
|----------------------|-------------|
| `product_image`      | Stores product image URLs or file references. |
| `color`              | Manages color options for products. |
| `product_category`   | Classifies products (e.g., clothing, electronics). |
| `product`            | Stores base product info (name, brand, price). |
| `product_item`       | Specific purchasable items (variations of a product). |
| `brand`              | Brand metadata and details. |
| `product_variation`  | Associates products with variation options like size, color. |
| `size_category`      | Groups sizes (e.g., clothing sizes, shoe sizes). |
| `size_option`        | Specific sizes like S, M, L, 42, etc. |
| `product_attribute`  | Custom attributes such as material, weight. |
| `attribute_category` | Groups product attributes into categories. |
| `attribute_type`     | Data types of attributes (text, number, boolean, etc). |

## 🔄 Data Flow Summary

We designed the data flow by:
- Identifying user interactions like browsing, selecting product options, and viewing variations.
- Mapping how product data (images, colors, sizes, attributes) is related and stored.
- Ensuring normalization to avoid data duplication and maintain integrity.


## 👥 Team Members

- [Jeptum Brenda](https://github.com/bjeptum)
- [Mercy Ochieng](https://github.com/254punchlinez)
- [Amy Wanjala](https://github.com/wat-tanya)
