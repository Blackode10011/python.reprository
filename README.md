# python.reprository
# Simples Ecommerce python 


# ''Using FastApi & Stripe'' 
```sh
Simples with python and Pa 
Building a simples Mini eCommerce
```
## _Requeriments_
-   environment set up
-   Install Dependences
-   Bootstrap
## _Install dependencies_
  ```sh
    $ virtualenv env
    $ source env/bin/activate
    $ pip install -r requirements.txt
```
## _Start your App_
```sh
    $ uvicorn src.app:app --reload
    Visit http://localhost:8000 in your browser. For another port, use --port 8099 directive.
```
## _Using Docker_
  ```sh
    $ git clone https://github.com/app-generator/ecommerce-fastapi-stripe.git
    $ cd ecommerce-fastapi-stripe
    $ docker-compose up --build 
```
 ```sh
    Visit http://localhost:8000 in your browser. The app should be up & running.
```
### _Create a new Product_
```sh
>  Go to src/templates/products directory
>  Create a new JSON file with data:
>  name: Used in product page & Cards
>  price: Used for payment
>  currency: Used for payment
>  info: used in cards
>  short_description: used in product page
>  full_description: used in product page
>  Create Media Files
>  Go to src/static/products
>  Create a directory using the same name as for JSON file
>  Create card.jpg: 500x335px
>  Create cover.jpg: 2100x1400px
>  Start or refresh the app
>  The new product should be listed in the products/ page
>  Product page is available at address:
>  http://localhost:8000/products/<SLUG>/ where the SLUG is the name of the JSON file
```
_By: DevOctavio_
