# StockManagementEngine

#PreRequisties
Postman client is recommended to be installed to test input and output of this applicaion. The endpoints (urls) are given on top of the endpoint methods in restcontroller.

#Sample products to help start with
[ {"productName":"Apples", "price":1.00, "currentStock":10,"additionalVolume":0,"minimumStockLevel":8,"orderState":"BLOCKED"},
{"productName":"Bread", "price":1.00, "currentStock":4,"additionalVolume":0,"minimumStockLevel":10,"orderState":"ALLOWED"},
{"productName":"Milk", "price":1.00, "currentStock":0,"additionalVolume":10,"minimumStockLevel":18,"orderState":"ALLOWED"},
{"productName":"Eggs", "price":1.00, "currentStock":5,"additionalVolume":0,"minimumStockLevel":6,"orderState":"BLOCKED"} ]

#Note
1. The h2 database is utilised in this application, you can access it with "http://localhost:8080/h2-console/login.do?jsessionid=3e73b3079127dcebebfc07e1046c01a6"

2. The product table is dropped eachtime the application starts at the moment to give flexibility to test various input stratagies
3. end-to-end testing is done in this project
