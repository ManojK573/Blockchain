## Build an Image ##

```docker build --tag manoj .```


## Run an image ##

```docker run --name x21218315 -p 8090:8080 manoj```

## Run the curl command ##

This transfers ETH:

```curl -i -X POST -H "Content-Type: application/json" -d '{\"address\": \"destination address\",\"amount\":\"desired amount\"}' http://localhost:8090/token```

##This will transfer the desired amount of ethereum from owner account to destination account. 

This transfers token:

```curl -i -X POST -H "Content-Type: application/json" -d '{\"address\": \"destination address\"}' http://localhost:8090/token```
#This will tranfer the ERC20 tokens from owner account to desired account.

