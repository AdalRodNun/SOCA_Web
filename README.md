# Context

SOCA Exchange is a startup focused on online clothing exchange, whose idea is to exchange clothes for points and points for clothes seeking to reduce the negative impact of the fast fashion trend, since the clothes they handle are clothes that can be reused, improving the environmental impact positively by not throwing away clothes that are no longer used and are in good condition.

As part of the growth of the startup, SOCA seeks to be able to automate its processes when registering new garments into their web page. Thats's how it was decided to create a Web Application to achieve a digital transformation of their inventory managment.


# Description

Web Platform to allow clothes segmentation and classification, with automatic assignment of points to the corresponding user, and registration on online inventory, with automatic generation of garment id, plus the ability to edit or delete an existing item in the inventory and the benefit of inventory export to an Excel file, for its next upload to existing WordPress store.

Main functions:

    -Register Garments
    -Generate Garment ID
    -Delete Garments
    -Visualize Inventory
    -Download Inventory as CSV
    -Register Users
    -Manage User Roles

There are two types of users:

    -Operator
    -Administrator


# App Design

### Login
<img src="https://user-images.githubusercontent.com/42302269/210919508-c6729d4a-d5e6-40fd-b931-6af7e050e771.png" width="700">

### Dashboard
<img src="https://user-images.githubusercontent.com/42302269/210919532-8d9acb29-32f0-4af4-a365-13171b2819b8.png" width="700">

### Register Garment
<img src="https://user-images.githubusercontent.com/42302269/210919497-22eb4e50-0551-4041-a831-6904b34a222c.png" width="700">

### Register User
<img src="https://user-images.githubusercontent.com/42302269/210919470-33285250-0f3b-4b87-ad68-003abbaab51b.png" width="700">

### Visualize Inventory
<img src="https://user-images.githubusercontent.com/42302269/210919482-fb550f3b-448f-4f1d-a3e0-7807982ee672.png" width="700">

### Manage User Roles
<img src="https://user-images.githubusercontent.com/42302269/210919525-8d4fd9a3-5cb3-44cb-b933-388e60027822.png" width="700">


# Architecture

The application was built with an architecture based on microservices and React library.

### High-level architecture of web platform:

<img src="https://user-images.githubusercontent.com/42302269/210912648-bf5102f9-ae48-4812-a7ad-e626e8a357a3.jpg" width="500">

### Microservices interaction:

<img src="https://user-images.githubusercontent.com/42302269/210918546-c5626e6c-6d1f-4959-9776-d1c5f3b37cf2.png" width="600">
