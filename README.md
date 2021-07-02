# URL-files
Application Name: crud-services
Port: 8201 , 820* 
End Points
http://localhost:8201/getAll-currency-mapping
http://localhost:8201/get-by-id/10001
http://localhost:8201/currency-exchange/from/USD/to/INR
http://localhost:8201/add-currency-mapping
http://localhost:8201/add-currency-mapping
http://localhost:8201/update-currency-mapping

-------------------------------------------------------------------

Naming Server
Application Name: naming-server 
Port: 8761
URL:http://localhost:8761/

-------------------------------------------------------------------

Application Name: currency-exchange-service
Port: 
End Points
http://localhost:8001/currency-exchange-proxy/from/EUR/to/INR
http://localhost:8001//getAll-currency-mapping
http://localhost:8001/get-by-id/10002
http://localhost:8001/add-currency-mapping
http://localhost:8001/update-currency-mapping-----issue
-------------------------------------------------------------------
Api Gateway
http://localhost:8765/crud-services/getAll-currency-mapping

http://localhost:8765/currency-exchange-service/get-by-id/10001
http://localhost:8765/currency-exchange-service/add-currency-mapping
http://localhost:8765/currency-exchange-service//update-currency-mapping
http://localhost:8765/currency-exchange-service/getAll-currency-mapping
http://localhost:8765/currency-exchange-service/delete-by-id/1

http://localhost:8765/currency-conversion-service/currency-conversion-feign/from/USD/to/INR/quantity/10


-------------------------------------------------------------------
Application Name: currency-conversion-service
Port: 8101
