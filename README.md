### apache-kafka
---
https://github.com/apache/kafka

https://kafka.apache.org/

```scala
// core/src/main/scala/kafka/consumer/BaseConsumerRecord.scala

@deprecated("This class has been deprecated and will be removed in a future in a future release. " +
  "Please use org.apache.kafka.clients.consumer.ConsumerRecord instead.", "0.11.0.0")
case class BaseConsumerRecord(topic: String,
  partition: Int,
  offset: Long,
  timestamp: Long = RecordBatch.NO_TIMESTAMP,
  timestampType: TimestampType = TimestampType.NO_TIMESTAMP_TYPE,
  key: Array[Byte],
  value: Array[Byte],
  headers: Headers = new RecordHeaders())

```

```
```

```
```


