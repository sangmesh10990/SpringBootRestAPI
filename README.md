# SpringBootRestAPI
Demo Application for accessing Exchange rates of EURO against foreign exchange(used https://ratesapi.io/documentation/ as data source)
# Swagger URL : http://localhost:8080/swagger-ui.html#/
# Rest END : http://localhost:8080/currentRate

For Access API need to login:
uname : username
password : password


#Go to Application resource folder :
#you can change this api credentils by editing properties file in resource folder of project
#Credentilas for Accessing API
api.username=username
api.password=password

Use properties file to set Currency for current and historical foreign exchange rates.
#No of month need to check past data
past.requiredMonth=6
#baseURl
rest.api.io.baseURL=https://api.ratesapi.io/api/
#Base Currency
rest.api.io.base=USD
#Required Rate against
rest.api.io.symbols=INR,GBP,HKD

