# **Catalogue Management Endpoints**

| **Actor**        | **Action**             | **Priority** | **HTTP Method** | **Endpoint**                           | **Description** |
|------------------|------------------------|--------------|-----------------|----------------------------------------|-----------------|
| **Engineers**    | Delete user account    | High         | DELETE          | /api/users/{userId}                    | Endpoint to allow users to request the deletion of their account and associated data. |
| **Engineers**    | Add Product            | High         | POST            | /api/product/                          | Endpoint to allow engineers to add new products (requires session token of engineer). |
| **Engineers**    | Update Product         | High         | PUT             | /api/product/{productId}               | Endpoint to allow engineers to update existing products. |
| **Engineers**    | Add Product Showcase   | High         | POST            | /api/product/{productId}/showcase      | Endpoint to allow engineers to add various product showcase images and teardown views. |
| **Engineers**    | Delete Product         | High         | DELETE          | /api/product/{productId}               | Endpoint to allow engineers to delete a product from the catalogue. |
| **Users**        | Validate Product       | High         | POST            | /api/product/{productId}/validate      | Endpoint to allow users to validate the product specifications added by engineers. |
| **Users**        | Replace Product Feature| High         | PUT             | /api/product/{productId}/replace       | Endpoint to allow users to replace or correct a feature of the product. |
| **Admin**        | Approve Product        | High         | POST            | /api/product/{productId}/approve       | Endpoint to allow admin to approve products that have been validated by users. |
| **Admin**        | View Approval Status   | Medium       | GET             | /api/product/{productId}/approval-status | Endpoint to view the approval status of products and details of pending approvals. |
| **Customers**    | View Products          | High         | GET             | /api/products                          | Endpoint to allow customers to view all products in the catalogue. |
| **Customers**    | Filter Products        | High         | GET             | /api/products/filter                   | Endpoint to filter products based on criteria such as screen size, weight, model number, price, ratings, etc. |
| **Customers**    | View Product Details   | High         | GET             | /api/product/{productId}               | Endpoint to view detailed information about a selected product. |
| **Customers**    | View Product Gallery   | Medium       | GET             | /api/product/{productId}/gallery       | Endpoint to view the product's outside showcase and teardown images/videos. |
| **Customers**    | View Product Reviews   | Medium       | GET             | /api/product/{productId}/reviews       | Endpoint to view customer reviews of the product. |
| **Customers**    | View Product FAQs      | Medium       | GET             | /api/product/{productId}/faqs          | Endpoint to view frequently asked questions related to the product. |
| **Customers**    | View Product Safety    | Medium       | GET             | /api/product/{productId}/safety        | Endpoint to view safety information and ratings of the product. |

---
