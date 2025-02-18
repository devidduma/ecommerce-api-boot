# Spring Boot Store

Online store application backend written in Spring Boot. Data on items such as books, coffee mugs, mouse pads and luggage tags can be retrieved through this backend module from a MySQL database.

### Run project

Create a Maven run configuration with command line life cycle event `spring-boot:run`.

### API

API is made available under `localhost:8080/api`.
```
{
  "_links" : {
    "countries" : {
      "href" : "http://localhost:8080/api/countries{?page,size,sort}",
      "templated" : true
    },
    "products" : {
      "href" : "http://localhost:8080/api/products{?page,size,sort}",
      "templated" : true
    },
    "customer" : {
      "href" : "http://localhost:8080/api/customer{?page,size,sort}",
      "templated" : true
    },
    "productCategory" : {
      "href" : "http://localhost:8080/api/product-category{?page,size,sort}",
      "templated" : true
    },
    "states" : {
      "href" : "http://localhost:8080/api/states{?page,size,sort}",
      "templated" : true
    },
    "profile" : {
      "href" : "http://localhost:8080/api/profile"
    }
  }
}
```