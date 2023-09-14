# spring-new-rest-client

## POST
```
curl --location 'http://localhost:8080/product-client/products' \
--header 'Content-Type: application/json' \
--data '{
        "name": "Watter bottle",
        "price": 299.0,
        "description": "BOROSIL NEW MODEL",
        "productType": "Baby&Kids"
    }'
```

## GET
```
curl --location 'http://localhost:8080/product-client/products' \
--data ''
```

## PUT
```
curl --location --request PUT 'http://localhost:8080/product-client/products/1' \
--header 'Content-Type: application/json' \
--data '{
    "name": "Mobile",
    "price": 10500,
    "description": "SAMSUNG Galaxy F13 (Sunrise Copper, 64 GB)",
    "productType": "Electronics"
}'
```

## DELETE
```
curl --location --request DELETE 'http://localhost:8080/product-client/products/1' \
--data ''
```
