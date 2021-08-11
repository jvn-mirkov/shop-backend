# shop-backend


### [Customer]
| Routes        | Description           | 
| ------------- |:-------------:|
| [`GET/customers/`]    |Get list of all customers|
| [`GET/customers/{id}`]    | Get details of a particular customer |     
| [`POST/customers`]| Post a new customer |    
| [`PUT/customers/{id}`] | Update a particular customer |
| [`DELETE/customers/{id}`] |Delete a particular customer |

### [Item]
| Routes        | Description           | 
| ------------- |:-------------:|
| [`GET/items/`]    |Get list of all items |
| [`GET/items/{id}`]    | Get details of a particular item |     
| [`POST/items`]| Post a new item |    
| [`PUT/items/{id}`] | Update a particular item |
| [`DELETE/items/{id}`] |Delete a particular item |

### [Order]
| Routes        | Description           | 
| ------------- |:-------------:|   
| [`POST/customers/{customerId}/orders`]| Post a new order |    
| [`DELETE/customers/{customerId}/orders/{orderId}`] |Delete a particular order |
| [`POST/orders/{orderId}/items/{itemId}`]| Add item to order |    
| [`DELETE/orders/{orderId}/items/{itemId}`] |Delete item from order |
| [`GET/orders/{orderId}`]    | Get total price from order |    
