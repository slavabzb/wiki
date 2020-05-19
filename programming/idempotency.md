# Idempotency

{% embed url="https://habr.com/ru/company/yandex/blog/442762/" %}

{% embed url="https://www.rabbitmq.com/reliability.html" caption="" %}

> In the event of network failure \(or a node failure\), messages can be [redelivered](https://www.rabbitmq.com/consumers.html#message-properties), and consumers must be prepared to handle deliveries they have seen in the past. It is recommended that consumer implementation is designed to be idempotent rather than to explicitly perform deduplication.



