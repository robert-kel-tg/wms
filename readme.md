1. Create policy, federation exchange
```bash
./downstream.sh
```
2. Emit message
```bash
go run emitter.go
```
3. Consumer message
```bash
go run receiver.go
```

#[Federated Exchange Example](https://jaxenter.com/distributed-log-aggregation-with-rabbitmq-federation-107287.html)

#[Shovel, Federated Exchange/Queue comparison](https://stackoverflow.com/questions/19357272/when-to-use-rabbitmq-shovels-and-when-federation-plugin)

#[Rabbitm federation Example1](https://www.cloudamqp.com/blog/2015-03-24-rabbitmq-federation.html)

#[Rabbitm federation Example2](https://www.cloudamqp.com/blog/2015-07-08-migrate-between-plans-rabbitmq-queue-federation.html)
