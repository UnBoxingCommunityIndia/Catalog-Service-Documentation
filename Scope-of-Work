sequenceDiagram
    participant Engineer
    participant User
    participant Admin
    participant Customer
    participant CatalogueService
    participant Database

    Engineer->>CatalogueService: Add Product Specifications
    CatalogueService->>Database: Insert Product Details
    Database-->>CatalogueService: Acknowledgement
    CatalogueService-->>Engineer: Product Added Successfully

    Engineer->>CatalogueService: Add Product Showcase
    CatalogueService->>Database: Insert Showcase Data
    Database-->>CatalogueService: Acknowledgement
    CatalogueService-->>Engineer: Showcase Added Successfully

    User->>CatalogueService: Validate Product
    CatalogueService->>Database: Update Validation Status
    Database-->>CatalogueService: Acknowledgement
    CatalogueService-->>User: Validation Completed

    User->>CatalogueService: Replace Product Feature
    CatalogueService->>Database: Update Product Feature
    Database-->>CatalogueService: Acknowledgement
    CatalogueService-->>User: Feature Replaced

    Admin->>CatalogueService: View Pending Approvals
    CatalogueService->>Database: Fetch Pending Products
    Database-->>CatalogueService: Return Pending Products
    CatalogueService-->>Admin: Display Pending Products

    Admin->>CatalogueService: Approve Product
    CatalogueService->>Database: Update Approval Status
    Database-->>CatalogueService: Acknowledgement
    CatalogueService-->>Admin: Product Approved

    Customer->>CatalogueService: View Products
    CatalogueService->>Database: Fetch Product List
    Database-->>CatalogueService: Return Product List
    CatalogueService-->>Customer: Display Products

    Customer->>CatalogueService: Filter Products
    CatalogueService->>Database: Fetch Filtered Products
    Database-->>CatalogueService: Return Filtered Products
    CatalogueService-->>Customer: Display Filtered Products

    Customer->>CatalogueService: View Product Details
    CatalogueService->>Database: Fetch Product Details
    Database-->>CatalogueService: Return Product Details
    CatalogueService-->>Customer: Display Product Details
