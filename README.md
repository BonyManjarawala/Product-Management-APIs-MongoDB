# Product-Management-APIs
# Product Management APIs ( Using MONGODB)

# SCHEMA:


PRODUCT 

* product id : String
* title : String
* price : String
* category : Array of String
* company id : String
* seller id : Array of String


COMPANY

* company id : String
* name : String
* product ids : Array of String


SELLER 

* seller id : String
* name : String
* product ids : Array of String


# POST REQUESTS:

ADD

* add new company
* add new seller
* add new product

RETRIEVE

* fetch company details based on product name
* fetch seller details based on product name
* fetch all products of a company
* fetch all products of a seller

UPDATE 

* update company (add/remove products)
* update seller (add/remove products)
* update product (add/remove category)

DELETE

* delete company
* delete seller
* delete product

# Screenshot
<a id="user-content-Screenshots" class="anchor" aria-hidden="true" href="#Screenshots"></a>

<a href="https://github.com/BonyManjarawala/Product-Management-APIs/tree/main/ProductManagementAPIS(Express)/Postman"> Click Here</a>
