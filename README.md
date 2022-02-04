# "ppbs-swagger-codegen" 

This proyect use swagger-codegen to generate the schema of api.

##Execute
mvn clean install

##API

### ecommerce

- GET /ecommerce
	- Get all ecommerce

- POST /ecommerce
	- Create new ecommerce

- DELETE /ecommerce/{id}
	- Delete Ecommmerce

- GET /ecommerce/{id}
	- Get ecommerce detail

- PUT /ecommerce/{id}
	- Update ecommerce

- POST /ecommerce/{id}/payment
	- Create new payment link to the ecommerce

- GET /ecommerce/{id}/report/{year}/{month}
	- Report monthly settlement Ecommerce

###Payment Processor
- POST /paymentprocessor
	- create new payment processor

- DELETE /paymentprocessor/{id}
	- Delete Payment Processor

- GET /paymentprocessor/{id}
	- Get Payment Processor detail

- PUT /paymentprocessor/{id}
	- Update Payment Processor

- GET /paymentprocessor/{id}/report
	- Report monthly

##Implementation
The implementation of the api is hosted in:

[https://github.com/dagasji/payment-processor-billing-system/](https://github.com/dagasji/payment-processor-billing-system/)
