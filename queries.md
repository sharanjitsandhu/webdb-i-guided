<!-- -- I want to see the name and city of all the customers
-- select City, CustomerName from customers

-- I want to see only customers from Berlin
-- select * from customers where Customerid > 29 and country = 'Spain'

-- all customer from Berlin and Spain
-- select * from customers where city = 'Berlin' or country = 'Spain'

-- all customers from Portland, Boise, Anchorage, Seattle
-- select * from customers where city in ('Portland', 'Seattle', 'Boise', 'Anchorage')

-- can I please get a list of customers from outside the USA and mexico?
-- select * from customers where country not in ('USA', 'Mexico')

-- a list of all our products with the most expensive at the top
-- select * from products order by price desc -- asc (default) or desc

-- a list of the 5 most expensive products we offer
-- select * from products order by price desc limit 5

-- a list of the 10 cheapest products we sale
-- select * from products order by price limit 10

-- how many items have been ordered across all orders
-- select count(*) from orderDetails

-- can I get a list of the countries where we have customers?
-- select distinct country from customers

-- using column aliases
-- select customerId as id, customerName as name, contactName as contact from customers

-- which cities begin with 'A', have any character after that and a 'c' as the third character?
-- select * from customers where city like 'A_c%' -->
