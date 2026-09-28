# Product Catalog — Product Backlog

## Product Backlog User Stories

### 1. Create a Product

**User Story**

As a catalog administrator, I need to create a product in the catalog, so that I can add new products for customers to discover.

**Acceptance Criteria**

- **Given** I am a catalog administrator  
  **When** I provide valid product information and submit the request  
  **Then** a new product is created and added to the catalog.

- **Given** I provide incomplete or invalid product information  
  **When** I submit the request  
  **Then** the product is not created and I receive a validation error.

---

### 2. Retrieve a Product

**User Story**

As a customer, I need to retrieve a product from the catalog, so that I can view its information and details.

**Acceptance Criteria**

- **Given** a product exists in the catalog  
  **When** I request the product using its valid product ID  
  **Then** the product details are returned.

- **Given** a product does not exist  
  **When** I request it using an invalid product ID  
  **Then** I receive an appropriate "product not found" response.

---

### 3. Update a Product

**User Story**

As a catalog administrator, I need to update a product in the catalog, so that I can keep product information accurate and up to date.

**Acceptance Criteria**

- **Given** a product exists in the catalog  
  **When** I submit valid updated product information  
  **Then** the product is updated with the new information.

- **Given** a product does not exist  
  **When** I attempt to update it  
  **Then** the product is not updated and I receive an appropriate error.

---

### 4. Delete a Product

**User Story**

As a catalog administrator, I need to delete a product from the catalog, so that I can remove products that are no longer available.

**Acceptance Criteria**

- **Given** a product exists in the catalog  
  **When** I request to delete the product  
  **Then** the product is removed from the catalog.

- **Given** a product does not exist  
  **When** I request to delete it  
  **Then** I receive an appropriate "product not found" response.

---

### 5. Like a Product

**User Story**

As a customer, I need to like a product in the catalog, so that I can express my interest in products I prefer.

**Acceptance Criteria**

- **Given** a product exists in the catalog  
  **When** I select "Like" for the product  
  **Then** the product's like count is increased and my like is recorded.

- **Given** I have already liked a product  
  **When** I select "Like" again  
  **Then** my like is not counted more than once.

---

### 6. Dislike a Product

**User Story**

As a customer, I need to dislike a product in the catalog, so that I can indicate that I am not interested in it.

---

### 7. List All Products

**User Story**

As a customer, I need to list all products in the catalog, so that I can browse the available products.

---

### 8. Query Products

**User Story**

As a customer, I need to query a subset of products in the catalog, so that I can find products matching specific criteria.

---

### 9. Cloud Hosting

**User Story**

As a business owner, I need the product catalog to be hosted in the cloud, so that it is accessible, scalable, and available to users.

> **Note:** This is technically a non-functional/system requirement rather than a traditional user story.

---

### 10. Automated Cloud Deployment

**User Story**

As a development team, I need automated deployment of new changes to the cloud, so that we can release updates quickly and consistently.

> **Note:** This is technically a technical/non-functional requirement rather than a traditional user story.

---

# Acceptance Criteria Summary

| # | Story | Acceptance Criteria |
|---|---|---|
| 1 | Create a Product | Valid product information creates a product; invalid information returns a validation error |
| 2 | Retrieve a Product | Valid product ID returns product details; invalid ID returns "product not found" |
| 3 | Update a Product | Existing product can be updated; non-existent product returns an error |
| 4 | Delete a Product | Existing product can be deleted; non-existent product returns "product not found" |
| 5 | Like a Product | Product can be liked; duplicate likes are not counted |

# Top 5 Stories

The Product Backlog is initially ordered as follows:

1. Create a Product
2. Retrieve a Product
3. Update a Product
4. Delete a Product
5. Like a Product

The first five stories have detailed acceptance criteria written using the **Given / When / Then** Gherkin syntax.
