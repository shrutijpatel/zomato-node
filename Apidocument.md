Page 1
 List of city
> http://localhost:6200/locations
> https://zomato-node.herokuapp.com/locations
 List of restaurants 
> http://localhost:6200/restaurants
> https://zomato-node.herokuapp.com/restaurants
 Restaurants wrt to city 
> http://localhost:6200/restaurants?state_id=2
> https://zomato-node.herokuapp.com/
 Quick search data  
> http://localhost:6200/mealTypes
> https://zomato-node.herokuapp.com/mealTypes


Page 2
> Restaurants wrt to quickSearch 
> http://localhost:6200/restaurants?meal_id=3
> https://zomato-node.herokuapp.com/restaurants?meal_id=3

> Filter
> Cuisine filter
> Data respect to cuisine and quickSearch 
> http://localhost:6200/filter/1?cuisine=1
> https://zomato-node.herokuapp.com/filter/1?cuisine=1
> Cost filter
> http://localhost:6200/filter/1?lcost=200&hcost=1000
> https://zomato-node.herokuapp.com/filter/1?lcost=200&hcost=1000
> Data respect to cuisine and cost 
> Cuisine filter + cost filter 
> http://localhost:6200/filter/1?lcost=200&hcost=1000&cuisine=1
> https://zomato-node.herokuapp.com/filter/1?lcost=200&hcost=1000&cuisine=1
>Sort
> Sort low to high in same quickSearch
> http://localhost:6200/filter/1?cuisineId=2&sort=1
> https://zomato-node.herokuapp.com/filter/1?cuisineId=2&sort=1
> Sort high to low in same quickSearch
> http://localhost:6200/filter/1?cuisineId=2&sort=-1
> https://zomato-node.herokuapp.com/filter/1?cuisineId=2&sort=-1
> Pagination
> https://zomato-node.herokuapp.com/filter/1?cuisineId=2&skip=0&limit=5

Page 3
> Restaurants details
> http://localhost:6200/details/1
> https://zomato-node.herokuapp.com/details/1
> Menu of that restaurants
> http://localhost:6200/menu/2
> https://zomato-node.herokuapp.com/menu/2

Page 4
> Menu items on user selection
> http://localhost:6200/menuItem
> https://zomato-node.herokuapp.com/menuItem
> Api to place order
> http://localhost:6200/placeorder
> https://zomato-node.herokuapp.com/placeorder

Page 5
> List all order
> http://localhost:6200/orders 
> https://zomato-node.herokuapp.com/orders
> Delete order 
> http://localhost:6200/deleteOrder
> https://zomato-node.herokuapp.com/deleteOrder
> Update order
> http://localhost:6200/updateorder/620a79376c2555fe034473fd
