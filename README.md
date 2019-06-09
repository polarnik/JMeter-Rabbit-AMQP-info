# Rabbit MQ Apache.JMeter

## Main project

https://github.com/jlavallee/JMeter-Rabbit-AMQP

| Last commit | JMeter | Amqp  | Commits | Star | Watch | Issues | Pull Requests | Branches |
| ----------- | ------ | ----- | ------: | ---: | ----: | -----: | ------------: |--------: |
| 2016-05-17  | 2.11   | 3.5.1 | 74      | 99   | 15    | 21     | 9             | 2        |


### Pull Requests (2019-06-08)

| Change | URL | From |
| ------ | --- | ---- |
| docker support https://wilsonmar.github.io/jmeter-install/                | [53](https://github.com/jlavallee/JMeter-Rabbit-AMQP/pull/53) | [wilsonmar](https://github.com/wilsonmar/JMeter-Rabbit-AMQP) |
| Add support for custom channel features                                   | [48](https://github.com/jlavallee/JMeter-Rabbit-AMQP/pull/48) | [voytek-solutions](https://github.com/voytek-solutions/JMeter-Rabbit-AMQP/tree/dead-letters) |
| Adding x-max-priority queue attribute and correcting issue 41             | [42](https://github.com/jlavallee/JMeter-Rabbit-AMQP/pull/42) | [gregLibert](https://github.com/gregLibert/JMeter-Rabbit-AMQP) |
| Maven, x-dead-letters-exchange, JSON Object                               | [32](https://github.com/jlavallee/JMeter-Rabbit-AMQP/pull/32) | [sergiogouveia](https://github.com/sergiogouveia/JMeter-Rabbit-AMQP) |
| Add RPC-Client sampler                                                    | [31](https://github.com/jlavallee/JMeter-Rabbit-AMQP/pull/31) | [devTransition](https://github.com/devTransition/JMeter-Rabbit-AMQP) |
| Add an option to share connection and channel between Samplers            | [30](https://github.com/jlavallee/JMeter-Rabbit-AMQP/pull/30) | [rbnxx](https://github.com/rbnxx/JMeter-Rabbit-AMQP) |
| Add x-message-ttl                                                         | [29](https://github.com/jlavallee/JMeter-Rabbit-AMQP/pull/29) | [conkeyn](https://github.com/conkeyn/JMeter-Rabbit-AMQP/tree/Add_exchange_and_queue_parameters) |
| Add a Maven POM, preconfigured for deploying to https://oss.sonatype.org/ | [16](https://github.com/jlavallee/JMeter-Rabbit-AMQP/pull/16) | [peterjanes](https://github.com/peterjanes/JMeter-Rabbit-AMQP) |


### Issues (2019-06-08)

* Does not work for dynamic work queues
* Does not work with Auto-delete exchanges
* Missing 'app_id' and 'timestamp' properties
* AMQP Consumer stays active for duration of Test Plan (multiple AMQP Consumer in same Thread Group)
* AMQP Consumer exception (no header in reply-to message.)
* 30,000 messages published instead of 1 when using Stepping Thread Group or Concurrency Thread Group
* cannot show on Jmeter 5.0

## Existing plugins (2019-06-08)


| From                                                                         | Last commit | Fork date       | JMeter | Amqp  | Commits | Star | Watch | Change |
| ---------------------------------------------------------------------------- | ----------- | --------------- | ------ | ----- | ------: | ---: | ----: |------- |
| [jlavallee](https://github.com/jlavallee/JMeter-Rabbit-AMQP)                 | 2016-05-17  |                 | 2.11   | 3.5.1 | 74      | 99   | 15    | | 
| [zeph1rus](https://github.com/zeph1rus/JMeter-Rabbit-AMQP)                   | 2018-10-24  | 2016-05-17 (74) | 5.0    | 4.8.3 | 85      | 1    | 0     | Added options to manage heartbeat |
| [aliesbelik](https://github.com/aliesbelik/JMeter-Rabbit-AMQP)               | 2018-09-26  | 2015-04-15 (70) | 4.0    | 5.4.1 | 80      | 3    | 2     | Maven, amqp v5.4.1, detault content type: text/plain utf-8, Add support for AMQP queue (x-max-priority) & message priority |
| [sergiogouveia](https://github.com/sergiogouveia/JMeter-Rabbit-AMQP)         | 2017-10-26  | 2015-04-15 (70) | 2.13   | 3.6.0 | 79      | 3    | 3     | Maven, x-dead-letter-exchange, Response as JSON, added gziped consumed messages decode |
| [wilsonmar](https://github.com/wilsonmar/JMeter-Rabbit-AMQP)                 | 2018-01-23  | 2016-05-17 (74) | 2.11   | 3.5.1 | 172     | 4    | 1     | docker support https://wilsonmar.github.io/jmeter-install/ |
| [wc-martin](https://github.com/wc-martin/JMeter-Rabbit-AMQP)                 | 2017-02-06  | 2015-04-15 (70) | 2.11   | 3.5.1 | 73      | 1    | 0     | Acknowledgement Mode: Confirmation |
| [voytek-solutions](https://github.com/voytek-solutions/JMeter-Rabbit-AMQP)   | 2017-08-21  | 2016-05-17 (74) | 2.11   | 3.5.1 | 76      | 1    | 0     |  Add support for custom channel features: You can explicitly set x-expires, x-message-ttl and other arguments. |
| [thburnett](https://github.com/thburnett/JMeter-Rabbit-AMQP)                 | 2018-06-15  | 2016-05-17 (74) | 2.11   | 3.5.1 | 76      | 1    | 1     |  Avoid adding replyto and correlation id headers when empty |
| [geniussportsgroup](https://github.com/geniussportsgroup/JMeter-Rabbit-AMQP) | 2015-08-12  | 2014-08-29 (54) | 2.13   | 3.3.4 | 60      | 1    | 11    | Maven, added headers to amqp publisher as JSON string |
| [miaosp](https://github.com/miaosp/JMeter-Rabbit-AMQP)                       | 2017-04-21  | 2016-05-17 (74) | 2.11   | 3.5.1 | 77      | 1    | 1     | Maven, add tls support: TLSv1.1 with keystore file |
| [gregLibert](https://github.com/gregLibert/JMeter-Rabbit-AMQP)               | 2017-05-03  | 2016-05-17 (74) | 2.11   | 3.5.1 | 77      | 1    | 1     |  Correcting no header in reply-to message, Adding x-max-priority field to queue parameters, Adding message priority and delivery mode to amqp publisher | 
| [looseend](https://github.com/looseend/JMeter-Rabbit-AMQP)                   | 2017-03-06  | 2016-05-17 (74) | 2.11   | 3.5.1 | 77      | 1    | 0     |  Added support for x-max-priority |

