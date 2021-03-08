# Reprodution of a sarama/AEH (Azure Event Hub) bug

[Github issue link](https://github.com/Shopify/sarama/issues/1540)

```
error consuming from group kafka: response did not contain all the expected topic/partition blocks
exit status 1
```

[consumer-with-sarama](consumer-with-sarama) - using original sarama 1.28.0 module
[consumer-with-sarama-fork](consumer-with-sarama-fork) - using a fork with a suggested fix