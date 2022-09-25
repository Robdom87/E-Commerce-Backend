# E-commerce Back End 

## Description

The purpose of this project is to create a simple back end routing for an e-commerce site, or in other words an API.

The user can view, add, update, and delete the following subjects: Catergories, Products, and Tags to the database. A catergory can have multiple products, but a product can only have one catergory. A product can have multiple tags, and a tag can have multiple products.

Below is the functionality provided alongside the appropriate routing.

View All Catergories
GET Request: https://example.com/api/catergories/

View Select Catergory
GET Request: https://example.com/api/catergories/:id

Add a Catergory
POST Request: https://example.com/api/catergories/

With the following JSON Body:
{
    "category_name" : "sampleName"
}

Update a Catergory
PUT Request: https://example.com/api/catergories/:id

With the following JSON Body:
{
    "category_name" : "updatedName"
}

Delete a Catergory
DELETE Request: https://example.com/api/catergories/:id

View All Products
GET Request: https://example.com/api/products/

View Select Product
GET Request: https://example.com/api/products/:id

Add a Product
POST Request: https://example.com/api/products/

With the following JSON Body:
{
    "product_name" : "sampleName",
    "price": 200.00,
    "stock": 3,
    "tagIds": [1, 2, 3, 4]
}

Update a Product
PUT Request: https://example.com/api/products/:id

With the following JSON Body:
{
    "product_name" : "updatedName",
    "price": 200.00,
    "stock": 3,
    "tagIds": [1, 2, 3, 4]
}

Delete a Product
DELETE Request: https://example.com/api/products/:id

View All Tags
GET Request: https://example.com/api/tags/

View Select Tag
GET Request: https://example.com/api/tags/:id

Add a Tag
POST Request: https://example.com/api/tags/

With the following JSON Body:
{
    "tag_name" : "sampleName"
}

Update a Tag
PUT Request: https://example.com/api/tags/:id

With the following JSON Body:
{
    "tag_name" : "updatedName"
}

Delete a Tag
DELETE Request: https://example.com/api/tag/:id

## Walkthrough Video

https://drive.google.com/file/d/1Aj0TVXyV4vsB6gI8NZy9QwJ84Gl0uUKU/view

