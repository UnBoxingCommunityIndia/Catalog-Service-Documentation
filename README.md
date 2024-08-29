# **Requirement Specification for Catalogue Service**

---

**Actors:**
- Engineers
- Users
- Admin
- Customers

---

### **Functions of Each Actor:**

#### **1. Engineers**
**Responsibilities:**
- **Adding Product Specifications:**
  - Brand Name
  - Model Name
  - Catalog Name
  - Subcatalog Name
  - Model Variant Name
  - Product Reference Link
  - Product Dimensions

- **Adding Product Showcases:**
  - **Outside Showcase Views:**
    - Straight on
    - Top show
    - Bottom shot
    - High angle shot
    - Hero view
    - Low view
    - Other views
  - **Teardown Showcase:**
    - Includes all views and necessary teardown details.

**Note:**
- Engineers should ignore the following:
  - Time of Purchase (MM-YYYY)
  - Product Usage Pattern (selecting from a list of options)
  - Product Usage Behavior (selecting from a list of options)

---

#### **2. Users**
**Description:**
- Users are individuals who have used a product and can validate the information added by Engineers.

**Functions:**
- After the specifications, features, and details have been added for a product, the user has access to two options:
  1. **Validate:**
     - Upon clicking "Validate," the validation process is completed, and the changes are updated.
  2. **Replace:**
     - Upon clicking "Replace," the user is redirected to the product specification page, where they can correct the desired feature.

---

#### **3. Admin**
**Description:**
- The Admin oversees the entire catalogue process.

**Functions:**
- For each product, the Admin can:
  - See whether the product has been approved or is pending approval.
  - If product approval is pending, they can view how many of the product features have been approved out of the total.

---

#### **4. Customers**
**Description:**
- Customers are the end consumers of the product.

**Functions:**
- Customers can:
  - View the products.
  - Filter products based on various criteria such as:
    - Screen size (if applicable)
    - Weight
    - Model Number
    - Price
    - Ratings
    - Other relevant filters
  - Upon selecting a product, customers are redirected to the product dashboard, where they can view detailed information about the product.

**Product Dashboard Sections:**
- **Gallery:**
  - Contains both outside showcase and teardown showcase images and videos.
  
- **Specifications Section:**
  - Detailed specifications of the product.
  
- **Key Notes Section:**
  - Important notes regarding the product.
  
- **Performance Section:**
  - **Screen & Display:**
    - SDR brightness
    - HDR brightness
    - Gradient
    - Viewing Angle
    - Color Volume
  
- **Experience Section:**
  - Contains videos for showcase, post-purchase, and teardown.
  - **Showcase:**
    - Unboxing reviews (video)
    - Engineering reviews
    - Experience reviews
    - Performance reviews
  - **Post Purchase:**
    - Servicing & Maintenance
    - Troubleshooting
    - Repair & Replacement
  - **Teardown:**
    - Disassemble/Reassemble
    - Components Explanation
    - Customization
    - Right to repair
  
- **Review Section:**
  - Customer reviews and ratings.
  
- **Queries Section:**
  - FAQs related to the product.
  
- **Safety Section:**
  - Safety ratings and information about the product.

---
