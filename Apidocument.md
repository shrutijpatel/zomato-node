Page 1
List of city
> http://localhost:6200/locations
>
List of restaurants 
> http://localhost:6200/restaurants
>
restaurants wrt to city 
> http://localhost:6200/restaurants?state_id=2
>
quick search data  
> http://localhost:6200/mealTypes
>


Page 2
restaurants wrt to quickSearch 
> http://localhost:6200/restaurants?meal_id=3
>

filter
> cuisine filter
  data respect to cuisine and quickSearch 
  > http://localhost:6200/filter/1?cuisine=1
  >
> cost filter
  > http://localhost:6200/filter/1?lcost=200&hcost=1000
  >
 data respect to cuisine and cost 
> cuisine filter + cost filter 
  > http://localhost:6200/filter/1?lcost=200&hcost=1000&cuisine=1
  >
> sort
    sort low to high in same quickSearch
    > http://localhost:6200/filter/1?cuisineId=2&sort=1
    >
    sort high to low in same quickSearch
    > http://localhost:6200/filter/1?cuisineId=2&sort=-1
    >
> pagination
   > http://localhost:6200/filter/1?cuisineId=2&skip=0&limit=5


Page 3
> restaurants details
> http://localhost:6200/details/1
>
> Menu of that restaurants
> http://localhost:6200/menu/2
>

page 4
> menu items on user selection
  > http://localhost:6200/menuItem
  > 

> api to place order
  > http://localhost:6200/placeorder
  >
page 5
> list all order
  > http://localhost:6200/orders
  >

Delete order 
> http://localhost:6200/deleteOrder
 

 update order
 > http://localhost:6200/updateorder/620a79376c2555fe034473fd