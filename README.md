I connected to salesDB
I created a new normalized ProductDetail table
I inserted into the new normalized table

# 1NF table

Resulting table (1NF):

OrderID CustomerName Product
101 John Doe Laptop
101 John Doe Mouse
102 Jane Smith Tablet
102 Jane Smith Keyboard
102 Jane Smith Mouse
103 Emily Clark Phone

# 2NF table

I created tale orders
I inserted intto table orders
I created table orderitems
I inserted into table Orderitems resulting into a 2NF table

Orders Table:

OrderID CustomerName
101 John Doe
102 Jane Smith
103 Emily Clark

OrderItems Table:

OrderID Product Quantity
101 Laptop 2
101 Mouse 1
102 Tablet 3
102 Keyboard 1
102 Mouse 2
103 Phone 1
