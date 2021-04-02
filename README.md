ADempiere Web Stack
==============

<div align="center">
	<img src="https://camo.githubusercontent.com/911c5d54ded447403e56de3f96f332c06bceb8bd/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f622f62312f4164656d70696572652d6c6f676f2e706e67" style="text-align:center;" width="400" />
</div>


### For all enviroment you should run the follow images:

- ADempiere gRPC: https://hub.docker.com/r/erpya/adempiere-grpc-all-in-one
```shell
docker pull erpya/adempiere-grpc-all-in-one
```

- Proxy ADempiere API: https://hub.docker.com/r/erpya/proxy-adempiere-api
```shell
docker pull erpya/proxy-adempiere-api
```

- ADempiere Vue: https://hub.docker.com/r/erpya/adempiere-vue
```shell
docker pull erpya/adempiere-vue
```

- ADempiere eCommerce: https://hub.docker.com/r/erpya/adempiere-ecommerce
```shell
docker pull erpya/adempiere-ecommerce
```


## Run Docker Stack

```shell
docker-compose up
```

Containers Running:
* AD_GRPC_Sever
* AD_Redis
* AD_ElasticSearch
* AD_Proxy_API
* AD_Vue
* AD_ECommerce
