# Finals-Lab-Task-3
- This portfolio is about learning MySQL by creating and managing a product database. It includes simple tasks like making a table, adding rules, inserting correct data, and changing a field. The goal is to understand how to build and organize a database using basic SQL.

# Step by Step Process:
1. **Create the Table**  
   - Make a table named `products`.  
   - Add three fields:  
     - `id` (auto-increment and primary key)  
     - `product_name` (text up to 100 characters, cannot be empty)  
     - `price` (decimal number)

2. **Add a Rule**  
   - Add a `CHECK` constraint to make sure the `price` is more than 0.

3. **Insert Valid Products**  
   - Only add products with a positive price:
     - Laptop – 999.99  
     - Smartphone – 599.99  
     - Tablet – 299.99  
     - Keyboard – 19.99  
     - Mouse – 14.99  
     - Desk Lamp – 24.99  
     - Speakers – 9.99  
   - Skip items with negative prices.

4. **Update the Table**  
   - Change the `product_name` field to allow up to 120 characters.

# Screenshots
## Query Statements
### 1. Task 1
- ![Image](https://github.com/user-attachments/assets/a74d8293-47c5-4699-aa4d-6ef429b1ed3f)
### 2. Task 2
- ![Image](https://github.com/user-attachments/assets/a87d5907-9db1-460a-b23b-d118e860340f)
### 3. Task 3
- ![Image](https://github.com/user-attachments/assets/6c4da79d-d849-47ad-8fc4-897c0cd81174)
### 4. Task 4
- ![Image](https://github.com/user-attachments/assets/55206384-6b19-4fd5-a520-d1513baccb5f)

# Table Structure
- ![Image](https://github.com/user-attachments/assets/8cd141f7-1c83-439c-8da2-e7ad587b562f)
- ![Image](https://github.com/user-attachments/assets/a843ccfc-5112-4f64-b091-e1d84a3d89d1)

# ER Diagram
- ![Image](https://github.com/user-attachments/assets/ac377255-d962-4ec8-ae05-a7c3f3866377)

