# ANIMATED SPOONS: Credit Card Validator

* This is going to:
  * use the Luhn Algorithm to validate credit card numbers
  * Will be part of a microservice
  * functionality will be part of a JSON exposed API
    * maybe v2 using GRPC


### Requirements
* Implement the Luhn algorithm
  * Build tests
  * __MAYBE__: implement CI to run said tests
* Create an HTTP server
* Configure the server to respond to GET requests having a JSON payload
* Accept valid JSON requests and proceed to step 5, whilst rejecting invalid requests using an HTTP 400 status code
* Extract the credit card number from the JSON payload
* Run the Luhn algorithm on the number
* Wrap the result into a JSON response payload
* Return the payload back to the user through the HTTP server

### Stretch Goals
* Report the identified card network (if any) in your JSON response
* Identify credit card numbers used by primary payment networks that operate in your regions, such as RuPay, UnionPay, JCB, Discover, EPI, or others

