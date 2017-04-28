# FoodDeliveryApplication

This is a food delivery application. 

## Design
There are four services:
1. RestaurantSearchService
2. OrderService
3. PaymentService
4. DeliveryService

## Data Storage
Use MySQL in this application

## RestaurantSearchService
Use Http Get request    
Endpoint: "/restaurantinfomation/{restaurantName}"

## OrderService
Use Http Post request    
Endpoint: "/{restaurantName}/order"    
Order information is in the Http body.

## PaymentService
Use Http Post request    
Endpoint: "/payment"    
Order information and payment information is in the Heep body

## DeliveryService
Use Http Get request    
Endpoint: "/deliveryinformation/{orderId}" or "/deliveryinformation/{UserName}"
